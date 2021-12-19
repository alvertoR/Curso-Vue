<template>
    <nav>
        <ul>
            <li>Nosotros</li>
            <li>Ellos</li>
            <li>Tú</li>
            <li>Él</li>
            <li>Elle</li>
        </ul>
    </nav>
</template>

<script>
export default {
    name:'NavComponet'
}
</script>

<style scoped>
nav {
    width: 300px;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: space-evenly;
}

nav ul li {
    color: white;
    font-weight: bold;
    cursor: pointer;
}
</style>