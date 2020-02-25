### 仿哔哩哔哩的React Native项目 暂时实现了视频，直播播放等功能，

npm i     

react-native link

react-native run-android



```
src 目录结构
├─ assets
│    ├─ icons //字体图标
│    │    ├─ font_bilibili
│    │    ├─ mybilibil_font
│    │    └─ myiconfont.ttf
│    └─ images //所需图片
│           ├─ QR.png
│           ├─ acfun.png
│           ├─ back.png
│           ├─ back_live.png
│           ├─ bangumi_home_login_guide.png
│           ├─ bili_default_avatar.png
│           ├─ billiveperson.png
│           ├─ black.jpg
│           ├─ dots.png
│           ├─ dynamic_login_guide.png
│           ├─ fengmian1.jpg
│           ├─ fengmian2.jpg
│           ├─ fengmian3.jpg
│           ├─ fullscreen-exit.png
│           ├─ fullscreen.png
│           ├─ head_icon.jpg
│           ├─ horline.png
│           ├─ ic_empty.png
│           ├─ ic_loading.png
│           ├─ ic_loading_error.png
│           ├─ ic_null.png
│           ├─ ic_player_coin.png
│           ├─ ic_player_danmaku_input_options_rl_disabled.png
│           ├─ ic_tv_play.png
│           ├─ ic_tv_play_large.png
│           ├─ icon.png
│           ├─ icon_bilibili.png
│           ├─ icon_empty.png
│           ├─ img_tips_error_load_error.png
│           ├─ jianbian.png
│           ├─ liveNext.png
│           ├─ live_background.png
│           ├─ live_banner1.jpg
│           ├─ live_banner2.png
│           ├─ live_banner3.jpg
│           ├─ livego.png
│           ├─ login_logo_account.png
│           ├─ login_logo_password.png
│           ├─ me_tv_sign_in.png
│           ├─ me_tv_sign_out.png
│           ├─ paihang.png
│           ├─ partitions.png
│           ├─ pause.png
│           ├─ play.png
│           ├─ splashpage.jpg
│           ├─ timg.gif
│           ├─ volume-off-outline.png
│           ├─ volume-up-outline.png
│           └─ 小电视.png
├─ components //部分组件
│    ├─ AppDraw
│    │    └─ land.js
│    ├─ BanMore.js
│    ├─ Bangumi
│    │    ├─ BanItem.js
│    │    └─ BmSwiper.js
│    ├─ ListItemUI.js
│    ├─ Live
│    │    └─ LiveItemUI.js
│    ├─ MemberBuy
│    │    ├─ GoodList.js
│    │    ├─ Tabs.js
│    │    ├─ TabsList.js
│    │    ├─ ThreeList.js
│    │    ├─ Top.js
│    │    └─ UnGoodList.js
│    └─ Move
│           └─ MoveItem.js
├─ pages //主页面
│    ├─ Classify.js
│    ├─ HomePage.js
│    ├─ MemberBuy.js
│    ├─ Search.js
│    ├─ home_sub_pages
│    │    ├─ Bangumi.js
│    │    ├─ Hot.js
│    │    ├─ Live.js
│    │    ├─ Move.js
│    │    ├─ Recommended.js
│    │    ├─ SeventyYears.js
│    │    └─ home_live
│    ├─ search_sub_pages
│    │    └─ SearchResult.js
│    ├─ vidoe_player
│    │    ├─ VideoComment.js
│    │    ├─ VideoPage.js
│    │    ├─ VideoPlayer.js
│    │    └─ ViderDetilInfo.js
│    └─ webView
│           └─ webView.js
├─ store
│    ├─ actionCreaters.js
│    ├─ actionTypes.js
│    ├─ index.js
│    └─ reducer.js
└─ utils //工具类
       └─ utils.js
//所需插件
	    "@react-native-community/viewpager": "^3.3.0",
        "moment": "^2.24.0",
        "native-base": "^2.13.8",
        "react": "16.9.0",
        "react-native": "0.61.5",
        "react-native-md5": "^1.0.0",
        "react-native-modal-dropdown": "^0.7.0",
        "react-native-orientation": "^3.1.3",
        "react-native-router-flux": "^4.0.6",
        "react-native-scrollable-tab-view": "^1.0.0",
        "react-native-shadow-cards": "^1.0.2",
        "react-native-splash-screen": "^3.2.0",
        "react-native-svg": "^11.0.1",
        "react-native-swiper": "^1.6.0-nightly.5",
        "react-native-tab-navigator": "^0.3.4",
        "react-native-vector-icons": "^6.6.0",
        "react-native-video": "^5.0.2",
        "react-native-webview": "^8.0.6",
        "react-redux": "^7.1.3",
        "redux": "^4.0.5",
        "text-encoding": "^0.7.0"
```