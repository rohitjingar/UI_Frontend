<template>
    <div class="footer">
        <p>
            2021-2022 © Course Pro Private Limited
        </p>
        <div class="ui">
            <p>
            Term & Condition
        </p>
        <p>
            Privacy Policy
        </p>
        </div>
       
    </div>
</template>

<script >
export default {
     name: "AppFooter",
};
</script>

<style scoped>
.footer{
    background: #FFFFFF 0% 0% no-repeat padding-box;
opacity: 1;
width: 100%;
height: 70px;
display: flex;
flex-direction: row;
}
.footer p{
    padding-left:4rem;
    text-align: left;
font: normal normal bold 25px/34px Noto Sans;
letter-spacing: 0px;
color: #1F2532;
text-transform: capitalize;
opacity: 1;
}
.ui{
    display: flex;

    margin-left:27rem;
}
@media screen and (max-width: 768px) {
  .footer {
    flex-direction: column;
    height: auto;
    align-items: center;
    justify-content: center;
  }

  .ui {
    margin-top: 1rem;
    margin-left: 0;
  }

  .ui p {
    margin: 0 1rem;
  }
}

@media screen and (max-width: 480px) {
  .footer p {
    font-size: 20px;
  }

  .ui p {
    font-size: 16px;
  }
}
</style>