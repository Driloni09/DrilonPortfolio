<template>
  <div>
      <article id="offers" class="blue-section">
        <section class="container">
            <h2>Pergatitja profesionale</h2>
            <div class="row">
                <div class="col-lg-3 col-md-6 mb-5 mb-lg-0" v-for="(offer, index) in offers" :key="index">
                    <div class="icon mx-auto"><i class="fas" :class="offer.icon"></i>
                        <h4>{{ offer.title }}</h4>
                        <span>{{ offer.description }}</span>
                    </div>
                </div>
            </div>
        </section>
      </article>
  </div>
</template>

<script>
export default {
    data: () => {
        return{
            offers: [
                {
                    icon: 'far fa-school',
                    title: 'Sami Frasheri',
                    description: 'Shkolla e mesme'
                },
                {
                    icon: 'fas fa-server',
                    title: 'Cisco Networking Academy',
                    description: 'Trajnim profesional'
                },
                {
                    icon: 'fas fa-university',
                    title: 'FIEK & UBT',
                    description: 'Studimet'
                },
                {
                    icon: 'fas fa-user-graduate',
                    title: 'UBT',
                    description: 'Diploma'
                },
            ]
        }
    },
}
</script>

<style long="scss" scoped>
@import url('https://use.fontawesome.com/releases/v5.8.1/css/all.css');

.blue-section{
    padding: 120px 10px;
    background-color: #1d809f;
    color: #fff;
    text-align: center;
}
 h2 {
        font-size: 3rem;
        font-weight: bold;
        margin-bottom: 50px;

    }
    h4{
        font-size: 1.6rem;
        padding-top: 20px;
    }

 
</style>