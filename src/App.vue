<script setup lang="ts">
  import image from "../images/image-qr-code.png"
</script>

<template>
    <section class="card-container w-[320px] h-[500px]">
      <div class="image-container p-[15px]">
        <img :src="image" alt="QR Code" />
      </div>
      <div class="text-container">
        <h1 class="text">Improve your front-end skills
        by building projects</h1>
        <div class="paragraph-container mt-[10px]  pr-[16px] pl-[16px] w-full">
          <p class="paragraph">Scan the QR code to visit Frontend
          Mentor and take your coding skills to the next level</p>
        </div>
      </div>
    </section>
</template>

<style scoped>
.card-container {
  border-radius: 15px;
  background: hsl(0, 0%, 100%);
}
.card-container img {
  border-radius: 10px;
}
.text-container {
  padding: 10px 24px 15px 18px;
}
h1 {
  font-size: 23px;
  line-height: 1.1;
  font-family: Outfit;
  font-weight: 700;
  color: hsl(218, 44%, 22%);
}
.paragraph {
  font-size: 16px;
  font-family: Outfit;
  color: hsl(220, 15%, 55%);
  font-weight: 400;
}

</style>
