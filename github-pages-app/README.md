# 旅行行程 App

這是一個可部署到 GitHub Pages 的純靜態單頁 App。

## 部署到 GitHub Pages

1. 建立或打開你的 GitHub repository。
2. 把這個資料夾內的所有檔案放到 repository 根目錄。
3. 到 GitHub repository 的 `Settings` -> `Pages`。
4. 在 `Build and deployment` 的 `Source` 選 `GitHub Actions`。
5. 推送到 `main` 分支後，GitHub Actions 會自動部署。

部署完成後，網址通常會是：

```text
https://你的帳號.github.io/你的repo/
```

## CSV 欄位

支援欄位包含：`日期`、`開始`、`結束`、`標題`、`地點`、`城市`、`地址`、`交通`、`分類`、`費用`、`備註`、`連結`、`地圖`。

App 也支援常見英文欄位，例如 `date`、`start`、`title`、`place`、`city`、`note`、`url`、`map`。
