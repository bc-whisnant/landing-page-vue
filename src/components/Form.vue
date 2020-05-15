<template>
  <form method="post" action="#">
    <InputField unique="first_name" label="First Name" />
    <InputField unique="last_name" label="Last Name" />
    <InputField unique="email" label="Email" />
    <div class="input-wrapper">
      <button>Contact Us</button>
    </div>
  </form>
</template>

<script>
import InputField from "./InputField";
export default {
  name: "Form",
  components: {
    InputField,
  },
};
</script>

<style scoped>
.input-wrapper > button {
  background: #555ae4;
  color: #fff;
  border-radius: 5px;
  padding: 10px;
}
</style>
