<template>
    <div class="testimonials-area container-fluid">
        <div class="row">
            <div class="col-lg-12 text-center services-title">
                <h1 class="text-uppercase title-text">Clients Say About Us</h1>
            </div>
        </div>

        <div id="carouselExampleControls" class="carousel carousel-dark slide" data-bs-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <div class="container d-flex justify-content-center">
                        <div class="card mb-3">
                            <div class="row g-0">
                                <div class="col-md-4">
                                    <img src="../../assets/avatars/avatar1.png" class="img-fluid rounded-start"
                                        v-bind:alt="testimonials[0]">
                                </div>
                                <div class="col-md-8">
                                    <div class="card-body">
                                        <h5 class="card-title">{{ testimonials[0] }}</h5>
                                        <p class="card-text">This is a wider card with supporting text below as a
                                            natural lead-in to additional content. This content is a little bit
                                            longer.
                                        </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="carousel-item" v-for="(testimonial, index) in testimonials.slice(1, testimonials.length)" :key="index">
                    <div class="container d-flex justify-content-center">
                        <div class="card mb-3">
                            <div class="row g-0">
                                <div class="col-md-4">
                                    <img v-bind:src="require('../../assets/avatars/avatar' + (index + 2) + '.png')" class="img-fluid rounded-start"
                                        v-bind:alt="testimonial">
                                </div>
                                <div class="col-md-8">
                                    <div class="card-body">
                                        <h5 class="card-title">{{ testimonial }}</h5>
                                        <p class="card-text">This is a wider card with supporting text below as a
                                            natural lead-in to additional content. This content is a little bit
                                            longer.
                                        </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls"
                data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls"
                data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            testimonials: ['Aji', 'Brenda', 'Cantika', 'Doni', 'Elang']
        }
    }
}
</script>

<style>
.testimonials-area {
    padding: 20px 40px 0 40px;
}

.carousel-item {
    align-items: center;
}
</style>