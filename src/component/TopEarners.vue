<template>
    <div>
      <div class="Earners_Intro">
         <p>
            Top Earners
         </p>
         <h1>
            Transformng your ideas into reality
         </h1>
 
      </div>
 
     <div class="Earners_t">
       <Character
        :image-url="require('./assets/per1.png')"
        title="₹8,00,000"
       
       />
       
       <Character
       :image-url="require('./assets/per2.png')"
        title="₹6,00,000"
        
       />
       <Character
       :image-url="require('./assets/per3.png')"
        title="₹5,00,000"
       
        />
        <Character
       :image-url="require('./assets/per4.png')"
        title="₹4,50,000"
       
        />
     </div>
  </div>
     
     
   </template>
   
   <script>
  import Character from "./Character.vue"
   
   export default {
     name: "AppTopEarners",
     components: {
       Character
     }
   };
  
   </script>

   <style scoped>
   .Earners_Intro{
    margin-top:10rem;
   }
   .Earners_Intro p{
    text-align:left;
font: normal normal normal 25px/34px Noto Sans;
letter-spacing: 0px;
color: #01CB63;
opacity: 1;
  }
  .Earners_Intro h1{
    width:35%;
    text-align:left;
font: normal normal bold 40px/54px Noto Sans;
letter-spacing: 0px;
color: #1F2532;
text-transform: capitalize;
opacity: 1;
  }
  .Earners_t{
    display: flex;
    flex-direction: row;
  }
  @media screen and (max-width: 700px) {
    .Earners_t{
      flex-direction: column;
    align-items: center;
    gap: 3rem;
    width:100%;
    }
    .Earners_Intro {
      margin-top: 5rem;
    }

    .Earners_Intro p {
      margin: 5rem;
      font-size: 30px;
    }

    .Earners_Intro h1 {
      margin: 5rem;
      font-size: 50px;
    }
  }
   </style>