# OmniXRI TinyML 小學堂 (2025) 【第 9 講】運動感測器應用─手勢辨識

<img src="https://raw.githubusercontent.com/OmniXRI/TinyML_Course_2025/refs/heads/main/images/2025_TinyML%E5%B0%8F%E5%AD%B8%E5%A0%82%E8%AA%B2%E7%A8%8B%E7%9B%B4%E6%92%AD%E5%9C%96%E7%A4%BA_Ch9.JPG" alt="" width="640">  

<span style="color:#FF0000;">**本課程完全免費，請勿移作商業用途！更多課程內容請參考文末教學資源連結。歡迎追蹤、留言、訂閱、點讚、轉發，讓更多需要的朋友也能一起學習。**</span>

**課程直播日期： 2025/05/07**  
**課程直播連結：https://youtu.be/TSUBkupIEQE**  
**課程簡報名稱： 20250507_TInyML_Course_Ch09_OmniXRI_Jack.pdf**  

## 課程內容

9.1. 運動資料集建置  
* 何謂運動感測器  
* 運動感測常見應用  
* [Edge Impulse 運動感測相關案例](https://docs.edgeimpulse.com/experts#accelerometer-and-activity-projects)  
* [Seeed Xiao nRF52840 Sense](https://wiki.seeedstudio.com/cn/XIAO_BLE/)  
* Xiao nRF52840 Sense 模組 ─ 參考電路  
* 穿戴式智慧人工智慧裝置 ─ 參考外形  
* Arduino 新增開發板設定
    https://files.seeedstudio.com/arduino/package_seeeduino_boards_index.json  
* 安裝Seeed nRF52840函式庫  
* 指定工作開發板及埠號  
* [安裝運動感測器（IMU）函式庫](https://github.com/Seeed-Studio/Seeed_Arduino_LSM6DS3)  
* 運動感測器（IMU）取值範例  
* IMU 連續取值輸出至 Edge Impulse  
* 監看運動感測器（IMU）輸出值  
* 設計自定義操作手勢  

9.2. Edge Impulse 開發環境建置  
* TinyML 開發流程選項  
* Edge Impulse 資料集建置方式  
* [快速操作指令表](https://github.com/OmniXRI/Edge_AI_TinyML_Course_2024/blob/main/Ch13_Motion_Recognition/IMU_Quick_Guide.md)  
* 下載及安裝必要工具  
    1. [Python 3.x](https://www.python.org/downloads/)  
    2. [Node.js](https://nodejs.org/en/download/package-manager)  
    3. [Arduino CLI](https://arduino.github.io/arduino-cli/0.35/installation/)  
* 安裝 Edge Impulse windows 工作環境
    npm install -g edge-impulse-cli --force  
* 建立 Edge Impulse 新專案  
* 啟動edge-impulse-data-forwarder  
    edge-impulse-data-forwarder --clean
* 檢查裝置是否已連線  
* 從外部裝置取得資料  
* 大量收集樣本並分割成獨立可訓練樣本  
* 原始資料與自動分割  
* 反複收集分割，建立完整資料集  

9.3. 模型選用與訓練  
* 選擇模型及設定必要參數  
* 提取資料特徵  
* 提取特徵結果  
* 設定分類訓練相關參數  
* 開始進行模型訓練及結果顯示  
* 線上測試（從外部裝置取樣）  

9.4. 模型部署與測試  
* 選擇部署種類及設定參數  
* 導入 Arduino 函式庫並進行推論測試  
* 手勢辨識結果（Arduino部份） 
* [Arduino 2.0 快速(增量)編譯](https://omnixri.blogspot.com/2024/10/arduino-20.html)  

## 參考文獻

[1] 許哲豪，臺灣科技大學資訊工程系「人工智慧與邊緣運算實務」（2021~2023）  
https://omnixri.blogspot.com/p/ntust-edge-ai.html  

[2] 許哲豪，OmniXRI's Edge AI & TinyML 小學堂 Youtube 直播課程總結  
https://omnixri.blogspot.com/2024/06/omnixris-edge-ai-tinyml-youtube.html  

[3] 許哲豪，歐尼克斯實境互動工作室系列發文─TinyML(MCU AI)系列  
https://hackmd.io/1PK1URhIQ7GutcWgpgsWbg#TinyMLMCU-AI%E7%B3%BB%E5%88%97  

[4] 許哲豪，【課程簡報】20240509_慈濟醫資_穿戴式人工智慧工作坊_利用TinyML技術快速搭建微型智慧應用  
https://omnixri.blogspot.com/2024/05/20240509tinyml12.html  

[5] 許哲豪， OmniXRI's Edge AI & TinyML 小學堂 【第13講】實作案例 ─運動辨識（快速指令表）  
https://github.com/OmniXRI/Edge_AI_TinyML_Course_2024/blob/main/Ch13_Motion_Recognition/IMU_Quick_Guide.md  

## 延伸閱讀  

* 許哲豪，如何讓 Arduino 2.0 快速編譯（增量編譯）  
https://omnixri.blogspot.com/2024/10/arduino-20.html  

* Seeed, Xiao nRF52840 Sense – Embedded ML – Motion Recognition based on Edge Impulse  
https://wiki.seeedstudio.com/XIAOEI/  

* Github, Seeed-Studio / Seeed_Arduino_LSM6DS3  
https://github.com/Seeed-Studio/Seeed_Arduino_LSM6DS3  

* Seeed, Xiao nRF52840 Sense – Embedded ML – Getting Started with TensorFlow Lite on Seeed Studio XIAO nRF52840 Sense  
https://wiki.seeedstudio.com/XIAO-BLE-Sense-TFLite-Getting-Started/  

## 教學資源

OmniXRI 系列文章：  
https://omnixri.blogspot.com/p/blog-page_19.html  

OmniXRI Youtube 教學影片頻道：  
https://www.youtube.com/@omnixri1784/videos  

OmniXRI Github 課程簡報及相關範例：  
https://github.com/OmniXRI/TinyML_Course_2025

---
**註：本課程非學校正式課程，現僅有老師一人，沒有教學助理可幫忙，如操作上有相關問題，請於[Youtube](https://www.youtube.com/@omnixri1784/featured), [FB Group](https://www.facebook.com/groups/edgeaitw), [Blogger](https://omnixri.blogspot.com/), [Medium](https://omnixri.medium.com/), [Hackmd](https://hackmd.io/@OmniXRI-Jack), [Github](https://github.com/OmniXRI) 各討論區中留言，老師會儘量協助，如有服務不週之處尚請見諒。**
