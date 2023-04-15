<template>
   <div>
     <div class="Course_Intro">
        <p>
            Courses
        </p>
        <h1>
          Our Most Popular Courses
        </h1>

     </div>

    <div class="courses_t">
      <Product
       :image-url="require('./assets/imgc1.jpg')"
       title="Ultimate Business Intelligence Analyst A to Z Course 2021"
       title1="46,995"
       title2="Students"
       title3="11 hr 20 mins"
       title4="44 Lectures"
      />
      
      <Product
      :image-url="require('./assets/img2.jpg')"
       title="Adobe Photoshop Training: From Beginner to Pro"
       title1="6,995"
       title2="Students"
       title3="6 hr 20 mins"
       title4="24 Lectures"
      />
      <Product
      :image-url="require('./assets/img3.jpg')"
       title="Social Media Marketing - A to Z Content Marketing class 2021"
       title1="46,995"
       title2="Students"
       title3="11 hr 20 mins"
       title4="44 Lectures"
       />

    </div>
 </div>
    
    
  </template>
  
  <script>
  import Product from "./Product.vue"
  
  export default {
    name: "AppCourses",
    components: {
      Product
    }
  };
 
  </script>

<style scoped>
  .Course_Intro p{
    text-align: center;
font: normal normal normal 25px/34px Noto Sans;
letter-spacing: 0px;
color: #01CB63;
opacity: 1;
  }
  .Course_Intro h1{
    text-align: center;
font: normal normal bold 40px/54px Noto Sans;
letter-spacing: 0px;
color: #1F2532;
text-transform: capitalize;
opacity: 1;
  }
  .courses_t{
    display: flex;
    flex-direction: row;
    
  }
  @media only screen and (max-width: 800px) {
  .Course_Intro h1 {
    font-size: 32px;
  }

  .courses_t {
    flex-direction: column;
    align-items: center;
    gap: 3rem;
    width:100%;
  }
}

@media only screen and (max-width: 576px) {
  .Course_Intro h1 {
    font-size: 28px;
  }
}
</style>
  