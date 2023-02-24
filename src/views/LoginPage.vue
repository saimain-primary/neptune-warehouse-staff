<template>
  <div class=" flex justify-center items-center h-screen bg-gray-200">
    <div class=" max-w-9xl">
      <div class=" text-center space-y-2 mx-6">
        <img src="" alt="" class=" w-16 h-16 mx-auto my-5">
        <h1 class="text-xl sm:text-2xl md:text-2xl font-bold">Sign in to your account</h1>
        
      </div>
      <div class=" mt-5 bg-white px-4 py-6 space-y-3 border border-gray-200 shadow-sm rounded">
        <div class=" space-y-2">
          <p class=" text-base lg:text-md font-semibold text-gray-600">Email address</p>
          <input type="email"  class=" w-full border border-gray-400 rounded-lg px-3 py-2" placeholder="enter your email">
        </div>
        <div class=" space-y-2">
          <p class="  text-base lg:text-md font-semibold text-gray-600">Password</p>
          <input type="email"  class=" w-full border border-gray-400 rounded-lg px-3 py-2" placeholder="enter your password">
        </div>
        
        <div class=" py-3">
          <div class=" w-full rounded-lg text-center py-2 bg-indigo-700 hover:bg-indigo-600 text-white ">
            Sign in
          </div>
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

