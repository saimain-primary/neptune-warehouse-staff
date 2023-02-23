<template>
  <div class=" flex justify-center items-center h-screen bg-gray-200">
    <div class=" max-w-9xl">
      <div class=" text-center space-y-2">
        <img src="" alt="" class=" w-16 h-16 mx-auto my-5">
        <h1 class="text-3xl sm:text-3xl md:text-4xl font-bold">Sign in to your account</h1>
        <p class=" text-lg text-indigo-500 font-medium"><span class=" text-gray-400">Or</span> start your 14 - day free trial</p>
      </div>
      <div class=" mt-5 bg-white px-4 py-6 space-y-3 border border-gray-200 shadow-sm">
        <div class=" space-y-2">
          <p class=" text-lg font-semibold text-gray-600">Email address</p>
          <input type="email"  class=" w-full border border-gray-400 rounded-lg px-3 py-2">
        </div>
        <div class=" space-y-2">
          <p class=" text-lg font-semibold text-gray-600">Password</p>
          <input type="email"  class=" w-full border border-gray-400 rounded-lg px-3 py-2">
        </div>
        <div class=" flex justify-between">
          <div class=" flex space-x-2"><input type="checkbox" > <p class="text-lg font-semibold text-gray-600">Remember me</p></div>
          <div>
            <p class=" text-indigo-400 text-base">Forgot your password?</p>
          </div>
        </div>
        <div class=" w-full rounded-lg text-center py-2 bg-indigo-400 text-white">
          Sign in
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name : 'LoginPage'
  }
</script>

