<template>
    <div id="contain">
            <div id="carousel">
                            <div id="myCarousel" class="carousel slide" data-ride="carousel">
                <!-- Indicators -->
                <ol class="carousel-indicators">
                <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
                <li data-target="#myCarousel" data-slide-to="1"></li>
                <li data-target="#myCarousel" data-slide-to="2"></li>
                <li data-target="#myCarousel" data-slide-to="3"></li>
                </ol>

                <!-- Wrapper for slides -->
                <div class="carousel-inner" role="listbox">

                <div class="item active">
                    <img src="../image/banner1.jpg" style="width:100%">
                    <div class="carousel-caption">
                    <h3>Chania</h3>
                    <p>The atmosphere in Chania has a touch of Florence and Venice.</p>
                    </div>
                </div>

                <div class="item">
                    <img src="../image/banner1.jpg" style="width:100%">
                    <div class="carousel-caption">
                    <h3>Chania</h3>
                    <p>The atmosphere in Chania has a touch of Florence and Venice.</p>
                    </div>
                </div>
                
                <div class="item">
                    <img src="../image/banner1.jpg" style="width:100%" >
                    <div class="carousel-caption">
                    <h3>Flowers</h3>
                    <p>Beautiful flowers in Kolymbari, Crete.</p>
                    </div>
                </div>

                <div class="item">
                    <img src="../image/banner1.jpg" style="width:100%">
                    <div class="carousel-caption">
                    <h3>Flowers</h3>
                    <p>Beautiful flowers in Kolymbari, Crete.</p>
                    </div>
                </div>
                </div>
            </div>
            </div>

        <div class="container-fluid">
            <h3 style="text-align:center">Lastest Product</h3>
        </div>
    </div>
</template>
<script>
export default {
  name: "Home"
};
</script>

<style>
#contain{
    padding-bottom: 30px;
    margin-top:-30px
}
</style>