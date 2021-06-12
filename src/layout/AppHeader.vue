<template>
    <header class="header-global">
        <base-nav class="navbar-main" transparent type="" effect="light" expand>
            <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
                <img src="img/brand/blue.png" alt="logo">
            </router-link>

            <div class="row" slot="content-header" slot-scope="{closeMenu}">
                <div class="col-6 collapse-brand">
                    <a href="https://demos.creative-tim.com/vue-argon-design-system/documentation/">
                        <img src="img/brand/blue.png">
                    </a>
                </div>
                <div class="col-6 collapse-close">
                    <close-button @click="closeMenu"></close-button>
                </div>
            </div>

            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
                <base-dropdown class="nav-item" menu-classes="dropdown-menu-xl">
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="ni ni-ui-04 d-lg-none"></i>
                        <span class="btn btn-primary">服务器旗下站点</span>
                    </a>
                    <div class="dropdown-menu-inner">
                        <a href="//skin.vlssu.com"
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-primary rounded-circle text-white">
                                <i class="ni ni-badge"></i>
                            </div>
                            <div class="media-body ml-3">
                                <h6 class="heading text-primary mb-md-1">VLSSUSKIN皮肤站</h6>
                                <p class="description d-none d-md-inline-block mb-0">这是我们服务器的皮肤站站点，也是进我们服务器最推荐的一个进入方式，在一切设置好并熟悉你将会体验到不一样的快捷</p>
                            </div>
                        </a>
                        <a href="//bbs.vlssu.com"
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-warning rounded-circle text-white">
                                <i class="ni ni-chat-round"></i>
                            </div>
                            <div class="media-body ml-3">
                                <h5 class="heading text-warning mb-md-1">VlssuBBS论坛</h5>
                                <p class="description d-none d-md-inline-block mb-0">服务器的一部分通知或交流都可以在这里，我们也比较推荐在这发出你的疑问或问题，我们会尽力完成你的建议或问题！</p>
                            </div>
                        </a>
                        <a href="//ban.vlssu.com"
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-warning rounded-circle text-white">
                                <i class="fa fa-wheelchair"></i>
                            </div>
                            <div class="media-body ml-3">
                                <h5 class="heading text-warning mb-md-1">VlssuBan</h5>
                                <p class="description d-none d-md-inline-block mb-0">我们会将所有熊服务器或违规的人同步在网站中，让那些熊服务器的人公开示众！</p>
                            </div>
                        </a>
                    </div>
                </base-dropdown>
                <base-dropdown tag="li" class="nav-item">
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="ni ni-collection d-lg-none"></i>
                        <span class="btn btn-primary">服务器卫星地图</span>
                    </a>
                    <router-link to="//zn.vlssu.com:40002" class="dropdown-item">生存服</router-link>
                    <router-link to="//zn.vlssu.com:40003" class="dropdown-item">创造服</router-link>
                    <router-link to="//zn.vlssu.com:40004" class="dropdown-item">模组服</router-link>
                    <router-link to="//zn.vlssu.com:40005" class="dropdown-item">空岛服</router-link>
                    <router-link to="//zn.vlssu.com:40007" class="dropdown-item">OLD生存服</router-link>
                </base-dropdown>
            </ul>
            <ul class="navbar-nav align-items-lg-center ml-lg-auto">
                <li class="nav-item">
                    <a class="btn active btn-primary btn-sm " href="https://jmc.vlssu.com/manual/faq" role="button" aria-pressed="true" title="常见问题">
                        <i class="fa fa-question-circle"> 常见问题</i>
                        <span class="nav-link-inner--text d-lg-none">常见问题</span>
                    </a>
                </li>
                <li class="nav-item d-none d-lg-block ml-lg-4">
                    <a href="https://cloud.vlssu.com/#/s/ZNCW" target="_blank" rel="noopener"
                       class="btn btn-neutral btn-icon">
                <span class="btn-inner--icon">
                  <i class="fa fa-cloud-download mr-2"></i>
                </span>
                        <span class="nav-link-inner--text">Download</span>
                    </a>
                </li>
            </ul>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
};
</script>
<style>
</style>
