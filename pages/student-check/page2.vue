<script setup>

</script>

<template>
    <div class="flex flex-col justify-between h-screen ">

        <div class="w-full bg-white rounded-b-badge pb-9 color-custom">
            <div class="dropdown ml-8">
            <div tabindex="0" role="button" class="text-white font-bold text-4xl">...</div>
            <ul tabindex="0" class="dropdown-content menu bg-white rounded-box z-[1] w-52 p-2 shadow">
                <li><a>Item 1</a></li>
                <li><a>Item 2</a></li>
            </ul>
        </div>
        <i class="fa-solid fa-xmark absolute right-10 top-7 transform -translate-y-1/2 text-white text-3xl"></i>
        <div class="w-5/6 mx-auto mt-2">
            <div class="text-start text-white text-4xl">Let's</div>
            <div class="text-start text-white text-4xl font-extrabold">Create</div>
            <div class="text-start text-white text-4xl font-extrabold">Yoour</div>
            <div class="text-start text-white text-4xl font-extrabold">Account</div>
        </div>
        </div>

        

        <div class="flex flex-col justify-center h-screen space-y-4 my-6 container">
            <div class="relative w-4/5 mx-auto">
                <input
                    class="btn btn-ghost border-solid border-2 border-emerald-950 w-full rounded-full text-emerald-950 text-start pl-12"
                    type="text" placeholder="Full Name">
                <i class="fas fa-user absolute left-4 top-1/2 transform -translate-y-1/2 text-emerald-950"></i>
            </div>
            <div class="relative w-4/5 mx-auto">
                <input
                    class="btn btn-ghost border-solid border-2 border-emerald-950 w-full rounded-full text-emerald-950 text-start pl-12"
                    type="text" placeholder="Email Address">
                <i class="fa-regular fa-envelope absolute left-4 top-1/2 transform -translate-y-1/2 text-emerald-950"></i>
            </div>
            <div class="relative w-4/5 mx-auto">
                <input
                    class="btn btn-ghost border-solid border-2 border-emerald-950 w-full rounded-full text-emerald-950 text-start pl-12"
                    type="text" placeholder="Password">
                <i class="fas fa-lock absolute left-4 top-1/2 transform -translate-y-1/2 text-emerald-950"></i>
            </div>
            <div class="relative w-4/5 mx-auto">
                <input
                    class="btn btn-ghost border-solid border-2 border-emerald-950 w-full rounded-full text-emerald-950 text-start pl-12"
                    type="password" placeholder="Retype Password">
                <i class="fas fa-lock absolute left-4 top-1/2 transform -translate-y-1/2 text-emerald-950"></i>
            </div>
            <div class="w-4/5 mx-auto text-gray-400 text-xs"><input type="checkbox" class="mr-2">I agree to the <span class="font-bold">Terms & Privacy</span></input></div>
            <button class="btn w-4/5 mx-auto block rounded-full color-custom text-white">Login</button>
            <div class="w-4/5 mx-auto text-xs"><div class="text-start  text-gray-400">Have an account? <span class="font-bold">Sign in</span></div></div>
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