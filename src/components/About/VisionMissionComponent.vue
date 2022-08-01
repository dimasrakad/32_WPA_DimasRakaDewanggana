<template>
    <div class="vision-mission-area container-fluid mb-4">
        <div class="vision mb-4">
            <h1 class="text-uppercase vision-mission-title">
                <span>Vision</span>
            </h1>
            <div class="vision-mission-content">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Distinctio magni amet sunt illum.
                Dolor dolores illum autem velit iste aperiam assumenda corporis voluptatibus. Quia dolore natus
                esse ut? Suscipit, nulla.
            </div>
        </div>
        <div class="mission mb-4">
            <h1 class="text-uppercase vision-mission-title">
                <span>Mission</span>
            </h1>
            <div class="vision-mission-content row" v-for="index in 10" :key="index">
                <div class="col-1">{{ index }}.</div>
                <div class="col-11">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Distinctio magni amet sunt illum.
                    Dolor dolores illum autem velit iste aperiam assumenda corporis voluptatibus. Quia dolore natus
                    esse ut? Suscipit, nulla.
                </div>
            </div>
        </div>
    </div>
</template>

<style>
.vision-mission-area {
    padding: 20px 40px 0 40px;
}

.vision-mission-title {
    text-align: center;
}

.vision-mission-content {
    text-align: justify;
}
</style>