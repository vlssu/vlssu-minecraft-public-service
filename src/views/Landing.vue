<template>
    <div>
        <div class="position-relative">
            <!-- shape Hero -->
            <section class="section-shaped my-0">
                <div class="shape shape-style-1 bj-2 shape-skew">
                </div>
                <div class="container shape-container d-flex">
                    <div class="col px-0">
                        <div class="row">
                            <div class="col-lg-6">
                                <h1 class="display-3  text-white">欢迎来到我们的服务器
                                    <span>VLSSU以玩家为核心多玩法的服务器！</span>
                                </h1>
                                <p class="lead  text-white">我们并非局限于孤立的绽放</p>
                                <p class="lead  text-white">    而是共同繁荣下的各自璀璨</p>
                                <div class="btn-wrapper">
                                    <base-button tag="a"
                                                 href="https://docs.vlssu.cn"
                                                 class="mb-3 mb-sm-0"
                                                 type="info"
                                                 icon="fa fa-code">
                                        服务器文档
                                    </base-button>
                                    <base-button tag="a"
                                                 href="https://cloud.vlssu.com/s/ZNCW"
                                                 class="mb-3 mb-sm-0"
                                                 type="white"
                                                 icon="ni ni-cloud-download-95">
                                        下载客户端
                                    </base-button>
                                    <base-button tag="a"
                                                 href="https://jq.qq.com/?_wv=1027&k=5mq4JvN"
                                                 class="mb-3 mb-sm-0"
                                                 type="success"
                                                 icon="fa fa-qq">
                                        加入QQ群
                                    </base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <!-- 1st Hero Variation -->
        </div>
        <section class="section section-lg pt-lg-0 mt--200">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-lg-12">
                        <div class="row row-grid">
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-check-bold" type="primary" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-primary text-uppercase">生存服务器</h6>
                                    <p class="description mt-3">长期的生存创新与建造。添加了辅助生存的插件来帮助玩家更具创新的建造生存。</p>
                                    <div>
                                        <badge type="primary" rounded>生存</badge>
                                        <badge type="primary" rounded>建造</badge>
                                        <badge type="primary" rounded>合作</badge>
                                    </div>
                                    <base-button tag="a" href="https://docs.vlssu.cn/summary/server/survive" type="primary" class="mt-4">
                                        了解更多
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-istanbul" type="success" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-success text-uppercase">创造服务器</h6>
                                    <p class="description mt-3">同世界，共创造。拥有完善的地皮系统，领会你与不同建筑师的创新风采。</p>
                                    <div>
                                        <badge type="success" rounded>创造</badge>
                                        <badge type="success" rounded>创新</badge>
                                        <badge type="success" rounded>创世</badge>
                                        <badge type="success" rounded>合作</badge>
                                    </div>
                                    <base-button tag="a" href="https://docs.vlssu.cn/summary/server/creative" type="success" class="mt-4">
                                        了解更多
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-books" type="info" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-info text-uppercase">模组服务器</h6>
                                    <p class="description mt-3">提供玩家自由选择的模组或玩家期待的名气整合。冒险与养老，仅是你一念之间。</p>
                                    <div>
                                        <badge type="info" rounded>新玩法</badge>
                                        <badge type="info" rounded>新模式</badge>
                                        <badge type="info" rounded>新体验</badge>
                                    </div>
                                    <base-button tag="a" href="https://docs.vlssu.cn/summary/server/mod-server" type="info" class="mt-4">
                                        了解更多
                                    </base-button>
                                </card>
                            </div>
                        </div>
                        <div class="row row-grid">
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-planet" type="warning" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-warning text-uppercase">空岛服务器</h6>
                                    <p class="description mt-3">多种岛屿提供给玩家选择，同一天空下不一样的岛屿生存。</p>
                                    <div>
                                        <badge type="warning" rounded>合作</badge>
                                        <badge type="warning" rounded>孤岛生存</badge>
                                        <badge type="warning" rounded>无中生有</badge>
                                    </div>
                                    <base-button tag="a" href="https://docs.vlssu.cn/summary/server/bskyblock" type="warning" class="mt-4">
                                        了解更多
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-send" type="yellow" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-yellow text-uppercase">快照服务器</h6>
                                    <p class="description mt-3">与时更新的世界，在此将更新的玩法一窥究竟。</p>
                                    <div>
                                        <badge type="yellow" rounded>实时跟进</badge>
                                        <badge type="yellow" rounded>原版纯生存</badge>
                                        <badge type="yellow" rounded>全新体验</badge>
                                    </div>
                                    <base-button tag="a" href="https://docs.vlssu.cn/summary/server/beta-survive" type="yellow" class="mt-4">
                                        了解更多
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-fat-add" type="light" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-light text-uppercase">敬请期待</h6>
                                    <p class="description mt-3">有什么建议可以私信我们，我们将考虑实现。</p>
                                    <div>
                                        <badge type="light" rounded>敬请期待</badge>
                                    </div>
                                    <base-button tag="a" href="https://docs.vlssu.cn/summary/server/login" type="light" class="mt-4">
                                        了解更多
                                    </base-button>
                                </card>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6 order-md-2">
                        <img src="img/theme/promo-1.png" class="img-fluid floating">
                    </div>
                    <div class="col-md-6 order-md-1">
                        <div class="pr-md-5">
                            <icon name="ni ni-settings-gear-65" class="mb-5" size="lg" type="success" shadow
                                  rounded></icon>
                            <h3>服务器状态与运营</h3>
                            <p>我们自2018年运营至今，走了很多的弯路，吸取教训，让服务器的氛围排在前位。</p>
                            <ul class="list-unstyled mt-5">
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-cloud-upload-96"></badge>
                                        <h6 class="mb-0">每天自动全盘备份服务器</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-ui-04"></badge>
                                        <h6 class="mb-0">优秀的插件系统，方便大家</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-settings"></badge>
                                        <h6 class="mb-0">及时周到的维护</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-world-2"></badge>
                                        <h6 class="mb-0">高配置服务器与稳定的网络</h6>
                                    </div>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section bg-secondary">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6">
                        <div class="card bg-default shadow border-0">
                            <img v-lazy="'img/theme/img-1.jpg'" class="card-img-top">
                            <blockquote class="card-blockquote">
                                <svg preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 583 95"
                                     class="svg-bg">
                                    <polygon points="0,52 583,95 0,95" class="fill-default"></polygon>
                                    <polygon points="0,42 583,95 683,0 0,95" opacity=".2" class="fill-default"></polygon>
                                </svg>
                                <h4 class="display-3 font-weight-bold text-white">寄语</h4>
                                <p class="lead text-italic text-white">服务器运营至今我们见过很多人也碰过很多事，我也发现了自己很多问题，我们会改正也会对群内、服务器玩家一个折中的高效的处理方式，让事情尽量变的公平，也希望玩家能主动与服务器管理交流，让事情的真相并不埋在海底。</p>
                            </blockquote>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="pl-md-5">
                            <icon name="ni ni-settings" class="mb-5" size="lg" type="warning" shadow rounded></icon>
                            <h3>服务器历史线</h3>
                            <p class="lead">我们在2018年中旬创立至今</p>
                            <p>2019初将服务器一周目的基础上增加了新版本的子服(子服命名为VLssu服)</p>
                            <p>2019中旬将一周目正式落幕，并将子服VLssu服更改为主服</p>
                            <p>2019-9-18创建VLssu公益服群并更名至VLssu公益服</p>
                            <p>2019-12月第二周目正式落幕并重新规划开启三周目，但时间不长没有注重备份与服务器维护被黑，所有数据全没，被迫改为过度周目并重新开启三周目</p>
                            <p>2020年服务器逐步推向群组服，并将服务器多元化</p>
                            <p>2021年服务器渐渐稳定，所有环境、网站、数据库实时/定时备份，让服务器数据不再丢失、担惊受怕。</p>
                            <a href="https://jq.qq.com/?_wv=1027&k=5mq4JvN" class="font-weight-bold text-warning mt-5">欢迎加入我们的QQ群</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg">
            <div class="container">
                <div class="row justify-content-center text-center mb-lg">
                    <div class="col-lg-8">
                        <h2 class="display-3">我们的团队</h2>
                        <p class="lead text-muted">对于服务器我们始终保持积极、乐观、热情的态度，我们很荣幸遇见你们。</p>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-1-800x800.jpg'"
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">飒爽师叔</span>
                                    <small class="h6 text-muted">服务器、网站等总管理</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="https://space.bilibili.com/22219285" type="warning" icon="fa fa-address-card" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="mailto:vlssu@vlssu.com" type="warning" icon="fa fa-envelope" rounded
                                                 icon-only></base-button>
                                    <base-button tag="a" href="https://blog.vlssu.com" type="warning" icon="fa fa-external-link" rounded
                                                 icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-2-800x800.jpg'"
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">冰心</span>
                                    <small class="h6 text-muted">空岛服管理</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="https://space.bilibili.com/106446416" type="warning" icon="fa fa-address-card" rounded
                                                 icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-3-800x800.jpg'"
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">Im_Jean</span>
                                    <small class="h6 text-muted">吉祥物、服务器创始人</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="https://space.bilibili.com/26658005" type="warning" icon="fa fa-address-card" rounded
                                                 icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-4-800x800.jpg'"
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">葵</span>
                                    <small class="h6 text-muted">服务器管理</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="https://space.bilibili.com/97475627" type="warning" icon="fa fa-address-card" rounded
                                                 icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-5-800x800.jpg'"
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">能力</span>
                                    <small class="h6 text-muted">空岛、模组服管理</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="https://space.bilibili.com/22935060" type="warning" icon="fa fa-address-card" rounded
                                                 icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 col-lg-3 mb-5 mb-lg-0">
                        <div class="px-4">
                            <img v-lazy="'img/theme/team-6-800x800.jpg'"
                                 class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                 style="width: 200px;">
                            <div class="pt-4 text-center">
                                <h5 class="title">
                                    <span class="d-block mb-1">CN_Tong</span>
                                    <small class="h6 text-muted">吉祥物</small>
                                </h5>
                                <div class="mt-3">
                                    <base-button tag="a" href="https://space.bilibili.com/399932543" type="warning" icon="fa fa-address-card" rounded
                                                 icon-only></base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!--
        <section class="section section-lg pt-0">
            <div class="container">
                <card gradient="warning"
                      no-body
                      shadow-size="lg"
                      class="border-0">
                    <div class="p-5">
                        <div class="row align-items-center">
                            <div class="col-lg-8">
                                <h3 class="text-white">欢迎您来到我们服务器</h3>
                                <p class="lead text-white mt-3">如果有什么建议或者想法可以在论坛中跟我们讲出，可以加入我们的QQ群，但论坛不符合国人来使用，所以更多我们在QQ群中讲出或收集建议，如果说你给我们提了建议，但是我们都没有回应你，那你可以发邮件来提醒我</p>
                            </div>
                            <div class="col-lg-3 ml-lg-auto">
                                <base-button tag="a" href="https://jq.qq.com/?_wv=1027&k=5mq4JvN"
                                             type="white" block size="lg">
                                    加入我们的QQ群
                                </base-button>
                            </div>
                        </div>
                    </div>
                </card>
            </div>
        </section>
        -->

    </div>
</template>

<script>
export default {
  name: "home",
  components: {}
};
</script>
