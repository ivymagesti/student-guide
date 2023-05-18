<template>
    <header>
        <nav class="container">
            <a href="/"><img id="logo" src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/wdev.svg">
        </a>
        <img alt="abrir menu" id="menu-button" src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/menu.svg">
        </nav>
    </header>
</template>

<script>
export default{
    name: 'AppHeader',
}
</script>

<style scoped>

header{
    background-color : var(--color-background-nav);
    height: 60px;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}

nav{
    display: flex;
    justify-content: space-between;
}

#logo{
    width: 130px;
}
#menu-button{
    width: 30px;
}

</style>
