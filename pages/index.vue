<script setup lang="ts">
import QrCode from "~/component/qrCode.vue";

const route = useRoute();
</script>

<template>
  <div class="">
    <!-- <h1>Nuxt Routing set up successfully!</h1>
    <p>Current route: {{ route.path }}</p>
    <a href="https://nuxt.com/docs/getting-started/routing" target="_blank">Learn more about Nuxt Routing</a> -->
    <!-- <QrCode /> -->
    <div class="bg-gray-400 min-h-screen">
      <Center class="py-52">
        <div
          class="card bg-white pt-3 pb-6 pl-3 w-[330px] h-full text-center shadow-lg rounded-2xl"
        >
          <div class="card-container">
            <div class="">
              <img
                src="../public/images/image-qr-code.png"
                alt="Frontend Mentor QR Code"
                class="w-[300px] rounded-lg"
              />
            </div>
            <div class="pt-4">
              <p class="text-xs font-bold to-blue-950">
                Improve your front-end <br />
                skills by build projects
              </p>
              <p class="text-xs pt-2 font-light text-gray-500">
                Scan the QR code to visit Frontend <br />
                Mentor and take your codeing skills <br />
                to the next levels
              </p>
            </div>
          </div>
        </div>
      </Center>
    </div>
  </div>
</template>
