<template>
    <div>
        <ul class="nav">
            <router-link tag='li' :to="{name:'Home'}" exact>
                <a>Home</a>
            </router-link>
            <router-link tag='li' :to="{name:'Categories'}">
                <a>Categories</a>
            </router-link>
            <router-link tag='li' :to="{name:'About'}">
                <a>About</a>
            </router-link>
            <router-link tag='li' :to="{name:'Contact'}">
                <a>Contact</a>
            </router-link>
        </ul>
    </div>
</template>
<script>
export default {
    name: "Mainmenu",

}
</script>

<style lang="scss" scoped>
.nav {
    background-color: black;
    color: white;
    overflow: hidden;
    display: flex;
    justify-content: center;

    li {
        display: inline-block;
        padding: 10px;
    }
    
    a {
        margin-right: 5px;
        text-decoration: none;
        color:white;
    }
    .router-link-exact-active{
        color: white;
        background-color: green;
    }
}
</style>