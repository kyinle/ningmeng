微信公众号 柠檬玩机交流

微信公众号：柠檬玩机交流
柠檬富豪小镇
下载地址：
https://hyskgame.com/apps/fuhaoxiaozhen/wxshare/index.html?createAt=1619750062&senderUserId=152420&senderInviteCode=HG7X&entryPointData=eyJzZW5kZXJVc2VySWQiOiIxNTI0MjAifQ

TG电报群: https://t.me/ningmeng666
微信公众号：柠檬玩机交流
#圈X

[rewrite_local]
#柠檬富豪小镇
https://sunnytown.hyskgame.com/api/messages\SaccessToken=\w+&msgtype=system_getGpvGameOptions url script-request-body http://nm999.cn/fhxz.js
[MITM]
hostname = sunnytown.hyskgame.com
#loon
https://sunnytown.hyskgame.com/api/messages\SaccessToken=\w+&msgtype=system_getGpvGameOptions url script-request-body http://nm999.cn/fhxz.js, requires-body=true, timeout=10, tag=柠檬富豪小镇
#surge
柠檬富豪小镇 = type=https://sunnytown.hyskgame.com/api/messages\SaccessToken=\w+&msgtype=system_getGpvGameOptions,requires-body=1,max-size=0,script-path=http://nm999.cn/fhxz.js,script-update-interval=0


[task_local]
#柠檬富豪小镇
*/10 * * * * http://nm999.cn/fhxz.js, tag=柠檬富豪小镇, enabled=true
