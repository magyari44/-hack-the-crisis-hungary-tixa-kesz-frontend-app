<template>
  <div class="gradient_arrow-image">
    <div class="gradient_arrow-inner_text">
      {{ separatorTitle }}
    </div>
  </div>
</template>

<script>
export default {
  name: "GradientArrow",
  props: ["separatorTitle"]
};
</script>

<style scoped>
.gradient_arrow-image {
  margin-top: 50px;
  background-size: cover;
  background: linear-gradient(145.81deg, #7F7FD5 15.44%, #00AEB3 51.31%, #91EAE4 83.6%) no-repeat;
  position: relative;
  padding: 20px 0;
}

.gradient_arrow-inner_text {
  display: flex;
  justify-content: center;
  font-family: Oswald;
  font-style: normal;
  font-weight: normal;
  font-size: 32px;
  line-height: 40px;
  color: #ffffff;
  position: relative;
  top: 60%;
}
</style>
