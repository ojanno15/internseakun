<template>
  <div>
      <div class="intro">
        <p class="intro-content">Showcase your thought provoking topics and ideas</p>
        <p class="intro-small-text">Big company announcement or simple sub-header taking two or more lines.</p>
        <Button :name="name" class="intro-button" @anotherPage="toAnotherPage"/>
      </div>

      <div class="intro-images">
        <img src="~/assets/images/logo_berita_2.png" alt="#" class="intro-images-one">
      </div>
  </div>
</template>

<script>
import Button from "~/components/Atoms/Button.vue"
export default {
    components: {
        Button: Button,
    },
    data() {
        return {
            name: 'Link 2',
        }
    },
    methods: {
        toAnotherPage() {
            this.$router.push('/detail');
        }
    }
}
</script>

<style>
* {
    margin: 0;
    padding: 0;
}
.intro {
    width: 700px;
    height: 400px;
    float: left;
}
.intro-content {
    width: 300px;
    font-size: 2rem;
    text-align: start;
    margin: 130px 30px 10px 150px;
}
.intro-small-text {
    width: 260px;
    margin: 0 30px 10px 150px;
}
.intro-images {
    background-color: #f0f8ff;
}
.intro-images-one {
    margin-left: 20px;
    width: 500px;
}
@media (max-width: 480px) {
    .intro {
        width: 100%;
        height: auto;
        position: relative;
        text-align: center;
    }
    .intro-content {
        width: 100%;   
        padding-top: 50px;
        text-align: center;
        margin: 0;
    }
    .intro-small-text {
        width: 100%;
        margin: 0;
    }
    .intro-button {
        text-align: center;
        margin: 0;
    }
    .intro-images-one {
        width: 100%;
        margin: auto;
        text-align: center;
    }
}
</style>