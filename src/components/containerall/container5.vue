<template>
    <div class="container5">
            <h1 class="title1">Let's activate your account</h1>
            <h2 class="a1">The application is fast,and only take about 5 minutes</h2>

            <div class="a2">
                <h3 class="a3">First Name*</h3>
                <h3 class="a3">Last Name*</h3>
            </div>

            <div class="a2">
                <input type="text" id="firstname" name="firstname" placeholder="Nombres" class="a4">
                <input type="text" id="lastname" name="lastname" placeholder="Apellido" class="a4">
            </div>

            <div class="a2">
                <h5 class="a3">Email*</h5>
                <h5 class="a3">Phone*</h5>
            </div>
                
            <div class="a2">
                <input type="text" id="email" name="email" placeholder="email@domain.com" class="a4">
                <input type="text" id="phone" name="phone" placeholder=" +886 | 3455 4546 567" class="a4">
            </div>
        </div>
</template>

<script lang="ts">
export default {
  name: 'ContainerComponent5', // 更新為多個單詞
};
</script>

<style scoped>
.container5 {
    width: 70%;
    height: 550px;
    border: 1px solid black;
    border-radius: 8px;
    background-color: white;
    margin-right: 10px;
}
</style>