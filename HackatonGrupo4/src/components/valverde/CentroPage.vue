<template>
    <div id="CentroPag">
        <div>
            <div class="resumen">
                <img src="@/assets/valverdeIcons/row_black.png" alt="" class="row">
                <h1>Resumen de compras </h1>
            </div>
            <div></div>

        </div>
        <div>
            <div>
                <div>Subtotal</div>
                <div id="total"></div>
            </div>

            <div></div>
            <div></div>
        </div>
    </div>
</template>
<script>
export default {
    name: `CentroPag`
}
</script>
<style>
#CentroPag {
    display: flex;
}

.total {
    border-top: 1px solid black;
    display: flex;
    width: 804px;
    font-size: 25px;
}

.resumen {
    display: flex;

}

.row {
    width: 48px;
    height: 24px;
    padding-top: 27px;
    padding-right: 20px;

}

#CentroPag {
    margin-left: 100px;
}
</style>
