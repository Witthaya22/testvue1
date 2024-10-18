<script setup>

</script>

<template>
    <div class="flex flex-col justify-between h-screen ">
        <div class="dropdown ml-8">
            <div tabindex="0" role="button" class="font-bold text-4xl">...</div>
            <ul tabindex="0" class="dropdown-content menu bg-white rounded-box z-[1] w-52 p-2 shadow">
                <li><a>Item 1</a></li>
                <li><a>Item 2</a></li>
            </ul>
        </div>
        <i class="fa-solid fa-xmark absolute right-10 top-7 transform -translate-y-1/2  text-3xl"></i>

        <div class="flex flex-col justify-end h-screen my-6 container">
            <div class="text-center my-4 text-emerald-800 text-6xl"><i class="fa-solid fa-lock"></i></div>
            <div class="text-center  text-emerald-800 text-4xl font-extrabold">Forgot</div>
            <div class="text-center  text-emerald-800 text-4xl">Password?</div>
            <div class="text-center  text-emerald-800 ">No worries,we'll send you</div>
            <div class="text-center  text-emerald-800 ">reset instructions</div>
        </div>

        <div class="w-full bg-white rounded-t-badge py-10  color-custom">
            <div class="w-4/5 mx-auto text-gray-200 mb-2 text-xs">Email</div>
            <div class="relative w-4/5 mx-auto mb-6">
                <input
                class="btn btn-ghost border-solid border-2 border-white w-full rounded-full text-white text-start pl-12"
                type="password" placeholder="Enter your Email">
                <i class="fa-regular fa-envelope absolute left-4 top-1/2 transform -translate-y-1/2 text-white"></i>
            </div>
            <button class="btn w-4/5 mx-auto block rounded-full color-custom2 text-gray-500 mb-10">Reset Password</button>
            <div class="w-4/5 mx-auto text-center text-gray-200 text-xl link mb-8">Back to Login</div>
            <div class="w-4/5 mx-auto text-center text-gray-200 text-xl"><i class="fa-solid fa-right-from-bracket"></i></div>
            
        </div>
    </div>
</template>

<style scoped>
body, html {
    overflow: hidden; 

}
.color-custom {
    background: linear-gradient(to right, #498176, #2d6258);
}

.color-custom2 {
    background-color: #bed2d0;
    border: 2px solid #a7c4c0;
}

</style>