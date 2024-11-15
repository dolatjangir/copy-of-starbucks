<script setup>


</script>

<template>
  <div class="container sm:flex sm:justify-center px-10 py-4">
    <div class="flex items-center">
      <img class="starbucks-img sm:w-[30px] md:w-[38px] lg:w-[38px] xl:w-[60.3px]  " src="https://www.starbucks.in/assets/icon/logo.png" /></div>

    <div class="header sm:flex  sm:justify-between sm:items-center w-screen  px-4  sm:h-[64px]">
                  <div class="left sm:hidden 2xl:block  text-lg font-bold pl-[20px] ">
                <button class="menu-button">MENU</button>
                <button class="rewards-button border-b-4 border-green-950">REWARD</button>
                <button class="">GIFT CARDS</button>
            </div>
            
            <div class="right  sm:invisible 2xl:visible font-semibold">
                <button class="pr-6 flex gap-2 justify-center items-center text-lg"><i class="fa-solid fa-location-dot"></i> Find Store</button>
                <button class="sign-in border border-neutral-400 rounded-3xl px-4 py-2">Sign In</button>
                <button class="join-now bg-black text-white rounded-3xl px-4 ">Join Now</button>
            </div>
            <div class="hamburger pr-3 text-xl 2xl:hidden">
             <i class="fa-solid fa-bars"></i>
            </div>
        </div>
      </div>
</template>
<style scoped>
.left, .right{
display: flex;
flex-direction: row;
gap: 16px;
}</style>
