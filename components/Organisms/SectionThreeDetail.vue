<template>
    <div>
        <div class="section-three">
            <div class="content-three">
                <p class="text-section-three">Big company announcement or simple sub-header taking two or more lines.
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
.content-three {
    width: 100%;
    float: left;
}
p.text-section-three {
    width: 70%;
    margin: auto;
    padding: 50px;
    text-align: justify;
    font-size: medium;
    word-spacing: 10px;
}
@media (max-width: 480px) {
    .content-three {
        width: 100%;
        text-align: center;
    }
    p.text-section-three {
        width: 100%;
        text-align: justify;
        padding: 50px;
        margin: auto; 
    }
}
</style>