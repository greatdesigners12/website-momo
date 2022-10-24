<template>
    <div>
        
        <div class="row d-flexr">
            <div v-for="product in products" class="col-lg-3 col-md-6 col-sm-12">
                <ProductCard imgUrl="/img/logo.png" contentText="Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum enim repellendus magni sapiente perspiciatis dignissimos optio, architecto sint voluptates eius, ea natus porro maxime eaque, officia itaque! Obcaecati, itaque perferendis!" />
            </div>
        </div>
          
    </div>
</template>

<script>
    import ProductCard from "./ProductCard.vue";

    export default{
        name: "productList",
        props: ["products"],
        components: { ProductCard, ProductCard }
    }   
</script>