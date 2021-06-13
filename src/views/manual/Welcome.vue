<template>
    <div class="profile-page">
        <section class="section-profile-cover section-shaped my-0">
            <div class="shape shape-style-1 bj-3 shape-skew alpha-4">
            </div>
        </section>
        <section class="section section-skew">
            <div class="container">
                <card shadow class="card-profile mt--300" no-body>
                    <div class="px-4">
                        <div class="row justify-content-center">
                            <div class="col-lg-3 order-lg-2">
                                <div class="card-profile-image">
                                    <a href="#">
                                        <img v-lazy="'img/theme/team-1-800x800.jpg'" class="rounded-circle">
                                    </a>
                                </div>
                            </div>
                            <div class="col-lg-4 order-lg-3 text-lg-right align-self-lg-center">
                                <div class="card-profile-actions py-4 mt-lg-0">
                                    <base-button type="info" size="sm" class="mr-4">简洁易懂</base-button>
                                    <base-button type="default" size="sm" class="float-right">模块化</base-button>
                                </div>
                            </div>
                        </div>
                        <div class="text-center mt-5">
                            <h3>欢迎来到
                                <span class="font-weight-light">文档欢迎页</span>
                            </h3>
                            <div class="h6 font-weight-300"><i class="ni location_pin mr-2"></i>此页面由 飒爽师叔 撰写</div>
                            <div class="h6 mt-4"><i class="ni business_briefcase-24 mr-2"></i>提供基本的进服方法与IP</div>
                            <div><i class="ni education_hat mr-2"></i>详细内容请进入相应服文档页</div>
                        </div>
                        <div class="mt-5 py-5 border-top text-center">
                            <div class="row justify-content-center">
                                <div class="col-lg-9">
                                    <p>我们服务器虽不完善，但是！我们会尽力完善他，也希望大家来玩如果说有什么意见或者想法都可以
                                        跟我们提建议，可以直接在留言板中提出，如果可以我们会尽力去实现，也可以来我们的QQ群唠嗑哦~
                                        (有什么不会的也可以来群里提问，但请不要在百度中随便一查就能查到的过来问。。。)</p>
                                </div>
                            </div>
                        </div>
                        <div>
                            <base-alert type="danger">
                                <span class="alert-inner--icon"><i class="fa fa-ban" aria-hidden="true"></i></span>
                                <strong>最后！</strong> 熊孩子你就省省心吧，熊服务器不会有任何损失，只要执行回档你的“努力”就会白费。
                            </base-alert>
                        </div>
                        <tabs fill class="flex-column flex-md-row">
                            <card shadow>
                                <tab-pane>
                                    <span slot="title">
                                        <i class="ni ni-badge"></i>
                                        皮肤站玩家登录方式
                                    </span>
                                    <p class="description">
                                        皮肤站认证IP：<span>jmc.vlssu.com</span></p>
                                </tab-pane>

                                <tab-pane title="正版玩家登录方式">
                                    <span slot="title">
                                        <i class="fa fa-balance-scale"></i>
                                        正版玩家登录方式
                                    </span>
                                    <p class="description">
                                        Cosby sweater eu banh mi, qui irure terry richardson ex
                                        squid. Aliquip placeat salvia cillum iphone. Seitan aliquip quis cardigan
                                        american apparel, butcher voluptate nisi qui.</p>
                                </tab-pane>
                            </card>
                        </tabs>
                        <div class="mt-5 py-5 border-top text-center">
                            <div class="row justify-content-center">
                                <div class="col-lg-9">
                                    <p>An artist of considerable range, Ryan — the name taken by Melbourne-raised, Brooklyn-based Nick Murphy — writes, performs and records all of his own music, giving it a warm, intimate feel with a solid groove structure. An artist of considerable range.</p>
                                    <a href="#">Show more</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </card>
            </div>
        </section>
    </div>
</template>
<script>
import Modal from "@/components/Modal.vue";
import Tabs from "@/components/Tabs/Tabs.vue";
import TabPane from "@/components/Tabs/TabPane.vue";
export default {
  components: {
    Tabs,
    TabPane,
    Modal
  },
  data() {
    return {
      modals: {
        modal1: false,
        modal2: false,
        modal3: false
      }
    };
  }
};
</script>
<style>
</style>
