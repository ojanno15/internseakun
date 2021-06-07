<template>
    <div>
        <div class="section-two">
            <div class="content-two">
                <img src="~/assets/images/logo_berita_2.png" alt="" class="image-two">
                <p class="text-section-two">Big company announcement or simple sub-header taking two or more lines.
                    Big company announcement or simple sub-header taking two or more lines.
                    Big company announcement or simple sub-header taking two or more lines.
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
.content-two {
    width: 100%;
    display: flex;
    justify-content: space-between;
}
.image-two {
    width: 350px;
    height: 300px;
    margin-left: 200px;
    float: left;
}
.text-section-two {
    float: right;
    width: 350px;
    text-align: justify;
    word-spacing: 12px;
    margin-right: 200px;
    font-size: medium;
    padding-top: 10px;
    padding-bottom: 80px;
}
@media (max-width: 480px) {
    .content-two {
        width: 100%;
        text-align: center;
        display: inline-block
    }
    .image-two {
        width: 100%;
        height: 500px;
        margin: auto;
    }
    .text-section-two {
        width: 100%;
        text-align: justify;
        margin: auto;
        padding: 50px;
    }
}
</style>