<template>
    <ui-main>
        <template v-slot:header>
            <van-nav-bar :title="$route.path.replace('/demo-','')" left-arrow @click-left="$router.replace('/demo')"/>
        </template>

        <ui-card>
            <template v-slot:title>
                <div class="flex col-center">
                    <ui-img src="https://p3.pstatp.com/thumb/249c000b0a4ab52ab70a.jpg" class="mr5"  size="30px" circle></ui-img>
                    <span>标题 slot=title</span>
                </div>
            </template>
            <div class="pre-line">
                边境口岸竖立着不少巨型广告牌，提醒着入境者：“你已进入世界上最大的民主国家。”

                这是摄影师 Tim Smith 第一次踏足印度。在此之前，他曾无数次被提醒：“这是一个神奇的国度。”

                旅行期间，他遇到过不少本地人，一边举起手机一边嚷着“photo，photo”，示意他和他们合影。

                在接下来的几天，Tim Smith 决定密切追踪这批狂热的自拍爱好者。
            </div>
        </ui-card>
    </ui-main>
</template>