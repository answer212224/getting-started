# Docker 入門教學

[English](README.md) | [繁體中文](README.zh-TW.md)

本教學旨在幫助大家開始使用容器，並專為 Docker Desktop 設計。雖然不會深入探討，但涵蓋了以下主題：

- 運行你的第一個容器
- 建構容器
- 了解容器的概念
- 運行和移除容器
- 使用卷（volumes）來持久化數據
- 使用綁定掛載（bind mounts）支持開發
- 使用容器網絡來支持多容器應用
- 使用 Docker Compose 簡化應用的定義和共享
- 使用映像層緩存加速構建並減少推送/拉取大小
- 使用多階段構建來分離構建時和運行時依賴

## 開始使用

如果你想運行本教學，可以在安裝 Docker Desktop 後使用以下命令：

```bash
docker run -d -p 80:80 docker/getting-started
```

啟動後，你可以打開瀏覽器訪問 [http://localhost](http://localhost)。

## 開發

本項目包含一個 `docker-compose.yml` 文件，可以在你的本地機器上啟動 mkdocs 應用，幫助你即時查看變更。

```bash
docker compose up
```

## 貢獻

如果你發現拼寫錯誤或其他問題，歡迎創建 PR 並提出修復建議！

如果你有改進教學的想法或想建議添加新內容，請先開一個 issue 再開始你的工作。我們雖然很歡迎意見，但我們希望保持教學範圍適合新手。因此，我們可能會拒絕更高級的請求，不希望你浪費任何工作。所以，請先提問，我們很樂意聽取你的想法！
