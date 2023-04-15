<template>
    <header class="header1">
       <div class="logo1">
          <img src="./assets/Group.png" alt="Logo"/>
       </div>
       <div class="butt">
           <button  id="button1">Login</button>
            
            <div class="reg_button"> <button  id="button2">Register</button>
            </div>

          
       </div>

    </header>
</template>

<script >
export default {
     name: "AppHeader",
};
</script>
  
<style scoped>
 .header1 {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem;
  color: #fff;
}

.logo1 img {
  height: 50px;
}
.butt {
  display: flex;
  gap: 1rem;
 
}
.butt button {
  background-color: transparent;
  font: normal normal bold 20px/27px Noto Sans;
  border: none;
  padding: 0.5rem 1rem;
  margin-left: 1rem;
  cursor: pointer;
  transition: all 0.2s ease-in-out;
}
#button1{
    color: #1F2532;
    opacity: 1;
}
.reg_button{
    background: #01CB63 0% 0% no-repeat padding-box;
box-shadow: 0px 5px 15px #01CB6359;
border-radius: 10px;
opacity: 1;
padding-left: 0.3rem;
margin: 4px;
}
#button2{
    font: normal normal normal 20px/27px Noto Sans;
    color: #FFFFFF;
   opacity: 1;
   margin:2px;
}


@media screen and (max-width: 1224px) {
    .header1 {
      flex-direction: column;
      justify-content: center;
      align-items: center;
      width:1224;
    }

    .logo1 {
      margin-bottom: 1rem;
    }

    .butt {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      margin-top: 1rem;
    }

    .butt button {
      margin-left: 0;
    }

    #button1 {
      margin-bottom: 0.5rem;
    }
  }

  /* For medium to large screens */
  
</style>







