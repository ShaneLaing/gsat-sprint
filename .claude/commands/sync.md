---
description: 把學習紀錄上傳到 GitHub，讓家教老師看到
---

1. 執行 `git status --short`，只看 `state/`、`docs/plan.md`、`index/answers/` 的變動。
2. 若有變動，用一句話告訴學生要上傳什麼（例：「今天的錯題和觀念紀錄」，不用列檔名），再用對話方塊問「上傳」「先不要」，**他點上傳**才繼續。
3. `git add state/ docs/plan.md index/answers/`，commit 訊息寫 `progress: YYYY-MM-DD 學習紀錄`。
4. `git pull --rebase` 後 `git push`。
5. 若 pull 有衝突或 push 失敗，不要強制覆蓋；告訴他發生了什麼，請他聯絡家教老師。
