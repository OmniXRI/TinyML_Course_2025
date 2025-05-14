# OmniXRI TinyML 小學堂 (2025) 【第 10 講】影像應用─影像分類

<img src="https://raw.githubusercontent.com/OmniXRI/TinyML_Course_2025/refs/heads/main/images/2025_TinyML%E5%B0%8F%E5%AD%B8%E5%A0%82%E8%AA%B2%E7%A8%8B%E7%9B%B4%E6%92%AD%E5%9C%96%E7%A4%BA_Ch10.JPG" alt="" width="640">  

<span style="color:#FF0000;">**本課程完全免費，請勿移作商業用途！更多課程內容請參考文末教學資源連結。歡迎追蹤、留言、訂閱、點讚、轉發，讓更多需要的朋友也能一起學習。**</span>

**課程直播日期： 2025/05/14**  
**課程直播連結：https://youtu.be/WryghjuDyPQ**  
**課程簡報名稱： 20250514_TInyML_Course_Ch10_OmniXRI_Jack.pdf**  

## 課程內容

10.1. Seeed SenseCraft AI 開發環建置  
* Seeed Grove Vision AI V2 Kit  
* Grove Vision AI Module V2 規格  
* Grove Vision AI Module V2 接腳圖  
* Grove Vision AI Module V2 元件圖  
* [Grove Vision AI Module V2 技術文件](https://wiki.seeedstudio.com/grove_vision_ai_v2/
)  
* [Xiao ESP32-C3 技術文件](https://wiki.seeedstudio.com/XIAO_ESP32C3_Getting_Started/
)  
* 開發板組裝 ─ 連接攝影機   
* 開發板組裝 ─ 連接攝影機（動畫）  
* 安裝驅動程式 (USB – COM)   
* 開發板組裝 ─ 連接USB  
* [Seeed SenseCraft AI 功能概述](https://sensecraft.seeed.cc/ai/)      
* Seeed SenseCraft AI ─ 註冊與登錄  
* Seeed SenseCraft AI ─ 預訓練模型  
* Seeed SenseCraft AI ─ 部署模型  
* Seeed SenseCraft AI ─ 執行推論  
* Seeed SenseCraft AI ─ 數據輸出  
* 燒錄故障排除 ─ ESP32C3  
* [Seeed SenseCraft Web Toolkit](https://seeed-studio.github.io/SenseCraft-Web-Toolkit/#/setup/process)  

10.2. 影像資料集建置  
* 資料集建置 – 分類識別 ─ 數據採集  
* 資料集建置 – 分類識別 ─ 資料多樣態  

10.3. 模型訓練與部署  
* 資料集建置 – 分類識別 ─ 模型訓練部署  
* 建立自定義模型 ─ 第一步基礎信息  
* 建立自定義模型 ─ 第二步模型  
* 部署並執行自定義模型  
* [進階補充 ─ 更多自定義模型訓練方式](https://wiki.seeedstudio.com/ModelAssistant_Introduce_Quick_Start/#model-training)  

10.4. 檢測結果輸出  
* 透過 Virtual-COM 以文字方式送出結果  
* [UART AT Protocol JSON 輸出文字格式](https://github.com/Seeed-Studio/SSCMA-Micro/blob/1.0.x/docs/protocol/at_protocol.md)  
* Arduino UART 接收結果範例  
* Xiao 開發板連接 Grove Vision AI V2 (動畫)  
* [Seeed SSCMA 技術說明文件](https://sensecraftma.seeed.cc/introduction/quick_start)  
* [下載 Seeed Arduino SSCMA](https://github.com/Seeed-Studio/Seeed_Arduino_SSCMA/)   
* Arudiuno 安裝 Seeed SSCMA   
* Arudiuno 安裝 ArduinoJSON  
* Arduino 新增 Xiao ESP32C3 開發板  
    * https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json  
* Xiao ESP32C3 讀取結果範例程式  
* Xiao ESP32C3 控制 GPIO  

## 參考文獻  

[1] 許哲豪，臺灣科技大學資訊工程系「人工智慧與邊緣運算實務」（2021~2023）  
https://omnixri.blogspot.com/p/ntust-edge-ai.html  

[2] 許哲豪，OmniXRI's Edge AI & TinyML 小學堂 Youtube 直播課程總結  
https://omnixri.blogspot.com/2024/06/omnixris-edge-ai-tinyml-youtube.html  

[3] 許哲豪，歐尼克斯實境互動工作室系列發文─TinyML(MCU AI)系列  
https://hackmd.io/1PK1URhIQ7GutcWgpgsWbg#TinyMLMCU-AI%E7%B3%BB%E5%88%97  

[4] Seeed SenseCraft AI  
https://sensecraft.seeed.cc/ai/home  


## 延伸閱讀  

* Seeed Studio Grove Vision AI Module V2  
https://wiki.seeedstudio.com/grove_vision_ai_v2/  

* Seeed Studio XIAO ESP32C3  
https://wiki.seeedstudio.com/XIAO_ESP32C3_Getting_Started/  

* Seeed SenseCraft Web Toolkit  
https://seeed-studio.github.io/SenseCraft-Web-Toolkit/#/setup/process  

* Seeed SSCMA – Getting Started  
https://sensecraftma.seeed.cc/introduction/quick_start  

* Github Seeed-Studio / SSCMA-Micro – AT Protocol Specification  
https://github.com/Seeed-Studio/SSCMA-Micro/blob/1.0.x/docs/protocol/at_protocol.md  


## 教學資源

OmniXRI 系列文章：  
https://omnixri.blogspot.com/p/blog-page_19.html  

OmniXRI Youtube 教學影片頻道：  
https://www.youtube.com/@omnixri1784/videos  

OmniXRI Github 課程簡報及相關範例：  
https://github.com/OmniXRI/TinyML_Course_2025

---
**註：本課程非學校正式課程，現僅有老師一人，沒有教學助理可幫忙，如操作上有相關問題，請於[Youtube](https://www.youtube.com/@omnixri1784/featured), [FB Group](https://www.facebook.com/groups/edgeaitw), [Blogger](https://omnixri.blogspot.com/), [Medium](https://omnixri.medium.com/), [Hackmd](https://hackmd.io/@OmniXRI-Jack), [Github](https://github.com/OmniXRI) 各討論區中留言，老師會儘量協助，如有服務不週之處尚請見諒。**
