<script setup>
import TheFooter from '../components/TheFooter.vue'
import TheHeader from '../components/TheHeader.vue'
import IconBesnik from '../components/icons/IconBesnik.vue'
import IconRent from '../components/icons/IconRent.vue'
import IconBuyer from '../components/icons/IconBuyer.vue'
import IconSeller from '../components/icons/IconSeller.vue'
import TheCard from '../components/TheCard.vue'

</script>

<template>
  <main>
    <div class="bg-[#E6F0FF]">
      <TheHeader />
      <div class="container flex flex-row justify-between items-center">
        <div class="">
          <p class="pb-6">Welcome to Besnik Agency</p>
          <h1 class="text-6xl font-bold">
            Discover a place <br /> you'll love to live.
          </h1>
          <p class="pt-6">
            get the best real estate deals first,
            before they hit the mass <br/> market! hot foreclosure
            deals with one simple search
          </p>
          <p class="pt-10">More about us</p>
        </div>
        <div class="hidden lg:block">
          <img src="@/assets/images/houseillustration.png" alt="">
        </div>
      </div>
    </div>
    <div class="container py-16">
      <div class="block lg:flex lg:felx-row justify-between pb-10">
        <div>
          <IconBesnik />
          <p class="pt-4 text-[#7D8589]">More than 45,000+ companies trust besnik</p>
        </div>
        <div class="mt-10 lg:mt-0">
          <img src="@/assets/images/star.png" alt="star">
          <p class="pt-4 text-[#7D8589]">5 Star Rating (2k+ Review)</p>
        </div>
      </div>
      <div class="hidden lg:grid lg:gap-x-8 lg:grid-cols-5 items-center pl-10">
        <span>
          <img src="@/assets/images/companiesLogo/meUndies.png" alt="meUndiesLogo">
        </span>
        <span>
          <img src="@/assets/images/companiesLogo/slack.png" alt="slackLogo">
        </span>
        <span>
          <img src="@/assets/images/companiesLogo/amazon.png" alt="amazonLogo">
        </span>
        <span>
          <img src="@/assets/images/companiesLogo/wooCommerce.png" alt="wooCommerceLogo">
        </span>
        <span>
          <img src="@/assets/images/companiesLogo/sitePoint.png" alt="sitePointLogo">
        </span>
      </div>
    </div>
    <!-- How it works -->
    <div class="container py-16">
      <div class="flex flex-col items-center">
        <hr class="border-2 border-[#000339] rounded w-14 my-10">
        <h2 class="text-[#000339]">How it works ?</h2>
        <p class="text-center text-[#5A6473]">
          Everything you need to know when
          you're looking to <br/> buy,rent, or sell -
          all in one place
        </p>
      </div>
      <div class="flex flex-row justify-between w-1/2 mx-auto py-10">
        <span class="flex flex-col items-center">
          <IconBuyer />
          <h4 class="text-[#3B3C45] text-center">Buyer Guides</h4>
          <p class="text-[#0689FF] font-medium">How to buy</p>
        </span>
        <span class="flex flex-col items-center">
          <IconRent />
          <h4 class="text-[#3B3C45]">Renter Guides</h4>
          <p class="text-[#0689FF] font-medium">How to rent</p>
        </span>
        <span class="flex flex-col items-center">
          <IconSeller />
          <h4 class="text-[#3B3C45]">Seller Guides</h4>
          <p class="text-[#0689FF] font-medium">How to Sell</p>
        </span>
      </div>
      <div class="text-center">Sell full Guidelines</div>
    </div>
    <div class="bg-[#F5FAFE]">
      <div class="container py-16">
        <div class="text-center lg:text-left">
          <h2 class="text-[#000339]">Featured Properties</h2>
          <span class="block lg:flex lg:flex-row justify-between items-center pt-4">
            <p class="text-[#5A6473] font-medium">Everything you need to know when you're looking</p>
            <p class="text-[#0689FF] font-medium">View All Properties</p>
          </span>
        </div>
        <div>
        </div>
        <TheCard />
      </div>
    </div>
    <div>
      <div class="container py-16">
        <div class="flex flex-row justify-around items-center">
          <div class="relative p-0">
            <div class="w-60 absolute -left-28 rounded-b-2xl bg-white p-4">
              <span class="flex flex-row justify-between items-center">
                <h2 class="text-[#000339]">40,000+</h2>
                <img src="@/assets/images/growth.svg" alt="">
              </span>
              <p class="text-[#A7A7A7] font-medium">By avarage for 2 bedroom apments in San Francisco, CA</p>
              <hr class="border-2 border-[#E9E9E9] rounded w-full my-5">
              <span>
                <img src="../assets/images/users.png" class="w-full" alt="">
              </span>
            </div>
            <div class="h-fit">
              <img src="@/assets/images/house5.jpg" class="h-fit" alt="">
            </div>
          </div>
          <div class="w-96 h-96 p-10">
            <hr class="border-2 border-[#000339] rounded w-14 my-5">
            <h2 class="text-[#000339]">You’ve found a neighborhood you love.</h2>
            <p class="pt-4 text-[#5A6473]">
              When you own a home, you’re committing to
              living in one location for a while. In a recent
              Trulia survey, we found that five out of six
              respondents said finding the right neighborhood
            </p>
          </div>
        </div>
        <div class="flex flex-row justify-around items-center pt-20">
          <span>
            <h2>2,500</h2>
            <p class="text-sm text-[#7B8087]">Homes for sale</p>
          </span>

          <span>
            <h2>5000+</h2>
            <p class="text-sm text-[#7B8087]">Homes Recently sold</p>
          </span>

          <span>
            <h2>170+</h2>
            <p class="text-sm text-[#7B8087]">Price Reduced</p>
          </span>
        </div>
      </div>
    </div>
    <!-- feature Properties -->
    <div class="container py-16">
      <div class="bg-[#063183] rounded-xl relative p-28">
        <div>
          <h2 class="text-white pb-4">Featured Properties</h2>
          <p class="text-white pb-6">Everything you need to know when your're looking</p>
          <div class="text-white">Get Started Now</div>
        </div>
        <div class="hidden lg:block lg:absolute -right-28 -top-12 overflow-hidden h-[25rem]">
          <img src="@/assets/images/mobilePhone.png" alt="">
        </div>
      </div>
    </div>
    <!-- footer -->
    <TheFooter />
  </main>
</template>
