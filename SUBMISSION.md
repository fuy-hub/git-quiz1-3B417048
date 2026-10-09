# 作答資料

- 學號：3B417048
- 姓名：張為嘉

## 第 2 題：Git 的三個版本

請填寫完成第二步後，`version.txt` 在三個位置中的內容。

- 已提交版本：v1
- 暫存區版本：v2
- 工作區版本：v3

### 使用的 Git 指令

請填寫你用來確認三種差異的 Git 指令。

1. 工作區 vs 暫存區：

   ```bash
   git diff version.txt
   ```

2. 暫存區 vs 上一次 commit：

   ```bash
   git diff --staged version.txt
   ```

3. 工作區 vs 上一次 commit：

   ```bash
   git diff HEAD version.txt
   ```

## 完成前自我檢查

- [v] 我保留了題目專案原本的 Git commit 歷史。
- [v] `.vscode` 已從目前版本開始停止追蹤，但本機檔案仍保留。
- [v] `version.txt` 的 Git 歷史依序為 `v1 → v2 → v3`。
- [v] 程式修正與文件修改分成不同的 commit。
- [v] `python app.py` 執行後平均為 `72.6`。
- [v] 我已確認 `git status` 沒有尚未處理的變更。
- [v] 我已把完成結果推送到自己的 GitHub Repository。
