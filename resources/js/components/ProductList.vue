<template>
    <div>
        <div class="vw-100">
            <div class="row">
                <div v-for="product in products" class="col-lg-4 col-md-6 col-sm-12">
                    <img src="/img/logo.png" alt="">
                </div>
                
            </div>
            
            
        </div>
    </div>
</template>

<script>
    export default{
        name: "productList",
        props: ["products"]
    }
</script>