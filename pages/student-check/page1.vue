<script setup>

</script>

<template>
    <div class="flex flex-col justify-between h-screen color-custom ">
        <div class="dropdown ml-8">
            <div tabindex="0" role="button" class="text-white font-bold text-4xl">...</div>
            <ul tabindex="0" class="dropdown-content menu bg-white rounded-box z-[1] w-52 p-2 shadow">
                <li><a>Item 1</a></li>
                <li><a>Item 2</a></li>
            </ul>
        </div>

        <div class="mb-2 flex flex-col justify-start text-center ">
            <div class="w-5/6 mx-auto">
                <img src="../../assets/images/แนะแนวศึกษาต่อ-1448x2048-removebg-preview.png" class="mx-auto lg:w-1/6 w-2/4 ">
            </div>
                <div class="text-yellow-500 font-extrabold text-6xl">Student</div>
                <div class="text-white font-extrabold text-lg">CHECK APP</div>
        </div>

        <div class="flex flex-col space-y-4 mx-auto mb-4 container">
            <div class="relative w-4/5 mx-auto">
                <input
                    class="btn btn-ghost border-solid border-2 border-white w-full rounded-full text-white text-start pl-12"
                    type="text" placeholder="Email or Phone">
                <i class="fas fa-user absolute left-4 top-1/2 transform -translate-y-1/2 text-white"></i>
            </div>
            <div class="relative w-4/5 mx-auto">
                <input
                    class="btn btn-ghost border-solid border-2 border-white w-full rounded-full text-white text-start pl-12"
                    type="password" placeholder="Password">
                <i class="fas fa-lock absolute left-4 top-1/2 transform -translate-y-1/2 text-white"></i>
            </div>
        </div>

        <div class="w-full bg-white rounded-t-badge pb-7">
            <div class="text-center my-4 text-gray-500"><a href="/student-check/page3">Forgot Password?</a></div>
            <button class="btn w-4/5 mx-auto block rounded-full color-custom text-white">Login</button>
            <div class="text-center my-1 text-gray-400">or</div>
            <a href="/student-check/page2"><button class="btn w-4/5 mx-auto block rounded-full color-custom2 text-gray-500">Create an account</button></a>
        </div>
    </div>
</template>

<style scoped>
/* html, body {
    overflow: hidden;
} */
.color-custom {
    background: linear-gradient(to right, #498176, #2d6258);
}

.color-custom2 {
    background-color: #bed2d0;
    border: 2px solid #a7c4c0;
}

</style>