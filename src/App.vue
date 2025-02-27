<script>
    import ContainerComponent from './components/containerall/container.vue';
    import ContainerComponent2 from './components/containerall/container2.vue';
    import ContainerComponent3 from './components/containerall/container3.vue';
    import ContainerComponent4 from './components/containerall/container4.vue';
    import ContainerComponent5 from './components/containerall/container5.vue';
    import ContainerComponent6 from './components/containerall/container6.vue';
    export default {
    name: 'App',
    components: {
        ContainerComponent,
        ContainerComponent2,
        ContainerComponent3,
        ContainerComponent4,
        ContainerComponent5,
        ContainerComponent6,
    },
};
</script>

<template>
    <ContainerComponent />
    <ContainerComponent2 />
    <br>
    <ContainerComponent3 />
    <br>
    <div class="wrapper">
        <ContainerComponent4/>
        <ContainerComponent5/>
    </div>
    <br>
    <ContainerComponent6 />
</template>

