<template>
    <div class="op1">
        <img :src="imageUrl" alt="My Image">
        <p class="tit">{{ title }}</p>
        <div class="rec">
            <h3>{{ title1 }}</h3>
            <p>{{ title2 }}</p>
        </div>
        <div class="infoCor">
          <div class="p1">
            <img class="timet" src="./assets/schedule-24px.png"/>
          <p >{{ title3 }}</p>
          </div>
          

          <div class="p2"> <img  class="NoL" src="./assets/date_range-24px.png"/>
          <p >{{ title4 }}</p>

          </div>
         
        </div>
    </div>
</template>

<script >
export default {
     name: "AppProduct",
     props: {
    title: {
      type: String,
      required: true
    },
    imageUrl: {
      type: String,
      required: true
    },
    title1:{
     type: String,
     required:true
    },
    title2:{
     type: String,
     required:true
    },
    title3:{
     type: String,
     required:true
    },
    title4:{
     type: String,
     required:true
    }
  }
};
</script>

<style scoped>
 .op1{
   width: 33%;
   background: #FFFFFF 0% 0% no-repeat padding-box;
border: 1px solid #E6E6E6;
border-radius: 15px;
opacity: 1;
margin:0.8rem;
 }
  .op1 img{
    width: 500px;
height: 300px;
background: transparent  0% 0% no-repeat padding-box;
border-radius: 15px 15px 0px 0px;
opacity: 1;

  }
  .tit{
    text-align: left;
font: normal normal bold 25px/34px Noto Sans;
letter-spacing: 0px;
color: #1F2532;
opacity: 1;
width: 80%;
margin:1rem
  }
  .tit1{
    text-align: left;
letter-spacing: 0px;
color: #1F2532;
opacity: 1;
  }
  .rec{
    margin-top:-1rem;
    display: flex;
    flex-direction: row;
    align-content: space-between;
    align-content: space-around;
    margin:1rem;
  }
  .rec h3{
    text-align: left;
font: normal normal bold 16px/22px Noto Sans;
letter-spacing: 0px;
color: #1F2532;

  }
  .rec p{
    padding-left:10px;
    text-align: left;
font: italic normal normal 16px/22px Noto Sans;
letter-spacing: 0px;

  }
  .infoCor{
    
    display: flex;
    flex-direction: row;
   
  }
  .infoCor .timet{
    width: 24px;
height: 24px;
/* UI Properties */
background: transparent  0% 0% no-repeat padding-box;
opacity: 1;
  }
  .infoCor .NoL{
    width: 24px;
height: 24px;
/* UI Properties */
background: transparent  0% 0% no-repeat padding-box;
opacity: 1;
padding-left: 1rem;
  }
  .infoCor p{
    text-align: left;
font: italic normal bold 15px/20px Noto Sans;
letter-spacing: 0px;
color: #86919D;
opacity: 1;
margin-top: 0.2rem;
margin-left: 5px;
  }
  .p1{
    padding-left:10px ;
    display: flex;
    flex-direction: row;
    
  }
  .p2{
    display: flex;
    flex-direction: row;
    padding-left: 16rem;
    padding-left:15rem;
  }
  @media (max-width: 768px) {
    .op1 {
      width: 100%;
    }
    
    .op1 img {
      width: 100%;
      height: auto;
    }

    .infoCor {
      flex-direction: column;
    }

    .p1,
    .p2 {
      padding-left: 10px;
    }

    .p2 {
      padding-left: 10px;
    }
  }
</style>