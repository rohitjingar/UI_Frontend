<template>
    <div class="op1">
      <img :src="imageUrl" alt="My Image">
      <div class="op2">
        <img src="./assets/ter.png"/>
        <p class="tit">{{ title }}</p>
      </div>
    </div>
</template>

<script >
export default {
     name: "AppCharacter",
     props: {
    title: {
      type: String,
      required: true
    },
    imageUrl: {
      type: String,
      required: true
    }
  }
};
</script>

<style scoped>
  .op1{
    width:25%;
  }
  .op2{
    display: flex;
    flex-direction: row;
    padding-top:5px;
  }
  .op2 p{
    text-align: left;
font: normal normal bold 25px/35px Noto Sans;
letter-spacing: 0px;
color: #1F2532;
opacity: 1;
padding-left:1rem;
  }
</style>