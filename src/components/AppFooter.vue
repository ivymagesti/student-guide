<template>
    <footer>

        <div></div>
    </footer>
</template>

<script>
export default{
    name: 'AppFooter',
}
</script>

<style scoped>

footer{
    background-color : var(--color-background-footer);
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
