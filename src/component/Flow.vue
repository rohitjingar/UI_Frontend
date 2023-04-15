<template>
    <div class="op1">
        <div class="Flow_Intro">
         <p>
            Refer
         </p>
         <h1>
            How it's Work
         </h1>
      </div>
      <img class="svgimg" src="./assets/Flow.svg.svg" alt="FLow1"/>
    </div>
</template>

<script >
export default {
     name: "AppFlow",
    
};
</script>
<style scoped>
.Flow_Intro{
    margin-top:8rem;
    margin-left: 2rem;
   }
  .Flow_Intro p{
    text-align: left;
font: italic bold  25px/34px Noto Sans;
letter-spacing: 0px;
color: #01CB63;
opacity: 1;
  }
  .Flow_Intro h1{
    margin-top: -1rem;
    text-align: left;
font: normal normal bold 40px/54px Noto Sans;
letter-spacing: 0px;
color: #1F2532;
text-transform: capitalize;
opacity: 1;
  }
  .svgimg{
    width:100%;
    height: 100%;
/* UI Properties */
background: transparent  0% 0% no-repeat padding-box;
opacity: 1;
  }
  @media only screen and (max-width: 700px) {
    .op1{
      width: 100%;
    }
    .Flow_Intro {
        margin-top: 4rem;
        margin-left: 1rem;
    }

    .Flow_Intro p {
        font-size: 20px;
    }

    .Flow_Intro h1 {
        font-size: 30px;
    }
}

@media only screen and (max-width: 480px) {
    .Flow_Intro {
        margin-top: 2rem;
        margin-left: 1rem;
    }

    .Flow_Intro p {
        font-size: 16px;
    }

    .Flow_Intro h1 {
        font-size: 24px;
    }
  }
</style>