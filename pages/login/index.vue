<script setup></script>

<template>
  <div class="backkk">
    <div class="flex min-h-screen justify-center items-center">
      <form class="w-full max-w-lg mx-auto rounded-lg p-8 space-y-6 backdrop-blur-xl">
        <div class="space-y-2">
          <img src="@/assets/images/forest (1).png" alt="logo" class="w-28 mx-auto">
          <h1 class="text-2xl text-center text-white font-bold">เข้าสู่ระบบ</h1>
        </div>
        <label class="block">
          <span class="block font-semibold text-white mb-2">ชื่อผู้ใช้งาน</span>
          <input class="input input-bordered w-full p-2 bg-white rounded-md" type="text"
            placeholder="กรอกชื่อผู้ใช้งาน" />
        </label>
        <label class="block">
          <span class="block font-semibold text-white mb-2">รหัสผ่าน</span>
          <input class="input input-bordered w-full p-2 bg-white rounded-md" type="password"
            placeholder="กรอกรหัสผ่าน" />
        </label>
        <button class="btn w-full py-2 mt-8 text-white bg-blue-500 font-semibold rounded-md hover:bg-blue-600">
          เข้าสู่ระบบ
        </button>
        <button class="link w-full py-2 mt-8 text-blue-500 font-semibold rounded-md">
          สมัครสมาชิก
        </button>
      </form>
    </div>
  </div>
</template>

<style scoped>
.backkk {
  background-image: url("../../assets/images/hills-2836301_1920.jpg");
  background-position: center;
  background-size: cover;
}
</style>
