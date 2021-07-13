<template>
<header>
            <div class="full-logo">
                <div class="full-logo__logo"></div>
                <div class="full-logo__text">
                    <span>MOMENTS OF AIR</span>
                </div>
            </div>
            <div class="menu">
                <div class="menu__item">
                    <p>Features</p>
                </div>
                <div class="menu__item">
                    <p>Technologies</p>
                </div>
                <div class="menu__item">
                    <p>Who we are</p>
                </div>
                <div class="menu__item">
                    <p>How do we deliver</p>
                </div>
                <div class="menu__item">
                    <button>Buy a set</button>
                </div>
            </div>
        </header>
</template>

<script>
export default {
  name: 'Header'
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
header{
    position: fixed;
    top:0;
    left: 0;
    display: flex;
    justify-content: space-around;
    height: 130px;
    width: 100%;

}
.full-logo{
    display: flex;
    &__logo{
        height: 46px;
        width: 46px;
        background-image: url(../assets/logo.png);
        background-position: center;
        background-repeat: no-repeat;
    }
}
.menu{
    display: flex;
    justify-content: space-around;
    align-items: center;
    
}
</style>
