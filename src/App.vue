<template>
  <div id="app">
     <Header/>
     <Intro/>
     <Family/>
     <Courses/>
     <TopEarners/>
     <Flow/>
     <Contact/>
     <Footer/>
  </div>
</template>

<script>
import Header from "./component/Header.vue";
import Intro from "./component/Intro.vue";
import Family from "./component/Family.vue";
import Courses from "./component/Courses.vue";
import TopEarners from "./component/TopEarners.vue";
import Flow from "./component/Flow.vue";
import Contact from "./component/Contact.vue";
import Footer from "./component/Footer.vue";
export default {
  name: "App",
  components:{
    Header,
    Intro,
    Family,
    Courses,
    TopEarners,
    Flow,
    Contact,
    Footer
  },
};
</script>
