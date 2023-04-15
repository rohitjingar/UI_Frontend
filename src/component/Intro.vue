<template>
    <div class="intro">
    
          <div class="t_intro">
               
               <div class="t1_intro"> <p>Anytime, Anywhere Learn On Your 
                Schedule From Any Device</p>

               </div>
               <div class="t2_intro">
                <p>We Believe everyone has the capcity to be
                     creative Course Pro is a place where people develop their own potential</p>
               </div>
               <div class="t3_intro">
                  <button >Let's Get Start</button>
               </div>
          </div>
          <div class="cute_girl">
            <div class="img_d"><img src="./assets/cute_g.jpg" alt="girl"/></div>
          
          </div>
    </div>
</template>

<script >
export default {
     name: "AppIntro",
};
</script>

<style scoped>
  .intro {
    display: flex;
    flex-direction: row;
    width: 100%;
  }

  .t_intro {
    display: flex;
    flex-direction: column;
    padding-left: 1rem;
    padding-right: 2rem;
    width: 50%;
    background: #01cb63;
  }

  .t1_intro {
    padding-left: 4rem;
    padding-top: 2rem;
  }

  .t1_intro p {
    font: normal normal bold 55px/60px "Noto Sans", sans-serif;
    letter-spacing: 0px;
    color: #ffffff;
    text-transform: capitalize;
    opacity: 0.9;
    text-align: left;
  }

  .t2_intro {
    padding-left: 5rem;
    padding-right: 14rem;
  }

  .t2_intro p {
    padding-top: -0.1rem;
    font: italic bold 19px/35px "Noto Sans", sans-serif;
    letter-spacing: 0px;
    color: #ffffff;
    text-transform: capitalize;
    opacity: 0.9;
    color: rgba(31, 37, 50, 1);
  }

  .t3_intro {
    padding-left: 5rem;
  }

  .t3_intro button {
    padding-left: 1rem;
    padding-right: 1rem;
    background: rgba(0, 0, 0, 1) 0% 0% no-repeat padding-box;
    border-radius: 10px;
    opacity: 1;
    color: rgb(249, 243, 243);
    font: italic normal normal 20px/50px Noto Sans;
    cursor: pointer;
    transition: all 0.2s ease-in-out;
  }

  .cute_girl {
    width: 50%;
    margin-right: -1rem;
  }

  .img_d {
    width: 100%;
    height: 0;
    padding-bottom: 80%;
    position: relative;
  }

  .cute_girl img {
    position: absolute;
    padding-left: px;
    width: 100%;
    height: 100%;
    object-fit: cover;
    opacity: 0.5;
  }

  /* Media queries */

  @media only screen and (max-width: 1268px) {
    .intro {
      flex-direction: column;
    }

    .t_intro {
      width: 100%;
      padding-right: 0;
    }

    .t2_intro {
      padding-right: 0;
    }

    .cute_girl {
      width: 100%;
      margin-right: 0;
    }
  }

  @media only screen and (max-width: 480px) {
    .t1_intro p {
      font-size: 40px;
      line-height: 50px;
    }

    .t2_intro p {
      font-size: 16px;
      line-height: 30px;
      padding-right: 5rem;
    }

    .t3_intro button {
      font-size: 16px;
      line-height: 30px;
    }
  }
</style>
