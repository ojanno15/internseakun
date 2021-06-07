<template>
  <div>
      <div class="section-two">
      <div class="left-content">
        <img src="~/assets/images/smile.svg" alt="#" class="left-images">
        <p class="left-title-one">Start with step one</p>
        <p class="left-title-two">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>

      <div class="right-content">
        <img src="~/assets/images/pie-chart.svg" alt="#" class="right-images">
        <p class="right-title-one">Keep easy to scan</p>
        <p class="right-title-two">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.section-two {
    width: 100%;
    height: auto;
    float: left;
    margin-top: 40px;
    margin-bottom: 40px;
}
.left-content {
    width: 700px;
    float: left;
}
.left-images {
    width: 300px;
    height: 150px;
    margin-left: 230px;
}
.left-title-one {
    font-size: 20px;
    margin-left: 305px;
    margin-top: 30px;
    padding: 10px;
}
.left-title-two {
    margin-left: 205px;
}
.right-content {
    width: 600px;
    float: right;
    margin-left: 30px;
}
.right-images {
    width: 300px;
    height: 150px;
    margin-left: 60px;
}
.right-title-one {
    font-size: 20px;
    margin-left: 140px;
    margin-top: 30px;
    padding: 10px;
}
.right-title-two {
    margin-left: 30px;
}
@media (max-width: 480px) {
    .section-two {
        position: relative;
        display: inline-block;
    }
    .left-content {
        width: 100%;
        padding-bottom: 50px;
        text-align: center;
    }
    .left-images {
        margin: auto;
    }
    .left-title-one {
        width: 70%;
        margin: auto;
    }
    .left-title-two {
        width: 90%;
        margin: auto;
        padding: 10px;  
    }
    .right-content {
        width: 100%;
        text-align: center;
    }
    .right-images {
        margin: auto;
    }
    .right-title-one {
        width: 90%;
        text-align: center;
        margin: auto;
    }
    .right-title-two {
        width: 90%;
        margin: auto;
        padding: 10px;
    }
}
</style>