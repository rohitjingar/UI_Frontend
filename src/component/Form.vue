<template>
     <div class="center">
  
  <form @submit.prevent="submitForm">
    <div class="inputbox">
      <input type="text" minlength="3" maxlength="20"  required>
      <span>Name</span>
     
    </div>
    <div class="inputbox">
      <input type="text" pattern="[a-zA-Z0-9_.+-]+@gmail.com"  required="required">
      <span>Email</span>
    </div>
    <div class="inputbox">
      <input type="text" pattern="[789][0-9]{9}" required="required">
      <span>Phone</span>
    </div>
    <div class="inputbox">
      <input type="text" required="required">
      <span>Subject</span>
    </div>
    
    <div class="inputbox">
      <input type="submit"  value="Submit">
    </div>
  </form>
</div>
</template>

<script >
export default {
     name: "AppForm",
};
</script>

<style scoped>
 .error {
  color: red;
}
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background: linear-gradient(45deg, greenyellow, dodgerblue);
  font-family: "Sansita Swashed", cursive;
}
.center {
    display: flex;
    flex-direction: column;
align-items: center;
  
}
.center h1 {
  font-size: 2em;
  border-left: 5px solid dodgerblue;
  padding: 10px;
  color: #000;
  letter-spacing: 5px;
  margin-bottom: 60px;
  font-weight: bold;
  padding-left: 10px;
}
.center .inputbox {
  position: relative;
  width: 300px;
  height: 50px;
  margin-bottom: 50px;
}
.center .inputbox input {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  border: 2px solid #000;
  outline: none;
  background: none;
  padding: 10px;
  margin-left:8rem;
  border-radius: 10px;
  font-size: 1.2em;
}
.center .inputbox:last-child {
  margin-bottom: 0;
}
.center .inputbox span {
  position: absolute;
  top: 14px;
  padding-left:3rem;
  font-size: 1em;
  transition: 0.6s;
  
/* UI Properties */

font: italic normal normal 20px/21px Noto Sans;

color: #86919D;
opacity: 1;
}


.center .inputbox [type="submit"] {
  width: 50%;
  background: rgb(51, 205, 102);
  
font: italic normal normal  Noto Sans;
letter-spacing: 0.5px;
color: #FFFFFF;
opacity: 1;
  border: #fff;
}
.center .inputbox:hover [type="submit"] {
  background: linear-gradient(45deg, rgb(15, 15, 15), rgb(11, 12, 12));
}
@media screen and (max-width: 768px) {
  .center{
    margin-top: 2rem;
    padding-top: 1rem;
    margin-left:-1rem;
    width: 100%;
  }
}
</style>