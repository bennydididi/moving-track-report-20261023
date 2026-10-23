# 关键词与SERP审计

基准日：2026-10-23。量源为所给PXAny/Google Ads查询快照；未重新运行付费扩词查询。API入口：https://api.pxany.com/v1/keyword-volumes 。Google Ads相近变体可能共享量，不能把各行求和当独立人次。

8种语言各300条且行内去重；英文复用于US/UK/CA/AU，合计3300条市场×词。英语仅2条5词，其余英欧词为2–4词；日韩按本地分词检查。格式合规不代表自然搜索习惯全都经过母语验证。软件/CRM/库存/预约、规则/表单/嵌入与消费者词均有覆盖。

420条量为“未找到”而非0，其中日本231、韩国168；脚本没有API报错不代表每词均有返回。moving estimate software四英语市场均未找到；moving estimating software美国返回0，不混写。

超200共53条：明确软件1、消费计算工具26、本地服务/价格25、升降实物1。以下全部重判，不沿用旧标签；本地和消费词只存档、不计入SaaS竞争结论。

18个月窗口：2025-04-23至2026-10-23；先按注册域去重，再按created精确日期判断；age_years仅交叉参考。>=2个新域名为新手友好，1个为有缝隙，0个为老站占优，未返回/年龄缺失保留未找到。域名注册日不等于产品上线日。

|市场|关键词|月搜|意图修正|返回结果|已知注册日/域名|18个月内|12个月内|18个月判定|来源|
|---|---|---:|---|---:|---:|---:|---:|---|---|
|US|moving cost calculator|6600|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|8/8|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=moving%20cost%20calculator&gl=us&hl=en)|
|US|moving estimate calculator|320|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|8/8|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=moving%20estimate%20calculator&gl=us&hl=en)|
|US|moving cost estimator|6600|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|8/8|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=moving%20cost%20estimator&gl=us&hl=en)|
|US|cubic feet calculator|40500|消费者免费计算/预算工具：仅记量，不作SaaS需求|10|7/7|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=cubic%20feet%20calculator&gl=us&hl=en)|
|US|moving box calculator|1300|消费者免费计算/预算工具：仅记量，不作SaaS需求|8|8/8|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=moving%20box%20calculator&gl=us&hl=en)|
|US|moving company software|590|明确B2B软件：进入第三步|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=moving%20company%20software&gl=us&hl=en)|
|US|moving cost calculation|6600|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|8/8|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=moving%20cost%20calculation&gl=us&hl=en)|
|US|moving rate calculator|6600|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|8/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=moving%20rate%20calculator&gl=us&hl=en)|
|US|small moving company|1000|本地服务或服务价格：本地服务跳过|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=small%20moving%20company&gl=us&hl=en)|
|US|local moving company|60500|本地服务或服务价格：本地服务跳过|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=local%20moving%20company&gl=us&hl=en)|
|US|man with van|590|本地服务或服务价格：本地服务跳过|8|7/7|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=man%20with%20van&gl=us&hl=en)|
|US|man and van|720|本地服务或服务价格：本地服务跳过|8|7/7|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=man%20and%20van&gl=us&hl=en)|
|US|single item movers|590|本地服务或服务价格：本地服务跳过|9|8/8|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=single%20item%20movers&gl=us&hl=en)|
|US|same day movers|4400|本地服务或服务价格：本地服务跳过|9|7/7|1|1|有缝隙|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=same%20day%20movers&gl=us&hl=en)|
|US|moving company rates|480|本地服务或服务价格：本地服务跳过|6|4/6|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=moving%20company%20rates&gl=us&hl=en)|
|US|moving cost per hour|480|本地服务或服务价格：本地服务跳过|8|8/8|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=moving%20cost%20per%20hour&gl=us&hl=en)|
|US|moving company estimate|2400|本地服务或服务价格：本地服务跳过|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=moving%20company%20estimate&gl=us&hl=en)|
|UK|moving cost calculator|480|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|9/9|1|1|有缝隙|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=moving%20cost%20calculator&gl=uk&hl=en)|
|UK|house moving calculator|320|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|7/8|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=house%20moving%20calculator&gl=uk&hl=en)|
|UK|moving cost estimator|480|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=moving%20cost%20estimator&gl=uk&hl=en)|
|UK|cubic feet calculator|590|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|9/9|1|1|有缝隙|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=cubic%20feet%20calculator&gl=uk&hl=en)|
|UK|moving cost calculation|480|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|8/9|1|1|有缝隙|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=moving%20cost%20calculation&gl=uk&hl=en)|
|UK|moving rate calculator|480|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=moving%20rate%20calculator&gl=uk&hl=en)|
|UK|local moving company|720|本地服务或服务价格：本地服务跳过|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=local%20moving%20company&gl=uk&hl=en)|
|UK|man with van|8100|本地服务或服务价格：本地服务跳过|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=man%20with%20van&gl=uk&hl=en)|
|UK|man and van|9900|本地服务或服务价格：本地服务跳过|10|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=man%20and%20van&gl=uk&hl=en)|
|UK|house removal quotes|210|本地服务或服务价格：本地服务跳过|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=house%20removal%20quotes&gl=uk&hl=en)|
|CA|moving cost calculator|320|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=moving%20cost%20calculator&gl=ca&hl=en)|
|CA|moving cost estimator|320|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|7/8|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=moving%20cost%20estimator&gl=ca&hl=en)|
|CA|cubic feet calculator|2400|消费者免费计算/预算工具：仅记量，不作SaaS需求|10|10/10|1|1|有缝隙|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=cubic%20feet%20calculator&gl=ca&hl=en)|
|CA|moving cost calculation|320|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=moving%20cost%20calculation&gl=ca&hl=en)|
|CA|moving rate calculator|320|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=moving%20rate%20calculator&gl=ca&hl=en)|
|CA|local moving company|3600|本地服务或服务价格：本地服务跳过|9|6/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=local%20moving%20company&gl=ca&hl=en)|
|CA|same day movers|480|本地服务或服务价格：本地服务跳过|9|8/8|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=same%20day%20movers&gl=ca&hl=en)|
|AU|local moving company|390|本地服务或服务价格：本地服务跳过|9|2/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=local%20moving%20company&gl=au&hl=en)|
|AU|man with van|720|本地服务或服务价格：本地服务跳过|7|2/7|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=man%20with%20van&gl=au&hl=en)|
|AU|last minute removals|260|本地服务或服务价格：本地服务跳过|9|0/9|0|0|未找到|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=last%20minute%20removals&gl=au&hl=en)|
|DE|Umzugskosten Rechner|590|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|0/9|0|0|未找到|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=Umzugskosten%20Rechner&gl=de&hl=de)|
|FR|simulateur prix déménagement|260|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|8/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=simulateur%20prix%20d%C3%A9m%C3%A9nagement&gl=fr&hl=fr)|
|FR|devis déménagement en ligne|1000|本地服务或服务价格：本地服务跳过|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=devis%20d%C3%A9m%C3%A9nagement%20en%20ligne&gl=fr&hl=fr)|
|FR|calculateur volume déménagement|480|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=calculateur%20volume%20d%C3%A9m%C3%A9nagement&gl=fr&hl=fr)|
|FR|estimation volume déménagement|210|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=estimation%20volume%20d%C3%A9m%C3%A9nagement&gl=fr&hl=fr)|
|FR|calculateur m3 déménagement|210|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|8/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=calculateur%20m3%20d%C3%A9m%C3%A9nagement&gl=fr&hl=fr)|
|FR|estimation m3 déménagement|320|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=estimation%20m3%20d%C3%A9m%C3%A9nagement&gl=fr&hl=fr)|
|FR|prix déménagement m3|590|本地服务或服务价格：本地服务跳过|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=prix%20d%C3%A9m%C3%A9nagement%20m3&gl=fr&hl=fr)|
|ES|precio guardamuebles|210|本地服务或服务价格：本地服务跳过|10|5/10|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=precio%20guardamuebles&gl=es&hl=es)|
|IT|preventivo trasloco online|210|本地服务或服务价格：本地服务跳过|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=preventivo%20trasloco%20online&gl=it&hl=it)|
|IT|piattaforma per traslochi|320|实体升降设备：排除|8|8/8|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=piattaforma%20per%20traslochi&gl=it&hl=it)|
|IT|listino prezzi traslochi|320|本地服务或服务价格：本地服务跳过|9|9/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=listino%20prezzi%20traslochi&gl=it&hl=it)|
|NL|kleine verhuizing|260|本地服务或服务价格：本地服务跳过|10|10/10|1|0|有缝隙|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=kleine%20verhuizing&gl=nl&hl=nl)|
|JP|引越し 費用 計算|210|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|2/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=%E5%BC%95%E8%B6%8A%E3%81%97%20%E8%B2%BB%E7%94%A8%20%E8%A8%88%E7%AE%97&gl=jp&hl=ja)|
|JP|引越し 見積もり シミュレーション|1000|消费者免费计算/预算工具：仅记量，不作SaaS需求|9|2/9|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=%E5%BC%95%E8%B6%8A%E3%81%97%20%E8%A6%8B%E7%A9%8D%E3%82%82%E3%82%8A%20%E3%82%B7%E3%83%9F%E3%83%A5%E3%83%AC%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3&gl=jp&hl=ja)|
|JP|引越し 見積もり オンライン|720|本地服务或服务价格：本地服务跳过|9|4/8|0|0|老站占优（仅已知样本）|[量源](https://api.pxany.com/v1/keyword-volumes) / [Google](https://www.google.com/search?q=%E5%BC%95%E8%B6%8A%E3%81%97%20%E8%A6%8B%E7%A9%8D%E3%82%82%E3%82%8A%20%E3%82%AA%E3%83%B3%E3%83%A9%E3%82%A4%E3%83%B3&gl=jp&hl=ja)|

## 边界修正

US moving company software仅返回9条；缺第10位，不声称完整前十。最年轻movingcrm.ai注册于2024-10-14，约2年，超18个月。emoversoftware.com的DR19只能说明已有相对低权重站曝光，不能等同新站容易。

UK moving cost calculator的calcforlife.com注册于2025-10-26，精确日期仍在12个月内，原age_years四舍五入为1.0；仍只是消费预算页。US same day movers和NL kleine verhuizing即使有新域名也本地服务跳过。意大利piattaforma per traslochi看SERP是升降设备，排除。
