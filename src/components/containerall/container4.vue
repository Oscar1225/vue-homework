<template>
    <div class="container4">
            <h1 class="title">Activate account</h1>

            <span class="c1">
                <h2 class="c2">step1</h2>
                <h2>Contact Information</h2>
                <h2>in progress</h2>
            </span>

            <span class="c1">
                <h2 class="c2">step2</h2>
                <h2>Business Information</h2>
                <h2>in progress</h2>
            </span>

            <span class="c1">
                <h2 class="c2">step3</h2>
                <h2>Banking Information</h2>
                <h2>in progress</h2>
            </span>

            <span class="c1">
                <h2 class="c2">step4</h2>
                <h2>Ownership Information</h2>
                <h2>in progress</h2>
            </span>

            <span class="c1">
                <h2 class="c2">step5</h2>
                <h2>Terms & Information</h2>
                <h2>in progress</h2>
            </span>
        </div>
</template>

<script lang="ts">
export default {
    name: 'ContainerComponent4', // 更新為多個單詞
};
</script>

<style scoped>
    .container4 {
    width: 25%;
    height:550px;
    border: 1px solid black;
    display: flex;
    border-radius: 8px;
    flex-direction: column;
    background-color: white;
    margin-left: 10px;
}
</style>