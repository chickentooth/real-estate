<template>
    <nav class="navbar navbar-expand-lg bg-info fixed-top navbar-transparent " color-on-scroll="200">
        <div class="container">
            <div class="navbar-translate">
                <!--<img rel="tooltip" title="" data-placement="bottom" target="_blank" data-original-title="CEN Group, The Real Property" style="width: 20%" src="../../../static/img/cen-group.png" alt="">-->

                <button class="navbar-toggler navbar-toggler" type="button" data-toggle="collapse" data-target="#navigation" aria-controls="navigation-index" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-bar bar1"></span>
                    <span class="navbar-toggler-bar bar2"></span>
                    <span class="navbar-toggler-bar bar3"></span>
                </button>
            </div>
            <div class="collapse navbar-collapse justify-content-end" id="navigation" data-nav-image="./assets/img/blurred-image-1.jpg">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" rel="tooltip" title="TRANG CHỦ" data-placement="bottom" href="javascript:void(0)" onclick="scrollToDownload()">
                            <i class="now-ui-icons objects_planet"></i>
                            <p>TRANG CHỦ</p>
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" rel="tooltip" title="TỔNG QUAN" data-placement="bottom" href="./documentation/tutorial-components.html" target="_blank">
                            <i class="now-ui-icons files_paper"></i>
                            <p>TỔNG QUAN</p>
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" rel="tooltip" title="GIÁ CẢ" data-placement="bottom" href="https://www.creative-tim.com/product/now-ui-kit-pro" target="_blank">
                            <i class="now-ui-icons business_money-coins"></i>
                            <p>GIÁ CẢ</p>
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" rel="tooltip" title="GIÁ CẢ" data-placement="bottom" href="https://www.creative-tim.com/product/now-ui-kit-pro" target="_blank">
                            <i class="now-ui-icons design_app"></i>
                            <p>MẶT BẰNG</p>
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" rel="tooltip" title="GIÁ CẢ" data-placement="bottom" href="https://www.creative-tim.com/product/now-ui-kit-pro" target="_blank">
                            <i class="now-ui-icons education_agenda-bookmark"></i>
                            <p>PHÁP LÝ</p>
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" rel="tooltip" title="GIÁ CẢ" data-placement="bottom" href="tel:0904684254" target="_blank">
                            <i class="now-ui-icons objects_spaceship"></i>
                            <p>LIÊN HỆ</p>
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" rel="tooltip" title="Facebook của chúng tôi" data-placement="bottom" href="https://www.facebook.com/sonhoang0302" target="_blank">
                            <i class="fa fa-facebook-square"></i>
                            <p class="d-lg-none d-xl-none">Facebook</p>
                        </a>
                    </li>

                </ul>
            </div>
        </div>
    </nav>
    
</template>

<script>
    export default {
        name: "navbar"
    }
</script>

<style scoped>

</style>