<template>
    <div>
        <div class="second-page bg-green-600 text-white h-screen">
        <nuxt-link to="/" class="button flex h-1/6 justify-end">
            <div class="text-white py-4 text-2xl tracking-widest font-semibold  bg-gray-500 w-full sm:w-2/6 md:w-1/5 flex justify-center items-center">
            01. Explore
            </div>
        </nuxt-link>
        <div class="content flex flex-col sm:flex-row md:flex-row w-full items-center h-5/6">
            <div class="date md:flex items-center py-2">
                <div class="text flex flex-row sm:flex-col md:flex-col px-4 text-center text-xl tracking-widest">
                    <p>02</p>
                    <p>/</p>
                    <p>02</p>
                </div>
            </div>
            <div class="content flex flex-col md:flex-row sm:flex-row justify-center w-full h-5/6 p-4 md:p-0 sm:p-0">
                <div class="spot1 flex items-end justify-center bg-blue-500 h-full md:w-48 sm:w-48 md:mx-6 sm:mx-6 my-2">
                    <p class="py-2">
                    Manduk Patinna
                    </p>
                </div>
                <div class="spot2 flex items-end justify-center bg-red-500 h-full md:w-48 sm:w-48 md:mx-6 sm:mx-6 my-2">
                    <p class="py-2">
                    Lo'ko Wai Lambun
                    </p>
                </div>
                <div class="spot3 flex items-end justify-center bg-green-500 h-full md:w-48 sm:w-48 md:mx-6 sm:mx-6 my-2">
                    <p class="py-2">
                    Sarambu Alla
                    </p>
                </div>
                <div class="spot4 flex items-end justify-center bg-indigo-500 h-full md:w-48 sm:w-48 md:mx-6 sm:mx-6 my-2">
                    <p class="py-2">
                    Camping Ground
                    </p>
                </div>
            </div>
        </div>
        </div>
    </div>
</template>
<script>
    export default {
        transition: 'slide-bottom'
    }
</script>

<style>
    .spot1{
        background-image: url('../assets/img/photo6109492160408694020.jpg');
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
    }

    .spot2{
        background-image: url('../assets/img/photo6109492160408693926.jpg');
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
    }

    .spot3{
        background-image: url('../assets/img/YOG01001.JPG');
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
    }

    .spot4{
        background-image: url('../assets/img/photo6109492160408693932.jpg');
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
    }
</style>