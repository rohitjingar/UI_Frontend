<template>
   <div class="fam1">
      <div class="fam2">
        <div class="fam3">
         <p>Total Students</p>
         <h1>5140</h1>
         <div class="strip">

         </div>
        </div>
        <div class="fam4">
            <p>Partners</p>
         <h1>4123</h1>
         <div class="strip"></div>
        </div>
        <div class="fam5">
            <p>Affiliate Distribution</p>
         <h1>4.18 Lac</h1>
         <div class="strip"></div>
        </div>
      </div>
   </div>
</template>

<script >
export default {
     name: "AppFamily",
};
</script>

<style scoped>
   .fam1{
    width: 100%;
    background: transparent url('./assets/group_item.png') 0% 0% no-repeat padding-box;
    opacity: 1;
   }
   .fam2{
    width:100%;
    display: flex;
    flex-direction: row;
   }
   .fam2 p{
    width: 100%;
    height: 47px;
    font: normal normal bold 35px/47px Noto Sans;
    letter-spacing: 0px;
    color: rgba(134, 145, 157, 1);
    opacity: 1;
   }
   .fam2 h1{
    margin-top: -1rem;
    width: 100%;
    height: 88px;
    font: normal normal bold 65px/88px Noto Sans;
    letter-spacing: 0px;
    color: rgba(31, 37, 50, 1);
    opacity: 1;
   }
   .fam3{
    padding-left: 8rem;
    width: 33%;
   }
   .fam4{
    padding-left: 8rem;
     width: 33%;
   }
   .fam5{
     width: 33%;
   }
   .strip{
    width: 140px;
    height: 7px;
    margin-top: -1.5rem;
    margin-bottom: 3rem;
    background: rgba(1, 203, 99, 1) 0% 0% no-repeat padding-box;
    opacity: 1;
   }
   
   .fam5 .strip{
    width: 252px;
   }
   @media screen and (max-width: 1224px) {
     .fam1{
      width: 100%;
    background: transparent url('./assets/group_item.png')  ;
    opacity: 1;
       height: 100%;
     }
    .fam2 {
      flex-direction: column;
      justify-content: center;
      align-items: center;
      width:1224;
      height: 1224px;
    }
    .fam5{
      margin: 1rem;
      padding: 1rem;
    }
    .fam5 p{
      margin: 2rem;
      padding: 1rem;
    }
    .fam5 h1{
      margin: 2rem;
      padding: 1rem;
    }
    .fam5 .strip{
      margin-left: 3rem;
    }
   
  }

  
</style>