<template>
    <div class="container services">
        <div class="row">
            <div class="col-lg-12 text-center services-title">
                <h1 class="text-uppercase title-text">Services Offers</h1>
            </div>
        </div>
        <div class="container services-list">
            <div class="row">
                <div class="col-lg-3 col-6" v-for="(service, index) in services" :key="index">
                    <div class="card mb-4">
                        <img src="../../assets/logo.png" v-bind:alt="service">
                        <div class="card-body text-center">
                            <h5 class="card-title text-uppercase font-roboto">{{ service }}</h5>
                            <p class="card-text text-secondary">
                                Lorem ipsum dolor sit amet, consectetur
                                adipisicing elit, sed do eiusmod
                                tempor incididunt ut labore et
                                dolore magna aliqua.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            services: ['web development', 'mobile developmennt', 'ui/ux design', 'it consulting', 'team augmentation', 'application security', 'operational system', 'data migration']
        }
    }
}
</script>

<style>
.services {
    margin-bottom: 40px;
}
</style>