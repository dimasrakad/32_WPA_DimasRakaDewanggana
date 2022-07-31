<template>
    <div class="row">
        <div class="col-lg-12 text-center services-title">
            <h1 class="text-uppercase title-text">Recently Done Projects</h1>
        </div>
    </div>
    <div class="container element-container">
        <div class="row grid">
            <div class="col-lg-4 col-6 element-item" v-for="(project, index) in projects" :key="index">
                <div class="card text-center mb-4">
                    <img src="../../assets/logo.png" v-bind:alt="project.name" class="img-fluid">
                    <div class="card-body">
                        <h4 class="text-uppercase">{{ project.name }}</h4>
                        <span class="text-secondary">{{ project.category }}, {{ project.time }}</span>
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
            projects: [
                {
                    name: "Project 1",
                    category: "Web Development",
                    time: "Latest"
                },
                {
                    name: "Project 2",
                    category: "Mobile Development",
                    time: "Latest"
                },
                {
                    name: "Project 3",
                    category: "Web Development",
                    time: "Latest"
                },
                {
                    name: "Project 4",
                    category: "Web Development",
                    time: "Upcoming"
                },
                {
                    name: "Project 5",
                    category: "Mobile Development",
                    time: "Upcoming"
                },
                {
                    name: "Project 6",
                    category: "Web Development",
                    time: "Upcoming"
                },
            ]
        }
    }
}
</script>