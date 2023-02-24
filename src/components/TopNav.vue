<template>
  <div class=" fixed w-full items-center justify-center">
    <nav class=" bg-indigo-200 opacity-100 py-4 flex justify-center md:justify-between px-4">
      <div class=" hidden md:block">
        <img
        src="https://tecdn.b-cdn.net/img/logo/mdb-transaprent-noshadows.png"
        style="height: 20px"
        alt=""
        loading="lazy" />
      </div>
      <div>
        <div class=" flex justify-center items-center space-x-6">
          <div class=" relative">
            <input type="text" name="" id="" class=" px-4 py-2 bg-gray-100 rounded-full border border-gray-300" placeholder="Search">
            <div class=" absolute top-2 right-3">
              <i class="fa-solid fa-magnifying-glass text-xl"></i>
            </div>
          </div>
          <div><i class="fa-solid fa-user text-2xl"></i></div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
  export default {
    name : "TopNav"
  }
</script>
