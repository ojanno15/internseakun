<template>
    <div>
        <div class="card">
            <div>
                <button class="button-popup" id="lates" @click="popUp">x</button>
                <p class="popup">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur soluta excepturi autem! Id totam consectetur sint, corrupti vero libero deserunt tempora expedita reiciendis facilis quia ut nesciunt, atque quo dolore.
                </p>
                    <div>
                        <input type="text" class="input">
                        <button>Submit</button>
                    </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    mounted() {
        this.showPopUp()
    },
    methods: {
        popUp() {
            $(".card").fadeOut("slow")
        },
        showPopUp() {
            setInterval ( function() {
                $(".card").fadeIn("slow")
            }, 6000)
        }
    }
}
</script>

<style>

</style>