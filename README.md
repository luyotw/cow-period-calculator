# 乳牛發情週期計算

這是一個可直接部署到 GitHub Pages 的靜態頁面。

## 部署到 GitHub Pages

如果這個資料夾還不是 git repository：

```bash
git init
git branch -M main
git add .
git commit -m "Add static cow cycle calculator"
```

接著建立 GitHub repository，加入 remote 並推上去：

```bash
git remote add origin https://github.com/<your-account>/<your-repo>.git
git push -u origin main
```

最後到 repository 的 `Settings` > `Pages`：

1. `Build and deployment` 選擇 `Deploy from a branch`。
2. Branch 選擇 `main`。
3. 資料夾選擇 `/ (root)`。
4. 儲存後等待 GitHub Pages 發布。

入口檔案是 `index.html`。
