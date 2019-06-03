<template>
    <div class="order">
        <div class="orderhead">
            <i class="icon iconfont icon-fanhui"></i>
            <p>订单列表</p>
        </div>
    </div>
</template>
<script>

export default {

}
</script>
<style lang="scss" scoped>
.order{
    width:100%;
    height:100%;
    display:flex;
    flex-direction:column;
}
.orderhead{
    width: 100%;
    height:50px;
    background:#3190e8;
    display:flex;
    color:white;
    justify-content: center;
    align-items: center;
    font-weight:600;
    p{
        flex:1;
        height: 100%;
        display:flex;
        justify-content: center;
        align-items: center;
    }
    .icon-fanhui{
            width: 30px;
            height: 50px;
            line-height: 50px;
            padding-left:20px;
            box-sizing:border-box;
        }
}
</style>
