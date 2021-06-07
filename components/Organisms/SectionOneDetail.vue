<template>
    <div>
        <div class="section-one-detail">
                <div class="content-one">
                    <img src="~/assets/images/logo_berita_2.png" alt="" class="image-one">
                    <h2 class="title-content-one">Showcase your thought provoking topics and ideas</h2>
                    <p class="text-content-one">Big company announcement or simple sub-header taking two or more lines.
                        Big company announcement or simple sub-header taking two or more lines.
                        Big company announcement or simple sub-header taking two or more lines.
                        Big company announcement or simple sub-header taking two or more lines.
                        Big company announcement or simple sub-header taking two or more lines.
                        Big company announcement or simple sub-header taking two or more lines.
                    </p>
                    <p class="text-content-two">
                        Big company announcement or simple sub-header taking two or more lines.
                        Big company announcement or simple sub-header taking two or more lines.
                        Big company announcement or simple sub-header taking two or more lines.
                    </p>
                </div>
            </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.content-one {
    width: 100%;
    text-align: center;
    background-color: #f0f8ff;
}       
.image-one {
    width: 600px;
    height: 500px;
}
.title-content-one {
    width: 100%;
    text-align: center;
    padding: 20px;
    word-spacing: 1rem;
    font-size: large;
    padding-bottom: 30px;
}
.text-content-one {
    width: 80%;
    text-align: justify;
    margin: auto;
    font-size: medium;
    word-spacing: 10px;
    padding: 25px;
}
.text-content-two {
    width: 80%;
    text-align: justify;
    margin: auto;
    font-size: medium;
    word-spacing: 10px;
    padding: 25px;
}
@media (max-width: 480px) {
    .content-one {
        width: 100%;
        text-align: center;
    }
    .image-one {
        width: 100%;
        height: 450px;
    }
    .text-content-one {
        width: 100%;
        text-align: justify;
        padding: 50px;
        margin: auto;        
    }
    .text-content-two {
        width: 100%;
        text-align: justify;
        padding: 50px;
        margin: auto;        
    }
}
</style>