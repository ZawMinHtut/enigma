<template>
    <div>
        <Header></Header>
        <IndexContent/>
        <Footer/>
    </div>
</template>

<script>
import Header from '@/components/index/Header.vue';
import IndexContent from '@/components/index/IndexContent.vue';
import Footer from '@/components/index/Footer.vue';;
import scss from '../../assets/scss/index.scss';
export default {
    name: 'Home',
    components: {
        Header, IndexContent, Footer
    }
}
</script>

