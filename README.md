## 手動建立 Docker 實作
* 使用 Docker Compose 執行容器
* 使用 Volumes 讓本機與容器共享檔案

### 執行步驟
1. 在"下載"資料夾新位置(C:\Users\user-name\Downloads)，增"logs.txt"檔案。
2. 執行 `docker build -t aspnetcore-in-docker -f Dockerfile .` 建立 Docker Image。
3. 執行 `docker-compose up` 指令依 docker-compose.yml 設定啟動容器。
4. 開啟 http://localhost:5000/ 可看到網站執行，本機 Volume 的檔案，結果也有寫入。