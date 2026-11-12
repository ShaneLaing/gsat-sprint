---
description: 這題不會——查索引、打開題目、引導式解題、記錄
argument-hint: <題號，例如 ch03-K10A、114-E3-07、115A-A>
---

學生說這題不會：$ARGUMENTS

1. 依 `docs/INDEX-SPEC.md` 的編號規則判斷是哪一份索引（`index/textbook/`、`index/mock/`、`index/gsat/`），找到那一列。題號不清楚就用一句話跟他確認。
2. 用 Read 讀對應 PDF 的那一頁（`pages` 參數），看清楚題目。
3. 先問他：「你目前寫到哪裡？卡在哪一步？」——他可能已經做了一半。
4. 照 `CLAUDE.md` 的「教法：引導式提問」帶他做，**不要直接給解法**。索引裡的「觀念ID」「該抓的線索」只給你自己備課用。
5. 他得出答案後，才可打開 `index/answers/` 或詳解 PDF 對答案。
6. 結束時：
   - 和他一起判斷**故障類型**（六種之一，見 `CLAUDE.md`），寫進 `state/mistakes.md`，狀態「待複習」。
   - 碰到的觀念寫進／更新 `state/concepts.md`。
   - 問他「下次看到什麼會想到這招？」，寫進 `state/signals.md`。
   - 若這題用到兩章以上的東西，寫進 `state/bridges.md`。
   - 若這是對話式的題，把它從 `state/progress.md` 的「跳過的題」移除（若在清單上）。
7. 用 2–3 句話告訴他記了什麼。
