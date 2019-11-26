<template>
    <header class="header">
        <h1>Todo List</h1>
        <Navbar />
    </header>
</template>

<script>
import Navbar from "./Navbar"

export default {
    name: "Header",
    components: {
        Navbar
    },
}
</script>

<style scoped>
.header {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
}
.header #nav {
    display: inline-flex;
}

.header #nav p {
    color: #fff;
    text-decoration: none;
}

.header a {
    color: #fff;
    padding: 0 5px;
    text-decoration: none;
}
</style>