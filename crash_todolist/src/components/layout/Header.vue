<template>
    <header class="header">
        <h1>Todo List</h1>
        <div id="nav">
            <router-link to="/"><p>Home</p></router-link> |
            <router-link to="/about"><p>About</p></router-link>
        </div>
    </header>
</template>

<script>
export default {
    name: "Header"
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