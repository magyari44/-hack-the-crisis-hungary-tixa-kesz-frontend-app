<template>
  <div class="custom_headline-image">
    <div class="custom_headline-inner_text">
      {{ customTitle }}
    </div>
  </div>
</template>

<script>
export default {
  props: ["customTitle"],
  name: "headlineTitle"
};
</script>

<style scoped>
.custom_headline-image {
  background-image: url("../../public/img/background/custom-headline-background.png");
  background-repeat: no-repeat;
  background-size: cover;
  background: linear-gradient(145.81deg, #7F7FD5 15.44%, #00AEB3 51.31%, #91EAE4 83.6%);
  padding:  5% 0 5% 0;
  position: relative;
}

.custom_headline-inner_text {
  display: flex;
  justify-content: center;
  font-family: Oswald;
  font-style: normal;
  font-weight: normal;
  font-size: 32px;
  line-height: 40px;
  color: #ffffff;
  position: relative;
}
</style>
