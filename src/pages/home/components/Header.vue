<template>
    <div class="header">
        <div class="h-left">
            <div class="iconfont back-icon">&#xe624;</div>
        </div>
        <div class="h-center">
            <span class="iconfont">&#xe632;</span>
            请选择城市
        </div>
        <div class="h-right">&#xe64a;城市</div>
    </div>
</template>
<script>
export default {
  name: 'HomeHeader'
}
</script>
<style lang="stylus" scoped>
   .header
        display: flex
        line-height: .86rem
        background-color: #00bcd4
        color: #fff
        .h-left
            width: .64rem
            float: left
            .back-icon
                text-align: center
                font-size: .4rem
        .h-center
            flex: 1
            border-radius: .1rem
            height: .64rem
            line-height: .64rem
            margin-top: .12rem
            margin-left: .2rem
            padding-left: .2rem
            background: #fff
            color: #ccc
        .h-right
            width: 1.24rem
            text-align:center
            float: right
</style>
