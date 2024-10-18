<script setup>

</script>

<template>
    <div class="flex flex-col justify-between h-screen color-custom">
        <div class="dropdown ml-8">
            <div tabindex="0" role="button" class="text-white font-bold text-4xl">...</div>
            <ul tabindex="0" class="dropdown-content menu bg-white rounded-box z-[1] w-52 p-2 shadow">
                <li><a>Item 1</a></li>
                <li><a>Item 2</a></li>
            </ul>
        </div>

        <div class="flex flex-col justify-end h-screen space-y-4 my-6 container">
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

        <div class="w-full bg-white rounded-t-badge pb-9">
            <div class="text-center my-4 text-gray-400">Forgot Password?</div>
            <button class="btn w-4/5 mx-auto block rounded-full color-custom text-white">Login</button>
            <div class="text-center my-1 text-gray-400">or</div>
            <button class="btn w-4/5 mx-auto block rounded-full color-custom2 text-gray-500">Create an account</button>
        </div>
    </div>
</template>

<style scoped>
.color-custom {
    background: linear-gradient(to right, #498176, #2d6258);
}

.color-custom2 {
    background-color: #bed2d0;
    border: 2px solid #a7c4c0;
}

</style>