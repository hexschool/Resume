# 六角人才牆
![](https://img.shields.io/github/last-commit/hsiangfeng/hsiangfeng.github.io.svg "最後一次更新")
![](https://img.shields.io/bitbucket/pr-raw/hsiangfeng/hsiangfeng.github.io.svg "求職人數")

## 求職者

**請務必確認自己已達到 skill.md 的審核標準，否則將會退 PR。**

## 求職流程

已達審核標準 → fork 當前版本 → **依 README 規範填寫 JSON 格式** → 發送 Pull request (PR) ↓

進入審核 → 審核成功 → merge 到當前 Master 分支 → **成功曝光！**

## 張貼規範

※ 填寫求職訊息時，請務必依照欄位填寫，並於 JSON 格式最後一筆加入求職者個人資訊，**若未依照欄位填寫及規範，將會被退 PR**。

```
imgUrl:     求職者照片連結 (圖片大小: 150x150)
name:       求職者姓名
tags:       求職者技能 (最多僅可填入 4 筆技能)
job:        應徵職缺名稱 (僅可輸入 2 種應徵職缺)
location:   求職地，請依照地區輸入名稱 (最多輸入 4 筆求職地)
type:       工作性質 (僅可輸入這 3 種類型性質)
experience: 工作經歷 (僅可接受數字)
profileUrl: 個人履歷連結，個人履歷內請務必附上作品連結及作品原始碼
```

範例格式：
```JSON
[
  {
    "imgUrl":"https://randomuser.me/api/portraits/men/61.jpg",
    "name":"廖洧杰",
    "tags":["Git", "Vue.js", "Gulp", "Bootstrap"],
    "job":["前端工程師", "前端設計師"],
    "location": ["全部", "台北", "台中", "高雄"],
    "type":["全職", "兼職", "遠端協作"],
    "experience": 1,
    "profileUrl": "https://www.cakeresume.com"
  },
  {
    "imgUrl":"https://randomuser.me/api/portraits/women/72.jpg",
    "name":"王小明",
    "tags":["Git", "CSS&HTML", "JavaScript"],
    "job":["前端工程師"],
    "location": ["台南", "高雄"],
    "type":["全職", "兼職"],
    "experience": 1.5,
    "profileUrl": "https://www.cakeresume.com"
  }
]
```

## 注意事項

- 求職者資訊刊登後一個月將會由系統自動下架。
- 若求職者履歷為 404 也會被系統自動下架。
- 求職者若找到工作，請務必刪除求職資訊。