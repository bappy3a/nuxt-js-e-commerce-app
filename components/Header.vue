<template lang="">
    <div>
        <div class="container">
            <div class="flex justify-between items-center py-6">
                <Logo/>

                <div class="w-96">
                    <div class="border border-gray-100 p-1 flex rounded-full items-center">
                        <div class="min-w-max px-3">
                            <img src="~/assets/img/search.svg" alt="">
                        </div>
                        <input class="w-full px-3 pxy-3 focus:outline-none" type="search" name="" placeholder="Search here ..">
                        <button class="bg-gray bg-button-bg px-6 rounded-full py-2 text-white" type="submit">Search</button>
                    </div>
                </div>

                <div class="min-w-max flex items-center">
                    <nuxt-link to="/" class="flex items-center"><span class="bg-icon-box rounded-full hover:bg-gray-200 inline-block flex items-center justify-center"><img src="~/assets/img/heart.svg" alt=""></span></nuxt-link>
                    <nuxt-link to="/" class="relative mx-4"><span class="bg-icon-box rounded-full hover:bg-gray-200 inline-block flex items-center justify-center"><img src="~/assets/img/shoping_bag.svg" alt=""></span><span class="absolute bg-red-600 w-4 h-4 top-0 right-0 rounded-full text-xs flex justify-center items-center text-white">0</span></nuxt-link>
                    <nuxt-link to="/" class="flex items-center"><span class="bg-icon-box rounded-full hover:bg-gray-200 inline-block flex items-center justify-center"><img src="~/assets/img/user.svg" alt=""></span><span>Accoutn</span></nuxt-link>
                </div>
            </div>

            <div class="flex items-center">
                <div class="w-96">
                  <div class="bg-green-600 flex rounded-full px-4 py-2 items-center cursor-pointer">
                    <div class="min-w-max">
                       <img src="~/assets/img/menu-right.png" alt="">
                    </div>
                    <div class="w-full text-center px-6 text-white">
                      All Categorys
                    </div>
                    <div class="min-w-max">
                      <img src="~/assets/img/chevron-down.png" alt="">
                    </div>
                  </div>
                </div>
                <div class="w-full">
                  <ul class="flex justify-center ">
                    <li>
                      <nuxt-link class="p-4" to="/">Home</nuxt-link>
                      <nuxt-link class="p-4" to="/">Shop</nuxt-link>
                      <nuxt-link class="p-4" to="/">Blogs</nuxt-link>
                      <nuxt-link class="p-4" to="/">Contact</nuxt-link>
                      <nuxt-link class="p-4" to="/">Track Order</nuxt-link>
                    </li>
                  </ul>
                </div>
                <div class="flex min-w-max bg-rark-orange">
                  <img src="~/assets/img/u_percentage.png" class="mr-3" alt=""> Special Offers!
                </div>
            </div>

        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="">

</style>
