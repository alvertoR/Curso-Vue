<template>
    <div class="container">
        <header class="container--header">
            <NavComponet />
            <h1 class="container---header--title">Este es header</h1>
        </header>
    </div>
</template>


<script>
import NavComponet from "@/components/Nav/Nav.vue";

export default {
    name: 'HeaderComponent',
    components: {
        NavComponet
    }
}
</script>

<style scoped>
.container {
    width: 500px;
    height: 250px;
    margin: 0 auto;
    background-color: red;
}

.container--header {
    display: flex;
    justify-content: center;
}

.container---header--title {
    color: white;
}
</style>