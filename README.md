#Cookie获取订阅
#适用于QX1.0.10
#Cookie获取成功后在重写里禁用掉本订阅
#Cookie失效时在重写里启用本订阅

#订阅地址(https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Get_Cookie_Remote.conf)

hostname = mobile01.91quzou.com, mk.immomo.com, huiyuan.163.com, geekhub.com, cxdng.cpic.com.cn, h5.youzan.com, api.infzm.com, api.xiaoheihe.cn, exp.angelalign.com, ngabbs.com, api.umer.com.cn, app*.jegotrip.com.cn, task.jegotrip.com.cn, my.ruanmei.com, www.mydigit.cn, wx-mini.pagoda.com.cn, m.weibo.cn, apapia-history.manmanbuy.com, weather-data.apple.com, mall.oclean.com, api.cashtoutiao.com, user-api-prd-mx.wandafilm.com, h5.bianlifeng.com, teacherapi.zmlearn.com, clientaccess.10086.cn, maicai.api.ddxq.mobi, vip.heytea.com, webapi.qmai.cn, proapi.115.com, proxy.vac.qq.com, *.xmcimg.com, as.xiaojukeji.com, note.youdao.com, ios.baertt.com, api.m.jd.com, music.163.com, c.tieba.baidu.com, weibo.com, iface?.iqiyi.com, *.smzdm.com, *.v2ex.com, www.52pojie.cn, *.bilibili.com, *.feng.com, *.video.qq.com, *.acfun.cn, *.rrys2019.com, mobwsa.ximalaya.com, *.rr.tv, www.flyertea.com, wapside.189.cn, sf-integral-sign-in.weixinjia.net, h5.ele.me, *.you.163.com, apk.tw, api.dongqiudi.com, *.m.163.com, user.qunar.com, yuba.douyu.com, ios.zmzapi.com, *.y.qq.com, *.csdn.net, m.ctrip.com, m.gdoil.cn, credits.bz.mgtv.com, api-takumi.mihoyo.com, act.10010.com, e.189.cn,  www.maomicd.com, wx.10086.cn, mtrace.qq.com, www.lltxt.com, weclub.ccc.cmbchina.com, promotion.waimai.meituan.com, i.meituan.com, daojia.jd.com, api-hdcj.9w9.com, api.everphoto.cn, group.baicizhan.com, maicai.api.ddxq.mobi, pm.m.fenqile.com, ms.jr.jd.com, nebula.kuaishou.com, api.dushu.io, node.kg.qq.com, app.nio.com, wxprdapplet.gac-nio.com, activity-1.m.duiba.com.cn, m.client.10010.com, m-bean.kaola.com, 110.43.90.61, zt.wps.cn, xiaoshuo.qm989.com, passport.suning.com, luckman.suning.com, sign.suning.com, gameapi.suning.com, m.ximalaya.com, iphone.myzaker.com, draw.jdfcloud.com, sapi.beingfine.cn, icbc1.wlphp.com, wx.17u.cn, frodo.douban.com, mcs-mimp-web.sf-express.com, gameapi.hellobike.com, mwegame.qq.com, api.1sapp.com, tieba.baidu.com, m.ximalaya.com, app.jf.360.cn, api.weibo.cn, pay.sc.weibo.com, api.inews.qq.com, newsapi.sina.cn, *.youth.cn, apiwz.midukanshu.com, www.duokan.com, appv8.qukantianxia.com, appv7.qukantx.com, xwsh.javamall.cn

# NobyDa

# 京东签到获取cookie
https:\/\/api\.m\.jd\.com\/client\.action.*functionId=signBean url script-request-header https://raw.githubusercontent.com/NobyDa/Script/master/JD-DailyBonus/JD_DailyBonus.js

# 爱奇艺获取cookie
^https:\/\/iface\d\.iqiyi\.com\/.+?psp_cki= url script-request-header https://raw.githubusercontent.com/NobyDa/Script/master/iQIYI-DailyBonus/iQIYI.js

# 贴吧签到获取cookie
https?:\/\/(c\.tieba\.baidu\.com|180\.97\.\d+\.\d+)\/c\/s\/login url script-request-header https://raw.githubusercontent.com/NobyDa/Script/master/BDTieBa-DailyBonus/TieBa.js

# 52破解论坛获取Cookie
https:\/\/www\.52pojie\.cn\/home\.php\?mod=space url script-request-header https://raw.githubusercontent.com/NobyDa/Script/master/52pojie-DailyBonus/52pojie.js

# 哔哩哔哩漫画获取cookie
^https:\/\/passport\.biligame\.com\/api\/login\/sso.+?version%22%3A%22(3|4|5) url script-request-header https://raw.githubusercontent.com/NobyDa/Script/master/Bilibili-DailyBonus/Manga.js

# 百度贴吧
https?:\/\/c\.tieba\.baidu\.com\/c\/s\/login url script-request-header https://raw.githubusercontent.com/NobyDa/Script/master/BDTieBa-DailyBonus/TieBa.js

# Chavyleung

# 百度签到
^https?:\/\/tieba\.baidu\.com\/?.? url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/tieba/tieba.cookie.js

# 网易云签到获取cookie(by chavyleung)
^https:\/\/music.163.com\/weapi\/user\/level url script-request-body https://raw.githubusercontent.com/chavyleung/scripts/master/neteasemusic/quanx/neteasemusic.cookie.js

# 什么值得买获取cookie(by chavyleung)
^https:\/\/www\.smzdm\.com\/?.? url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/smzdm/quanx/smzdm.cookie.js

# V2ex获取cookie
^https:\/\/www\.v2ex\.com\/mission\/daily url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/v2ex/quanx/v2ex.cookie.js

# Bilibili直播获取Cookie
^https:\/\/(www|live)\.bilibili\.com\/?.? url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/bilibili/bilibili.cookie.js

# 威锋论坛获取cookie
^https:\/\/(www\.)?feng\.com\/?.? url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/feng/feng.cookie.js

# 腾讯视频获取cookie
^https:\/\/access.video.qq.com\/user\/auth_refresh url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/videoqq/videoqq.cookie.js
^https?:\/\/v.qq.com\/x\/bu\/mobile_checkin url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/videoqq/videoqq.cookie.js

# Acfun视频cookie获取
^https:\/\/api\-new\.app\.acfun\.cn\/rest\/app\/user\/personalInfo url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/acfun/acfun.cookie.js

# 人人字幕组获取cookie
^https?:\/\/(www\.)?rrys2020\.com\/?.? url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/zimuzu/zimuzu.cookie.js
^http:\/\/ios.zmzapi.com\/index.php.*a=(mobile_)?login url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/zimuzu/zimuzu.cookie.js

# 喜马拉雅获取cookie
^https?:\/\/.*\/mobile\-user\/homePage\/.* url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/ximalaya/ximalaya.cookie.js

# 人人视频获取cookie
^https:\/\/api\.rr\.tv\/user\/profile url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/rrtv/rrtv.cookie.js

# 飞客茶馆获取cookie
^https:\/\/www\.flyertea\.com\/source\/plugin\/mobile\/mobile\.php\?module=getdata&.* url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/flyertea/flyertea.cookie.js

# 顺丰速运
^https:\/\/sf-integral-sign-in.weixinjia.net\/app\/index url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/sfexpress/sfexpress.cookie.js
^https:\/\/mcs-mimp-web.sf-express.com\/mcs-mimp\/share\/(.*?)Redirect url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/sfexpress/sfexpress.cookie.js


# 懂球帝获取cookie
^https:\/\/api\.dongqiudi\.com\/v2\/user\/is_login url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/dongqiudi/dongqiudi.cookie.js

# 网易严选获取cookie
^https:\/\/m\.you\.163\.com\/xhr\/points\/index\.json url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/yanxuan/yanxuan.cookie.js

# APK.TW获取cookie
^https:\/\/apk\.tw\/?.? url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/apktw/apktw.cookie.js

# 去哪儿 获取cookie
^https:\/\/user.qunar.com\/webapi\/member\/signIndexV2.htm url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/qunar/qunar.cookie.js

# CSDN获取cookie
^^https:\/\/passport.csdn.net\/v2\/api\/app\/login\/checkAndRefreshToken url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/csdn/csdn.cookie.js
^https:\/\/gw.csdn.net\/mini-app\/v2\/lucky_draw\/login\/sign_in\? url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/csdn/csdn.cookie.js

# 芒果tv 获取cookie
^https:\/\/credits.bz.mgtv.com\/user\/creditsTake url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/mgtv/mgtv.cookie.js

#加油广东 获取cookie
^https:\/\/m.gdoil.cn\/webapi\/usersign\/addusersign url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/gdoil/gdoil.cookie.js

# 猫咪音乐 获取cookie
https:\/\/www.maomicd.com\/plugin.php\?id=k_misign:sign&operation=qiandao url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/maomicd/maomicd.cookie.js

# 中国移动
^http:\/\/wx.10086.cn\/website\/taskCenter\/index\? url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/10086/10086.cookie.js
^http:\/\/wx.10086.cn\/website\/taskCenter\/sign\? url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/10086/10086.cookie.js

# 米游社 获取cookie
^https:\/\/api-takumi.mihoyo.com\/apihub\/api\/getGameList url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/mihoyo/mihoyo.cookie.js

# 中国联通 获取cookie
^https:\/\/act.10010.com\/SigninApp\/signin\/querySigninActivity.htm url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/10010/10010.cookie.js
^https:\/\/act.10010.com\/SigninApp(.*?)\/signin\/daySign url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/10010/10010.cookie.js
^https:\/\/m.client.10010.com\/dailylottery\/static\/(textdl\/userLogin|active\/findActivityInfo) url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/10010/10010.cookie.js

# 美团外卖 获取cookie
^https:\/\/promotion.waimai.meituan.com\/playcenter\/signIn\/entry url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/wmmeituan/wmmeituan.cookie.js
^https:\/\/promotion.waimai.meituan.com\/playcenter\/signIn\/doaction url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/wmmeituan/wmmeituan.cookie.js

# 网易新闻获取cookie
^https:\/\/(.*?)c\.m\.163\.com\/uc\/api\/sign\/v3\/commit url script-request-body https://raw.githubusercontent.com/chavyleung/scripts/master/neteasenews/neteasenews.cookie.js

# QQ音乐获取cookie(需要TF195+)
^https:\/\/u.y.qq.com\/cgi\-bin\/musicu.fcg url script-request-body https://raw.githubusercontent.com/chavyleung/scripts/master/qqmusic/qqmusic.cookie.js
^https:\/\/u.y.qq.com\/cgi\-bin\/musicu.fcg url script-response-body https://raw.githubusercontent.com/chavyleung/scripts/master/qqmusic/qqmusic.cookie.js

# 美团
^https:\/\/i.meituan.com\/evolve\/signin\/signpost\/ url script-request-body https://raw.githubusercontent.com/chavyleung/scripts/master/meituan/meituan.cookie.js

# 时光相册
^https:\/\/api.everphoto.cn\/users\/self\/checkin\/v2 url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/everphoto/everphoto.cookie.js

# 百词斩
^https://group\.baicizhan\.com/group/rewards? url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/bcz/bcz.cookie.js

# 叮咚买菜
^https:\/\/maicai.api.ddxq.mobi\/point\/home url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/mcdd/mcdd.cookie.js

# 分期乐
^https://pm\.m\.fenqile\.com/route0014/star/sign/sign.json url script-request-body https://raw.githubusercontent.com/chavyleung/scripts/master/fenqile/fenqile.cookie.js
^https:\/\/pm\.m\.fenqile\.com/route0014\/app\/tab\/privilege\/convertTaskReward.json url script-request-body https://raw.githubusercontent.com/chavyleung/scripts/master/fenqile/fenqile.cookie.js

# 樊登读书
^https://api\.dushu\.io/CheckIn url script-request-body https://raw.githubusercontent.com/chavyleung/scripts/master/fandeng/fandeng.cookie.js

# 全民K歌
^https://node\.kg\.qq\.com/webapp/proxy? url script-request-body https://raw.githubusercontent.com/chavyleung/scripts/master/qmkg/qmkg.cookie.js

# 蔚来
^https:\/\/app\.nio\.com\/api\/1\/app\/daily_checkin url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/nio/nio.cookie.js

# 合创
^https:\/\/wxprdapplet\.gac-nio\.com\/community\/userSignIn\/simpleAuth\/front\/.*\/sign$ url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/hycan/hycan.cookie.js

# 京东到家
;^https:\/\/daojia.jd.com/client(.*?)functionId=signin(.*?)userSigninNew url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/jddj/jddj.cookie.js

# 海底捞
^https:\/\/activity-1\.m\.duiba\.com\.cn\/signactivity\/doSign$ url script-request-body https://raw.githubusercontent.com/chavyleung/scripts/master/haidilao/hdl.js

# 网易考拉
^https:\/\/m-bean\.kaola\.com/m/point/sign\.html url script-request-body https://raw.githubusercontent.com/chavyleung/scripts/master/wykl/wykl.cookie.js

# WPS
^https:\/\/zt.wps.cn\/2018\/docer_check_in\/api\/act_list url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/wps/wps.cookie.js

# 七猫小说
^https:\/\/xiaoshuo\.qm989\.com url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/qimao/qmnovel.js

# 苏宁易购
^https:\/\/passport.suning.com\/ids\/login$ url script-request-body https://raw.githubusercontent.com/chavyleung/scripts/master/suning/suning.cookie.js
^https:\/\/luckman.suning.com\/luck-web\/sign\/api\/clock_sign.do url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/suning/suning.cookie.js
^https:\/\/sign.suning.com\/sign-web\/m\/promotion\/sign\/doSign.do url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/suning/suning.cookie.js
^https:\/\/gameapi.suning.com\/sngame-web\/(api\/signin\/private\/customerSignOperation.do|gateway\/api\/queryPrize.do) url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/suning/suning.cookie.js

# Zaker
^https:\/\/iphone\.myzaker\.com\/zaker\/sign_in\/\/api\/sign_in\.php url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/zaker/zaker.js

# 不背单词
^https:\/\/sapi\.beingfine\.cn\/v3\/bb\/reward\/by-sign-in url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/bubei/bubei.js

# 豆瓣时间
^https:\/\/frodo\.douban\.com\/api\/v2\/niffler\/check_in\/status url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/dbsj/dbsj.cookie.js

# 哈啰出行
^https:\/\/gameapi\.hellobike\.com\/api url script-request-body https://raw.githubusercontent.com/chavyleung/scripts/master/hellobike/hellobike.js

# 掌上飞车
^https:\/\/mwegame\.qq\.com\/ams\/sign\/doSign\/month url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/zsfc/zsfc.js

# 趣头条
^https:\/\/api\.1sapp\.com\/sign\/info? url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/qtt/qtt.cookie.js
^https:\/\/api\.1sapp\.com\/content\/readV2? url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/qtt/qtt.cookie.js
^https:\/\/api\.1sapp\.com\/x\/feed\/getReward? url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/qtt/qtt.cookie.js

# 米读
^https:\/\/apiwz\.midukanshu\.com url script-request-body https://raw.githubusercontent.com/chavyleung/scripts/master/midu/midu.cookie.js

# 多看
^https:\/\/www\.duokan\.com\/checkin\/v0\/status url script-request-body https://raw.githubusercontent.com/chavyleung/scripts/master/duokan/duokan.cookie.js

# 京东618
^https:\/\/api.m.jd.com\/client.action\?functionId=cakebaker_getHomeData url script-request-body https://raw.githubusercontent.com/chavyleung/scripts/master/jd/jd.618.cookie.js

# 有道云笔记
^https:\/\/note.youdao.com\/yws\/mapi\/user\?method=checkin url script-request-body https://raw.githubusercontent.com/chavyleung/scripts/master/noteyoudao/noteyoudao.cookie.js

# 中国移动查话费
^https:\/\/clientaccess.10086.cn\/biz-orange\/LN\/uamrandcodelogin\/autoLogin url script-request-body https://raw.githubusercontent.com/chavyleung/scripts/master/10086/10086.fee.cookie.js
^https:\/\/clientaccess.10086.cn\/biz-orange\/BN\/realFeeQuery\/getRealFee url script-request-body https://raw.githubusercontent.com/chavyleung/scripts/master/10086/10086.fee.cookie.js

# > 万达电影
^https:\/\/user-api-prd-mx\.wandafilm\.com url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/wanda/wanda.cookie.js

# > 百果园
^https:\/\/wx-mini.pagoda.com.cn\/api\/v1\/wxmini\/signIn\/customer url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/pagoda/pagoda.cookie.js

# > 南方周末
^http:\/\/api\.infzm\.com\/mobile\/pumpkin_task\/complete? url script-request-header https://raw.githubusercontent.com/chavyleung/scripts/master/nfzm/nfzm.cookie.js

#其他

# 饿了么 (By @syzzzf)
^https:\/\/h5\.ele\.me\/restapi\/eus\/v\d\/current_user$ url script-request-header https://raw.githubusercontent.com/songyangzz/QuantumultX/master/elem/elemGetCookies.js

#斗鱼鱼吧 (By @yyfyyf123)
https://yuba.douyu.com/wbapi/web/group/myFollow url script-request-header https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Task/yubaSign.js

# 携程旅行 (By @barrymchen)
https:\/\/m\.ctrip\.com\/restapi\/soa2\/14946\/json\/userBaseInfo url script-request-header https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Task/ctrip_cookie.js
# 小程序 复制到本地
;^https:\/\/m\.ctrip\.com\/restapi\/soa2\/16575\/getUserInfo url script-request-body https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Task/ct_cookie.js

# 京东成长分 (By @barrymchen)
^https:\/\/ms\.jr\.jd\.com\/gw\/generic\/bt\/h5\/m\/queryUserSignFlow url script-request-header https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Task/jdczfcookie.js

# 工银e生活 (By @barrymchen)
^https:\/\/icbc1\.wlphp\.com:8444\/js\/api\/index\/signIn url script-request-body https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Task/icbc_cookie.js

# 微信小程序-同程艺龙 (By @barrymchen)
^https:\/\/wx\.17u\.cn\/wcsign\/sign\/GetSignInfo url script-request-body https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Task/tongc_cookie.js

# 京东到家 (By @barrymchen, @GideonSenku & @Macsuny)
https:\/\/daojia\.jd\.com\/client\?_jdrandom=\d{13}&functionId=%2Fsignin url script-request-header https://raw.githubusercontent.com/Sunert/Scripts/master/Task/jddj.js

# 快手极速版 (By @Macsuny)
https:\/\/nebula\.kuaishou\.com\/rest\/n\/nebula\/activity\/earn\/overview url script-request-header https://raw.githubusercontent.com/Sunert/Scripts/master/Task/kuaishou.js

# 微信小程序-来客有礼 (By @Macsuny)
https:\/\/draw\.jdfcloud\.com\/\/api\/bean\/square\/silverBean\/task\/get\? url script-request-header https://raw.githubusercontent.com/Sunert/Scripts/master/Task/lkyl.js

# 电视家 (By @Macsuny)
http:\/\/api\.gaoqingdianshi\.com\/api\/v\d\/sign\/signin url script-request-header https://raw.githubusercontent.com/Sunert/Scripts/master/Task/dianshijia.js

http:\/\/api\.gaoqingdianshi\.com\/api\/v2\/cash\/withdrawal\?code= url script-request-header https://raw.githubusercontent.com/Sunert/Scripts/master/Task/dianshijia.js

# 中国电信套餐 (By @uchvk & @Macsuny)
^https?:\/\/e\.189\.cn\/store\/user\/package_detail\.do url script-request-header https://raw.githubusercontent.com/Sunert/Scripts/master/Task/telecomInfinity.js

# > 微博 (By @Macsuny)
https:\/\/api\.weibo\.cn\/\d\/video\/machine\?gsid url script-request-header https://raw.githubusercontent.com/Sunert/Scripts/master/Task/weibo.js
# 钱包
https:\/\/pay\.sc\.weibo\.com\/aj\/mobile\/home\/welfare\/signin\/do\? url script-request-header https://raw.githubusercontent.com/Sunert/Scripts/master/Task/weibo.js

# 腾讯新闻(By 红鲤鱼与绿鲤鱼与驴 & @Macsuny)
https:\/\/api\.inews\.qq\.com\/event\/v1\/user\/event\/report\? url script-request-body https://raw.githubusercontent.com/Sunert/Scripts/master/Task/txnews.js

# 新浪新闻(By @Macsuny)
https:\/\/newsapi\.sina\.cn\/\?resource=hbpage&newsId=HB-1-sina_gold_center url script-request-header https://raw.githubusercontent.com/Sunert/Scripts/master/Task/sinanews.js
https:\/\/newsapi\.sina\.cn\/\?resource=userpoint\/signIn url script-request-header https://raw.githubusercontent.com/Sunert/Scripts/master/Task/sinanews.js

# > 中青看点极速版 (By @Macsuny)
https:\/\/\w+\.youth\.cn\/TaskCenter\/(sign|getSign) url script-request-header https://raw.githubusercontent.com/Sunert/Scripts/master/Task/youth.js

https?:\/\/ios\.baertt\.com\/v5\/article\/complete url script-request-body https://raw.githubusercontent.com/Sunert/Scripts/master/Task/youth.js

https:\/\/ios\.baertt\.com\/v5\/article\/red_packet url script-request-body https://raw.githubusercontent.com/Sunert/Scripts/master/Task/youth.js

https:\/\/ios\.baertt\.com\/v5\/user\/app_stay\.json url script-request-body https://raw.githubusercontent.com/Sunert/Scripts/master/Task/youth.js

# 数码之家 (By @Macsuny)
id=k_misign:sign&operation=qiandao&format=text url script-request-header https://raw.githubusercontent.com/Sunert/Scripts/master/Task/mydigit.js

# 楼兰小说论坛 (By @iNotification)
^https:\/\/www\.lltxt\.com/hack\.php\?H_name=qiandao&action=qiandao url script-request-header https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Task/loulancheck.js

# 招行信用卡公众号 (By @iNotification)
https://weclub\.ccc\.cmbchina.com/SCRMCustomActivityFront/checkin/request/get-home-data\.json\?activityCode=checkin url script-request-header https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Task/cmbchina.js

# 微信小程序 活动抽奖 (By @makexp & @zZPiglet)
^https:\/\/api-hdcj\.9w9\.com\/v\d\/sign url script-request-header https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Task/WeChatLottery_new.js

# 滴滴出行 (By @zZPiglet)
^https:\/\/as\.xiaojukeji\.com\/ep\/as\/toggles\? url script-request-header https://raw.githubusercontent.com/zZPiglet/Task/master/DiDi/DiDi.js

# 115 (By @zZPiglet)
^https?:\/\/proapi\.115\.com\/ios\/user\/takespc\? url script-request-header https://raw.githubusercontent.com/zZPiglet/Task/master/115/115.js

# 奈雪 (By @zZPiglet)
^https:\/\/webapi\.qmai\.cn\/web\/cy\/v\d\/store\/template-scene url script-request-header https://raw.githubusercontent.com/zZPiglet/Task/master/Naixue/Naixue.js

# 掌门好老师 (By @zZPiglet)
^https:\/\/teacherapi\.zmlearn\.com\/v1\/teacherApp\/app\/points\/taskCenter url script-request-header https://raw.githubusercontent.com/zZPiglet/Task/master/ZMTeacher/ZMTeacher.js

# 便利蜂 (By @zZPiglet)
^https:\/\/h5\.bianlifeng\.com\/meepo\/taskCenter\/home\/v\d url script-request-header https://raw.githubusercontent.com/zZPiglet/Task/master/Blibee/Blibee.js

# 欧可林 (By @zZPiglet)
^https:\/\/mall\.oclean\.com\/API\/VshopProcess\.ashx$ url script-request-header https://raw.githubusercontent.com/zZPiglet/Task/master/Oclean/Oclean.js

# 微信小程序 - 欧可林商城 (By @zZPiglet)
^https:\/\/mall\.oclean\.com\/API\/VshopProcess\.ashx\?action=TaskHome&clientType=5&client=5&openId= url script-request-header https://raw.githubusercontent.com/zZPiglet/Task/master/Oclean/Oclean_mini.js

# 微博通知 (By @zZPiglet)
^https:\/\/m\.weibo\.cn\/feed\/ url script-request-header https://raw.githubusercontent.com/zZPiglet/Task/master/Weibo/Weibo.js

# 小黑盒 (By @zZPiglet)
^https:\/\/api\.xiaoheihe\.cn\/account\/home_v2\/\? url script-request-header https://raw.githubusercontent.com/zZPiglet/Task/master/heybox/heybox.js

# 豆瓣电影日历 (By @zZPiglet)
^https:\/\/frodo\.douban\.com\/api\/v\d\/calendar\/today url script-request-header https://raw.githubusercontent.com/zZPiglet/Task/master/MovieCalendar/MovieCalendar.js

# 微信喜马拉雅 (By @makexp)
https://m.ximalaya.com/wechat/ url script-request-header https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Task/xmly_wc.js

# 360扫地机 (By @qiaoborui)
^https://app.jf.360.cn/signin/index/index url script-request-header https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Task/360.js

# 微博超话 (By Evilbutcher & toulanboy)
^https?://m?api\.weibo\.c(n|om)\/2\/(cardlist|page\/button) url script-request-header https://raw.githubusercontent.com/toulanboy/scripts/master/weibo/weibotalk.cookie.js

# Funboat  (By Evilbutcher)
https:\/\/h5\.youzan\.com\/wscump\/checkin\/checkin url script-request-header https://raw.githubusercontent.com/evilbutcher/Quantumult_X/master/check_in/funboat/funboat.js
https:\/\/h5\.youzan\.com\/wscuser\/membercenter\/stats url script-request-header https://raw.githubusercontent.com/evilbutcher/Quantumult_X/master/check_in/funboat/funboat.js

# 小木虫论坛(By toulanboy)
^https?:\/\/mapi.xmcimg.com\/bbs\/memcp.php\?action url script-request-header https://raw.githubusercontent.com/toulanboy/scripts/master/muchong/muchong.js

# 京东价格提醒(By toulanboy)
^https:\/\/apapia-history\.manmanbuy\.com\/ChromeWidgetServices\/WidgetServices\.ashx url script-request-body https://raw.githubusercontent.com/toulanboy/scripts/master/jd_price_detect/jd_price_detect.js

# qq会员成长值签到 (By @lowking)
https:\/\/proxy.vac.qq.com\/cgi-bin\/srfentry.fcgi? url script-request-header https://raw.githubusercontent.com/lowking/Scripts/master/QQVip/qqVipCheckIn.js

# 哔哩哔哩番剧监控 (By @lowking)
https?:\/\/app.bilibili.com\/x\/v2\/space\/bangumi url script-request-header https://raw.githubusercontent.com/lowking/Scripts/master/bilibili/bangumiMonitor.js

# 叮咚农场(By iepngs)
https:\/\/maicai\.api\.ddxq\.mobi\/user\/checkLogin url script-request-header https://raw.githubusercontent.com/iepngs/Script/master/dingdong/index.js

# 惠头条签(By 红鲤鱼与绿鲤鱼与驴)
# 作者的邀请码:53150681 nzw9314邀请码: 12773106
#时段签到, 阅读数据, 小视频和视频 4个cookie
https:\/\/api\.cashtoutiao\.com url script-request-body https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Task/htt_cookie.js

# 趣看天下(By 红鲤鱼与绿鲤鱼与驴)
# 作者的邀请码:9656852 nzw9314邀请码:  iepngs邀请码:9848880
https:\/\/(appv8\.qukantianxia|appv7\.qukantx)\.com url script-request-header https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Task/qktx_cookie.js

# 特仑苏(By 红鲤鱼与绿鲤鱼与驴)
# 点击进入“特仑苏向往的生活”小程序授权登录后点击放牧获取ck
https:\/\/xwsh\.javamall\.cn url script-request-header https://raw.githubusercontent.com/nzw9314/QuantumultX/master/Task/tls_cookie.js

#趣走(By 红鲤鱼与绿鲤鱼与驴)
https:\/\/mobile01\.91quzou\.com\/rebate\/qz\/task\/homeTaskView\.do url script-request-header https://raw.githubusercontent.com/wangdelu2020/hongliyu/master/quwalk2.2.js

#陌陌(By 红鲤鱼与绿鲤鱼与驴)
https:\/\/mk\.immomo\.com\/activity\/fastsign\/index\/signIn? url script-request-body https://raw.githubusercontent.com/wangdelu2020/hongliyu/master/momosign.js

# 彩云天气 (By Peng-YM)
https://weather-data.apple.com url script-request-header https://raw.githubusercontent.com/Peng-YM/QuanX/master/Tasks/caiyun.js

# 无忧行 (by @vinewx)
https?:\/\/app.*\.jegotrip\.com\.cn\/.*getUser\? url script-response-body https://ooxx.be/js/jegotrip.js
https?:\/\/task\.jegotrip\.com\.cn\:8080\/app\/tasks\?userid url script-response-body https://ooxx.be/js/jegotrip.js

# 优麦医生 (by @vinewx)
https?:\/\/api\.umer\.com\.cn\/.*getCurrentUmerSign url script-request-header https://ooxx.be/js/umer.js

# 时代天使 (by chouchoui)
^https:\/\/exp.angelalign.com\/api\/v1\/mini_program\/get_plan_list url script-request-header https://raw.githubusercontent.com/chouchoui/QuanX/master/Scripts/angelalign/angelalign.cookie.js

# nga刮墙 (by chouchoui)
^https:\/\/ngabbs.com\/nuke.php\?? url script-request-body https://raw.githubusercontent.com/chouchoui/QuanX/master/Scripts/nga/nga.cookie.js

# 来客有礼宠汪汪强制助力(By lxk0301)
# 从京东APP宠汪汪->领狗粮->邀请好友助力，分享给你小号微信或者微信的文件传输助手。 自己再打开刚才的分享，助力成功后，退出小程序重新进去刚才分享的小程序即可
^https:\/\/draw\.jdfcloud\.com\/\/pet\/enterRoom\?reqSource=weapp&invitePin=.*+(&inviteSource=task_invite&shareSource=\w+&inviteTimeStamp=\d+&openId=\w+)?|^https:\/\/draw\.jdfcloud\.com\/\/pet\/helpFriend\?friendPin url script-request-header https://raw.githubusercontent.com/lxk0301/scripts/master/jd_joy_help.js

# 电信余额提醒 (By id77)
^https?:\/\/e\.189\.cn\/store\/user\/balance_new\.do url script-request-header https://raw.githubusercontent.com/id77/QuantumultX/master/task/10000.cookie.js

# 网易游戏会员 (By id77)
^https:\/\/huiyuan\.163\.com\/jf\-mall\-api\/api\/sign_up\/(lucky|normal) url script-request-header https://raw.githubusercontent.com/id77/QuantumultX/master/task/163GameVip.cookie.js

# Geekhub (By id77)
^https:\/\/geekhub\.com\/checkins\/start url script-request-header https://raw.githubusercontent.com/id77/QuantumultX/master/task/geekhub.cookie.js

# 太好购 (By id77)
^https:\/\/cxdng\.cpic\.com\.cn\/taieshop\/api\/CustomerFansInfo\/GetFansInfo url script-request-header https://raw.githubusercontent.com/id77/QuantumultX/master/task/thg.cookie.js
