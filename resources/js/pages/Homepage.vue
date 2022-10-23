<template>
    <div>
        <HeaderComponent />
        <div class="100vw">
            <div class="row">
                <div class="col-10 d-flex justify-content-center align-items-center flex-column">
                    <h1 class="internBoldText">BELANJA ACCESSORIS</h1>
                    <h1 class="internBoldText text-primary">TERLENGKAP DAN TERMURAH</h1>
                    <button class="btn btn-primary w-50 d-flex align-items-center justify-content-center">
                        <h2 class="mb-0">BELANJA SEKARANG</h2>
                    </button>
                </div>
                <div class="col-2">
                    <img id="bagImg" src="/img/shopping bag.png" class="float-end" alt="">
                </div>
            </div>
        </div>
        <ProductListComponent :products="skills"></ProductListComponent>

    </div>
</template>

<script>
import HeaderComponent from "../components/header.vue";
import ProductListComponent from "../components/ProductList.vue";
export default {
    components: { HeaderComponent, ProductListComponent },
    data() {
        return {
            skills: [
                {
                    name: 'Frozen Yogurt',
                    required: 1,
                    vMode1: ''
                },
                {
                    name: 'Ice cream sandwich',
                    required: 3,
                    vMode1: ''
                },
                {
                    name: 'Eclair',
                    required: 1,
                    vMode1: ''
                },
                {
                    name: 'Frozen Yogurt',
                    required: 1,
                    vMode1: ''
                },
                {
                    name: 'Ice cream sandwich',
                    required: 3,
                    vMode1: ''
                },
                {
                    name: 'Eclair',
                    required: 1,
                    vMode1: ''
                }
            ]
        }
    }
}
</script>

<style scoped>
@font-face {
    font-family: "Inter-Bold";
    src: local("Inter-Bold"), url(./font/Inter-Bold.otf) format("truetype");
}

.internBoldText {
    font-family: "Inter-Bold";
}

.w-60 {
    width: 60%;
}

#bagImg {
    width: 300px;
    height: auto;
}
</style>