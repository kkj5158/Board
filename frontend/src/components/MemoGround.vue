<template>
  <div class="ground">
    <Header/>
    <Memo/>
    <Footer/>
  </div>
</template>

<script>
import Header from "./MemoHeader.vue";
import Footer from "./MemoFooter.vue";
import Memo from "./MemoBody.vue";

export default {
  components:{Header, Footer, Memo}
}
</script>