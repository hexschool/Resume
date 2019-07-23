# 六角人才牆
![最後一次更新](https://img.shields.io/github/last-commit/hexschool/Resume.svg "最後一次更新")

這是由六角學院所提供的六角人才牆，這裡所有刊登的人才都是由六角學院所鑑定，在這邊刊登的話，您的求職資訊將會直接曝光給所有廠商。

若您已達到[**刊登門檻**](https://github.com/hexschool/Resume#刊登門檻)，可以依照[**刊登流程**](https://github.com/hexschool/Resume#刊登流程)簡單幾步驟完成：

## 刊登門檻

**請務必確認自己已達到 [skill.md](https://github.com/hexschool/Resume/blob/master/skill.md) 的審核標準，否則將退 PR。**

## 刊登流程

已達刊登門檻 → Fork 當前版本 → Clone develop 分支 → **依 [README 刊登規範](https://github.com/hexschool/Resume#刊登規範) 填寫 profile.json** → 發送 Pull request (PR) 至分支 develop ↓

進入審核 → 審核成功 → merge 到當前 Master 分支 → **成功曝光給廠商！** 

※ 發送 PR 時，標題欄位與 Commit 請填寫「**新增資料 - XXX**」，**XXX** 為您的姓名，例如：「**新增資料 - 王小明**」。

<a href="https://hsiangfeng.github.io/git/20190615/4143994266/" target="_blank">Pull request (PR)參考文章</a>。

## 刊登規範

※ 填寫刊登資訊時，請務必依照欄位填寫，並於 profile.json 最後一筆加入個人資訊，**若未依照欄位規範填寫，將退 PR**。

※ 個人簡述的字數可以使用此 <a href="https://www.ifreesite.com/wordcount/" target="_blank">小工具</a>，來了解自己是否超出 150 字，請觀看 **總數** 欄位。

※ 大頭貼圖片可以使用 <a href="https://imgur.com/" target="_blank">Imgur 空間服務</a>。

```
imgUrl:     大頭貼圖片連結 (圖片建議大小: 150 x 150，連結範例: https://i.imgur.com/xxx.jpg)
name:       個人真實姓名
tags:       擅長技能 (最多僅可填入 4 種主要技能，一個 tags 代表一個技術，舉例: ["RWD", "JavaScript"]，注意 CSS&HTML 請輸入 RWD)
job:        應徵職缺名稱 (僅可輸入 1 種應徵職缺)
location:   應徵求職地點，請依照地區輸入名稱 (最多輸入 4 筆求職地點，請勿輸入"全部"、"不限"、"全地區"等)
type:       工作性質 (僅可輸入"全職"、"兼職"、"遠端協作"，這 3 種工作性質)
experience: 相關工作經歷 (僅可輸入數字，單位是以年為單位，若為半年則是輸入 0.6，若是兩年相關經歷則輸入 2)
description:個人簡述 (限制 150 字數內)
profileUrl: 個人線上履歷連結，線上履歷內請務必附上作品 Demo 與原始碼連結 (GitHub)
```

範例格式：
```JSON
[
  {
    "imgUrl":"https://fakeimg.pl/150x150/",
    "name":"廖洧杰",
    "tags":["Node.js", "Vue.js", "Gulp", "Bootstrap"],
    "job":["前端工程師"],
    "location": ["台北", "台中", "台東","屏東"],
    "type":["全職", "兼職", "遠端協作"],
    "experience": 1,
    "description": "接觸互動作業可以說智慧試驗界面用戶，很快突破專題本月很快什麼，一臉風景厲害是他不如說話夏天冠軍法律責任售價製品定義之間網路，導致執行時間一聲工程傳說拒絶物流明年二人部隊，生成高速有所充滿提示不是很人口，學會目錄一項，授權公共權威衝突模糊小孩，千萬平靜這樣減肥評論負責組成各種合適體制突然，果然到了部。",
    "profileUrl": "https://www.cakeresume.com"
  },
  {
    "imgUrl":"https://fakeimg.pl/150x150/",
    "name":"王小明",
    "tags":["Git", "RWD", "JavaScript"],
    "job":["前端工程師"],
    "location": ["台南", "高雄","雲林"],
    "type":["全職", "兼職"],
    "experience": 0,
    "description": "關閉地球版權訪問有限責任公司，由於近年來，只能認證硬體到來居住說明讓他選擇之家負責人瘋狂世界工人，根據門派確保小心論文產生，庫存校長性質最快招商有很多危險持續方案基礎，下一頁判斷小孩不好但在，系列對。",
    "profileUrl": "https://www.cakeresume.com"
  },
  {
    "imgUrl":"https://fakeimg.pl/150x150/",
    "name":"漂亮阿姨",
    "tags":["Git", "RWD", "JavaScript"],
    "job":["前端工程師"],
    "location": ["嘉義"],
    "type":["遠端協作"],
    "experience": 5,
    "description": "關閉地球版權訪問有限責任公司，由於近年來，只能認證硬體到來居住說明讓他選擇之家負責人瘋狂世界工人，根據門派確保小心論文產生，庫存校長性質最快招商有很多危險持續方案基礎，下一頁判斷小孩不好但在，系列對。",
    "profileUrl": "https://www.cakeresume.com"
  }
]
```

## 注意事項

- 若求職者履歷連結為 **404** 將會被**系統自動下架**。
- 求職者若找到工作，請務必**刪除刊登資訊**。
  - 當您成功透過人才牆媒合工作後，將會被加入至**就業成功榜**內，僅會留下名子與頭像。
- 求職者若要更新刊登資訊、刪除刊登資訊，請重新發送 PR。
  - 更新刊登資訊 or 刪除刊登資訊時，標題欄位與 Commit 標題請打 「**更新資料 - 王小明**」、「**刪除資料 - 王小明**」
- 若發生衝突請自行解決。
  - 解決衝突問題可以參考<a href="https://hsiangfeng.github.io/git/20190621/4239571950/" target="_blank">此篇文章</a>。
- 請務必注意中英文空格問題，**否則將會退PR**。
  - 可參考 [中文文案排版指北](https://github.com/sparanoid/chinese-copywriting-guidelines)。
## 系統更新時間

※ 本系統將於**每週五做一次更新**人才牆刊登資訊，若要刊登資訊，請於**週一 ~ 週四提出 PR**。
