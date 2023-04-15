<template>
   <div>
        <div class="intro_cont">
            <p class="p1">
                Contact Us
            </p>
            <p class="p2">
                Reach Out with any question you have
            </p>
        </div>
        <div class="Cont">
           <div class="Cont_info">
               <p class="p3">Contact Information</p>
                <div class="Sym">
                    <div  class="lk" id="Sym1">
                       <img src="./assets/Groupo.svg" alt="logo4"/>
                       <p>contact@coursepro.com</p>
                    </div>
                    <div class="lk" id="Sym2">
                        <img src="./assets/Groups.svg" alt="logo4"/>
                       <p>1800-562-895, 1800-869-877</p>
                    </div>
                    <div class="lk" id="Sym3">
                        <img src="./assets/Groupt.svg" alt="logo4"/>
                       <p>102 Street, India</p>
                    </div>

                </div>
                <p class="p3">Social Media Channel</p>

                <div class="Social">
                  <img src="./assets/Facebook.svg" alt="logo5"/>
                  <img src="./assets/Twitter.svg" alt="logo5"/>
                  <img src="./assets/Github.svg" alt="logo5"/>
                  <img src="./assets/Linkedin.svg" alt="logo5"/>
                </div>
           </div>

           <div class="form_info">
              <p class="p4">Fill up the form and our team will get back to you within 24 hours</p>
              <Form/>
           </div>
        </div>


   </div>
</template>

<script >
import Form from "./Form.vue"
export default {
     name: "AppContact",
     components:{
        Form,
     },
};
</script>

<style scoped>
.intro_cont{
    display: flex;
    flex-direction: column;
align-items: center;
}
  .p1{
    text-align: center;
   
font: normal normal normal 25px/34px Noto Sans;
letter-spacing: 0px;
color: #01CB63;
opacity: 1;
  }
  .p2{
    
font: normal normal bold 40px/54px Noto Sans;
letter-spacing: 0px;
color: #1F2532;
text-transform: capitalize;
opacity: 1;
width: 410px;
height: 109px;
text-align: center;
margin-top:-0.8rem;
  }
  .Cont{
    display: flex;
    flex-direction: row;
    background: #F8F9FB 0% 0% no-repeat padding-box;
opacity: 1;

  }
  .Cont_info{
    margin-bottom: 4rem;
    display: flex;
    flex-direction: column;
align-items: center;
  }
  
  .p3{
    margin-top:4rem;
    margin-left: 7rem;
    font: normal normal bold 35px/34px Noto Sans;
letter-spacing: 0.7px;
color: #201F23;
opacity: 1;
  }
  .Sym{
    display: flex;
    flex-direction: column;
    margin-top:1.6rem;
    margin-left: 8rem;
  }
  .lk{
    display: flex;
    flex-direction: row;
  }
  .lk img{
    width: 72px;
height: 72px;
margin-top:0.5rem;
background: transparent  0% 0% no-repeat padding-box;
opacity: 1;
  }
  .lk p{
font: normal normal bold 25px/34px Noto Sans;
letter-spacing: 0px;
color: #201F23;
opacity: 0.8;
  }
  .Social{
    display: flex;
    flex-direction: row;
    align-content: space-evenly;
    padding-left: 5rem;
    margin-left: 1rem;
  }
  .Social img{
    width: 60px;
height: 60px;

padding-left: 4rem;
background: transparent  0% 0% no-repeat padding-box;
opacity: 1;
  }
  
  .p4{
    width: 570px;
height: 68px;
margin-top:4rem;
margin-left: 15rem;
text-align: center;
font: normal normal bold 25px/34px Noto Sans;
letter-spacing: 0px;
color: #201F23;
opacity: 1;
  }
  @media screen and (max-width: 820px) {
  .Cont {
    display: flex;
    flex-direction: column;
    width: 100%;
    
  }
  .p4{
    margin-left: 16rem;
   width: 55%;

text-align: left;
font: normal normal bold 25px/34px Noto Sans;
letter-spacing: 0px;
color: #201F23;
opacity: 1;
  }
  .p2{
    margin-left:7rem;
  }
}
</style>