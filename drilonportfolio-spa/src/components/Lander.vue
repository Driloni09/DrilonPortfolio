<template>
    <div>
        <section class="section">
            <div class="container-fliud">
                <img alt="Profile photo" class="rounded-circle" src="https://i.ibb.co/gZ4WPY4/photo.jpg" width="200" height="220">
                <h2>Drilon Rexhepi</h2>
                <h1>Software Developer</h1>
                <p>Ky eshte nje projekt ne te cilin une paraqes portfolion time duke mesuar dotnet core dhe vue.js
                </p>
                <button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target=".bd-example-modal-lg">Contact</button>
                 
            </div>
        </section>
        <!-- modal for contact -->
        <section class="">
            <div class="modal fade bd-example-modal-lg" tabindex="-1" 
                role="dialog" aria-labelledby="myLargeModalLabel" aria-hidden="true">
                    <div class="modal-dialog modal-lg">
                            <div class="modal-content">
                                <contact/>
                            </div>
                    </div>
                </div>
        </section>
    </div>
</template>


<style lang="css" scoped>
    .section{
        padding-top: 10%;
        padding-bottom: 10%;
        background-color: bisque;
    }
</style>



<script lang="ts">
import Contact from './Includes/Contact.vue'
export default {
    name:'Lander',
    components:{
        Contact
    }  
}
</script>