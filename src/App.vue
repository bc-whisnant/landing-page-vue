<template>
  <div id="app">
    <Nav />
    <div class="hero-box">
      <div class="hero-box-left">
        <LargeText>
          Your trusted web developers, just a click away.
        </LargeText>
        <MediumText>
          Meet our team of web dev experts ready to take on your biggest
          challenges and turn them into opportunities to outshine your
          competition. Connect with us today to get started.
        </MediumText>
      </div>
      <div class="hero-box-right">
        <Form />
      </div>
    </div>
  </div>
</template>

<script>
import Nav from "./components/Nav.vue";
import Form from "./components/Form.vue";
import LargeText from "./components/LargeText.vue";
import MediumText from "./components/MediumText.vue";



export default {
  name: "App",
  components: {
    Nav,
    Form,
    LargeText,
    MediumText
  },
};
</script>
<style scoped>
body {
  background: #fff;
  color: #777;
}
.hero-box {
    background: #f3f3ff;
    display: flex;
}
.hero-box-left {
    width: 400px;
    margin: 25px;
}
.hero-box-right {
    width: 100%;
    margin: 25px; 
}



</style>
