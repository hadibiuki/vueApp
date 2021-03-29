<template>
    <div>
      <the-header></the-header>
      <card-info></card-info>
      <gallry></gallry>
      <comment></comment>
      <contact></contact>
      <the-footer></the-footer>
    </div>
    
</template>


<script>
import TheHeader from './components/layout/TheHeader.vue';
import TheFooter from './components/layout/TheFooter.vue';
import CardInfo from './components/CardInfo/CardInfo.vue';
import Gallry from './components/Gallery/Gallery.vue';
import Comment from './components/Comment/Comment.vue';
import Contact from './components/Contact/Contact.vue';

export default {
  components:{TheHeader,CardInfo,Gallry,Comment,Contact,TheFooter}
}
</script>


<style>

:root{
  --perpel : #754EF9;
  --white:#FFFFFF;
  --black:#101010;
}

*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

body{
  overflow-x: hidden;
}
button{
  border: none;
  outline: none; 
  cursor: pointer;
}

</style>