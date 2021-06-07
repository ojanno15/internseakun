<template>
    <div>
        <div class="section-four">
            <div class="content-four">
                <p class="text-section-four">Big company announcement or simple sub-header taking two or more lines.
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
.content-four {
    width: 100%;
    float: left;
    background-color: #f0f8ff;
}
p.text-section-four {
    width: 70%;
    margin: auto;
    padding: 50px;
    text-align: justify;
    font-size: medium;
    word-spacing: 10px;
}
@media (max-width: 480px) {
    .content-four {
        width: 100%;
        text-align: center;
    }
    p.text-section-four {
        width: 100%;
        text-align: justify;
        padding: 50px;
        margin: auto; 
    }
}
</style>