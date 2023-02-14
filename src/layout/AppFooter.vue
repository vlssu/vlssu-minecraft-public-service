<template>
    <footer class="footer has-cards">
        <div class="container">
            <div class="row row-grid align-items-center my-md">
                <div class="col-lg-6">
                    <h3 class="text-primary font-weight-light mb-2">谢谢你游玩我们的服务器!</h3>
                    <h4 class="mb-0 font-weight-light">你也可以加入我们任意的聊天群</h4>
                </div>
                <div class="col-lg-6 text-lg-center btn-wrapper">
                    <a target="_blank" rel="noopener" href="https://jq.qq.com/?_wv=1027&k=5mq4JvN"
                       class="btn btn-neutral btn-icon-only btn-twitter btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="加入我们的QQ群">
                        <i class="fa fa-qq"></i>
                    </a>
                    <a target="_blank" rel="noopener" href="https://discord.gg/Cs542v28Xt"
                       class="btn btn-neutral btn-icon-only btn-facebook btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="加入我们Discord">
                        <i class="fa fa-comments"></i>
                    </a>
                </div>
            </div>
            <hr>
            <div class="row align-items-center justify-content-md-between">
                <div class="col-md-7">
                    <div class="copyright">
                        &copy; 2018 - {{year}}
                        <a href="https://blog.vlssu.com" target="_blank" rel="noopener">飒爽师叔</a>|
                        <a href="http://beian.miit.gov.cn" class="nav-link" target="_blank" rel="noopener">赣ICP备2023000574号-1</a>|
                        <a href="http://www.beian.gov.cn/portal/registerSystemInfo?recordcode=36010802000815" target="_blank" class="nav-link" rel="noopener"><img src="/img/icons/gongan.png"/>&nbsp赣公网安备 36010802000815号</a>
                    </div>
                </div>
                <div class="col-md-5">
                    <ul class="nav nav-footer justify-content-end">
                        <li class="nav-item">
                            <a href="//blog.vlssu.com" class="nav-link" target="_blank" rel="noopener">师叔的小窝</a>
                        </li>
                        <li class="nav-item">
                            <a href="//skin.vlssu.com" class="nav-link" target="_blank" rel="noopener">VlssuSkin皮肤站</a>
                        </li>
                        <li class="nav-item">
                            <a href="//docs.vlssu.cn"
                               class="nav-link" target="_blank" rel="noopener">服务器文档</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style>
</style>
