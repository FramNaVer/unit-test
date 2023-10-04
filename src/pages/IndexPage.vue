<template>
  <div class="htmlClass">
    <h1>{{ title }}</h1>
  </div>
  <InputPage/>
  <FuctionPage/>

</template>


<script>
import InputPage from '../pages/InputPage.vue';
import FuctionPage from '../pages/FunctionPage.vue';

export default {
    name: 'HtmlComponent',
    compenent: {
        InputPage,
        FuctionPage
    },
    data() {
        return {
            title: 'Tanadon Inmano 340',
        };
    },
    components: { InputPage,FuctionPage }
}
</script>

<style scoped></style>
