<template>
    <article id="recent-projects" class="white-section">
        <section class="container">
            <h3>Recent Projects</h3>
            <div class="row no-gutters">
                <div class="col-lg-6" v-for="(project, index) in recentProjects" :key="index">
                    <a href="" class="portfolio-item">
                        <span class="caption">
                            <span class="caption-content">
                                <h2>{{ project.title }}</h2>
                                <p class="mb-0">{{ project.description }}</p>
                            </span>
                        </span>
                        <img class="img-fluid" src="https://cdn.dribbble.com/users/22460/screenshots/4248814/programming-school.png?compress=1&resize=400x300">
                    </a>
                </div>
            </div>
        </section>

    </article>
</template>

<script>
export default {
    data: () => {
        return{
            recentProjects: [
                {
                    img: 'todo.png',
                    title: 'Jot',
                    description: 'Nje aplikacione qe perdoret per te ruajtur kontaktet'
                },
                {
                    img: 'todo.png',
                    title: 'Job Hunt',
                    description: 'Nje aplikacion i cili perdoret per postimin e aplikimeve te vendeve te punes'
                },
                {
                    img: 'todo.png',
                    title: 'Task Manager',
                    description: 'Nje aplikacion i cili perdoret per ruajtjen e taskave'
                },
                {
                    img: 'todo.png',
                    title: 'FoodRecipes',
                    description: 'Nje aplikacion per ruajtjen e recetave te ushqimit'
                },
            ]
        }
    },
}
</script>

<style scoped>
.row{
    padding-top: 50px;
}
.portfoli-item{
    display: block;
    position: relative;
    overflow: hidden;
}
.caption{
    display: flex;
    height: 100%;
    width: 100%;
    position: absolute;
    top: 0;
    bottom: 0;
    z-index: 1;
    
}
.caption-content{
    text-align: left;
    color: #fff;
    margin: auto 2rem 2rem;
}
img{
    width: 700px;
    transition: transform .2s linear;
    padding-right: 1px;
}
h3{
    margin-top: 3rem;
    font-weight: bold;
    font-size: 3rem;
}
.container{
    padding: 2rem;
}
</style>