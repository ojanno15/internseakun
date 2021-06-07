<template>
    <div>
        <div class="section-four">
            <div class="card-one">
                <img src="~/assets/images/profile.png" alt="Avatar" style="width:100%" class="container-image-one">
                <div class="container-card-one">
                <p class="text-one">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>

            <div class="card-two">
                <img src="~/assets/images/profile.png" alt="Avatar" style="width:100%" class="container-image-two">
                <div class="container-card-two">
                <p class="text-two">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>

            <div class="card-three">
                <img src="~/assets/images/profile.png" alt="Avatar" style="width:100%" class="container-image-three">
                <div class="container-card-three">
                    <p class="text-three">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.section-four {
    width: 100%;
    height: 400px;
    float: left;
    display: flex;
    justify-content: center;
    margin-top: 10px;
    background-color: white;
    padding: 40px;
}
.card-one{
    width: 260px;
    height: 300px;
    box-shadow: 4px 4px 8px 4px rgba(0,0,0,0.2);
    transition: 0.3s;
    border-radius: 10px;
    background-color: white;
}
.text-one {
    font-size: small;
}
.card-two {
    background-color: white;
}
.card-three {
    background-color: white;
}
.card-one:hover {
    box-shadow: 8px 10px 10px 8px rgba(0,0,0,0.2);
}
.container-card-one {
    padding: 2px 16px;
}
.container-image-one {
    width: 260px!important;
    height: 200px;
    padding: 20px;
    float: left;
}
.card-two{
    width: 260px;
    height: 300px;
    box-shadow: 4px 4px 8px 4px rgba(0,0,0,0.2);
    transition: 0.3s;
    margin-left: 80px;
    border-radius: 10px;
}
  .card-two:hover {
    box-shadow: 8px 10px 10px 8px rgba(0,0,0,0.2);
}
.container-card-two {
    padding: 2px 16px;
}
.container-image-two {
    width: 260px!important;
    height: 200px;
    padding: 20px;
    float: left;
}
.text-two {
    font-size: small;
}
.card-three{
    width: 260px;
    height: 300px;
    box-shadow: 4px 4px 8px 4px rgba(0,0,0,0.2);
    transition: 0.3s;
    margin-left: 80px;
    border-radius: 10px;
}
.card-three:hover {
    box-shadow: 8px 10px 10px 8px rgba(0,0,0,0.2);
}
.container-card-three {
    padding: 2px 16px;
}
.container-image-three {
    width: 260px!important;
    height: 200px;
    padding: 20px;
    float: left;
}
.text-three {
    font-size: small;
}
@media (max-width: 480px) {
    .section-four {
        width: 100%;
        display: inline-block;
        height: auto;
        position: relative;
        text-align: center;
        margin-bottom: 100px;
    }
    .card-one {
        margin: auto;
    }
    .card-two {
        margin: auto;
    }
    .card-three {
        margin: auto;
    }
}
</style>