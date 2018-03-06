<template>
<div class="index-page sidebar-collapse">
    <Navbar/>
    <div class="wrapper">
        <div class="page-header clear-filter" filter-color="black"  style="background: rgba(0, 0, 0, 0.4);">
            <div class="page-header-image" style="background-image: url(&quot;../../static/img/cairong.jpg&quot;); transform: translate3d(0px, 107px, 0px);">
            </div>
            <div class="container">
                <div class="content-center brand">
                    <br>
                    <img class="n-logo animated flip" src="../../static/img/now-logo.png" alt="">
                    <br>
                    <h2 class="h1-seo text-capitalize">Đất đặc khu kinh tế Vân Đồn</h2>
                    <div class="container">
                        <div class="row">
                            <div class="col-md-8 ml-auto mr-auto text-center">
                                <h1 class="title animated shake">Cơ hội đầu tư cực tốt</h1>
                                <h2 class="description text-light  animated wobble">Lợi nhuận lên tới <span class="title text-primary">50% </span> - <span class="title text-primary">150% </span> một năm</h2>
                            </div>
                        </div>
                        <div class="separator separator-primary"></div>
                    </div>
                </div>
            </div>
        </div>
            <div class="section" id="carousel">
                <div class="container">
                    <div class="row justify-content-center">
                        <div class="col-9">
                            <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
                                <ol class="carousel-indicators">
                                    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                                    <li data-target="#carouselExampleIndicators" data-slide-to="1" class=""></li>
                                </ol>
                                <div class="carousel-inner" role="listbox">
                                    <div class="carousel-item active">
                                        <img class="d-block" src="../../static/img/info1.png" alt="First slide">
                                    </div>
                                    <div class="carousel-item">
                                        <img class="d-block" src="../../static/img/info2.png" alt="Second slide">
                                    </div>
                                </div>
                                <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                                    <i class="now-ui-icons arrows-1_minimal-left"></i>
                                </a>
                                <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                                    <i class="now-ui-icons arrows-1_minimal-right"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="section section-download" id="#download-section" data-background-color="black">
                <div class="container">
                    <div class="row justify-content-md-center">
                        <div class="text-center col-md-12 col-lg-8">
                            <h3 class="title">Tôi không hiểu các bạn còn chờ cái đầu buồi gì ?</h3>
                            <h5 class="description">Gọi ngay chúng tôi đi</h5>
                        </div>
                        <div class="text-center col-md-12 col-lg-8">
                            <a href="tel:0972289170" v-on:scroll="onScroll" v-bind:class="{wobble : isWobble}"  class="btn btn-primary btn-lg btn-round animated" role="button">
                                <i class="si si-call-out"></i>
                                Gọi Ngay
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- Sart Modal -->
        <!--  End Modal -->

       <vue-footer/>   <!--vue-footer == VueFooter-->
    </div>
</div>
</template>

<script>
    import Navbar from './template/navbar'
    import VueFooter from './template/footer' /*this is file name*/
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Vuejs Ville',
        isWobble: false
    }
  },
    components : {
      Navbar, VueFooter
    },
    methods: {
        onScroll(event) {
            console.log("scrolling");
        }
    }

}
</script>
