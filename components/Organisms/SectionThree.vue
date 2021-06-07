<template>
    <div>
        <div class="section-three">
            <div class="section-three-images">
                <img src="~/assets/images/logo_berita_2.png" alt="#" class="images-three">
            </div>
            
            <div class="section-three-intro">
                <p class="section-three-content">Big company announcement</p>
                <p class="section-three-smalltext">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                <button class="section-three-button"><a href="Link2.html" class="button-three">Link 2</a></button>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.section-three {
    width: 100%;
    height: 600px;
    background-color: #f0f8ff;
    float: left;
}
.section-three-images {
    width: max;
    float: left;
    margin-top: 80px;
}
.images-three {
    width: 400px;
    height: 400px;
    margin-left: 180px;
}
.section-three-intro {
    width: max;
    margin: 170px 0 0 140px;
    float: left;
}
.section-three-content {
    width: 300px;
    font-size: 2rem;
    font-weight: 900;
    margin: 30px 30px 0 30px;
}
.section-three-smalltext {
    width: 500px;
    margin: 30px 30px 0px 30px;
}
.section-three-button {
    width: 80px;
    height: 30px;
    border-radius: 5px!important;
    background-color: black;
    margin: 30px;
}
.button-three {
    color: white;
    text-decoration: none!important;
}
@media (max-width: 480px) {
    .section-three {
        position: relative;
        height: max-content;
    }
    .section-three-intro {
        width: 100%;
        text-align: center;
    }
    .section-three-content {
        width: 100%;
        margin: 0;
        text-align: center;
    }
    .section-three-smalltext {
        width: 90%;
        margin: auto;
        padding: 10px;
        text-align: center;
    }
    .images-three {
        width: 100%;
        margin: 0;
    }
    .section-three-intro {
        width: 100%;
        margin: 0;
    }
    .section-three-button {
        text-align: center;
    }
}
</style>