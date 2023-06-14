<script>
export default {
    mounted() {
        const container = this.$refs.container;
        const script = document.createElement('script');
        script.async = true;
        script.src = 'https://cpwebassets.codepen.io/assets/embed/ei.js';
        container.append(script);
    },
};
</script>

<template>
    <div ref="container">
        Here is a custom element with a script
    </div>
</template>