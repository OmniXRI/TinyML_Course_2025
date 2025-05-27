# OmniXRI TinyML 小學堂 (2025) 【第 11 講】影像應用─物件偵測

<img src="https://raw.githubusercontent.com/OmniXRI/TinyML_Course_2025/refs/heads/main/images/2025_TinyML%E5%B0%8F%E5%AD%B8%E5%A0%82%E8%AA%B2%E7%A8%8B%E7%9B%B4%E6%92%AD%E5%9C%96%E7%A4%BA_Ch11.JPG" alt="" width="640">  

<span style="color:#FF0000;">**本課程完全免費，請勿移作商業用途！更多課程內容請參考文末教學資源連結。歡迎追蹤、留言、訂閱、點讚、轉發，讓更多需要的朋友也能一起學習。**</span>

**課程直播日期： 2025/05/21**  
**課程直播連結：https://youtu.be/NfwqOlriZ-o**  
**課程簡報名稱： 20250521_TInyML_Course_Ch11_OmniXRI_Jack.pdf**  

## 課程內容

11.1. Edge Impulse 開發環建置  
* TinyML 開發流程選項  
* Seeed Grove Vision AI V2 Kit  
* Grove Vision AI Module V2 技術文件  
* Grove Vision AI Module V2 元件圖  
* 下載及安裝必要工具  
* 安裝 Edge Impulse 工作環境  
* 安裝驅動程式 (USB Virtual COM)   
* 開發板組裝 ─ 連接攝影機   
* 開發板組裝 ─ 連接USB  
* Edge Impulse AI 硬體 ─ WiseEye2說明  
* 安裝 COM 高速通訊工具 xmodem  
* 燒錄預編譯映像檔 ─ Edge Impulse CLI  
* 燒錄預編譯映像檔 ─ Python + xmodem  
* 回復出廠設定 ─ SensenCraft Web Toolkit  
* 開發板連接 Edge Impuse Studio  
* Edge Impulse Studio 裝置清單  

11.2. 影像資料集建置  
* 影像資料集比較  
* 常見物件偵測資料標註工具  
    * [LabelMe](https://github.com/wkentaro/labelme)
    * [LabelImg](https://github.com/HumanSignal/labelImg)
    * [CVAT](https://www.cvat.ai/)
    * [Roboflow](https://roboflow.com/)
* 常見物件偵測標註格式 ─ VOC, YOLO  
* YOLO 家族發展史  
* Edge Impulse 資料集建置方式  
* [Edge Impulse 物件偵測範例](https://docs.edgeimpulse.com/docs/tutorials/end-to-end-tutorials/computer-vision/object-detection/object-detection)  
* Edge Impulse Studio 資料擷取  
* Edge Impulse Studio 建立物件標籤  

11.3. 模型選用與訓練  
* Edge Impulse Studio ─ 建立模型  
* Edge Impulse Studio ─ 產生特徵  
* Edge Impulse Studio ─ 訓練模型  
* Edge Impulse Studio ─ 訓練結果  

11.4. 模型部署與測試  
* 採用 Edge Impulse 訓練轉換  
* 下載 TFLite 模型  
* 使用 Google Colab 進行轉換  

## 參考文獻  

* 許哲豪，臺灣科技大學資訊工程系「人工智慧與邊緣運算實務」（2021~2023）  
https://omnixri.blogspot.com/p/ntust-edge-ai.html  

* 許哲豪，OmniXRI's Edge AI & TinyML 小學堂 Youtube 直播課程總結  
https://omnixri.blogspot.com/2024/06/omnixris-edge-ai-tinyml-youtube.html  

* 許哲豪，歐尼克斯實境互動工作室系列發文─TinyML(MCU AI)系列  
https://hackmd.io/1PK1URhIQ7GutcWgpgsWbg#TinyMLMCU-AI%E7%B3%BB%E5%88%97  

* Edge Impulse, Seeed Grove Vision AI Module V2 (WiseEye2)  
https://docs.edgeimpulse.com/docs/edge-ai-hardware/mcu-+-ai-accelerators/himax-seeed-grove-vision-ai-module-v2-wise-eye-2  

* Edge Impulse, Object detection with bounding boxes  
https://docs.edgeimpulse.com/docs/tutorials/end-to-end-tutorials/computer-vision/object-detection/object-detection  

## 延伸閱讀  

* Edge Impulse CLI Installation  
https://docs.edgeimpulse.com/docs/tools/edge-impulse-cli/cli-installation  

* Seeed Studio Grove Vision AI Module V2  
https://wiki.seeedstudio.com/grove_vision_ai_v2/  

* Seeed SenseCraft Web Toolkit  
https://seeed-studio.github.io/SenseCraft-Web-Toolkit/#/setup/process  

* Github – edgeimpulse, firmware-seeed-grove-vision-ai-module-v2  
https://github.com/edgeimpulse/firmware-seeed-grove-vision-ai-module-v2  

*  MJRoBot (Marcelo Rovai), MJRoBot (Marcelo Rovai)Computer Vision at the Edge with Grove Vision AI Module V2  
https://www.hackster.io/mjrobot/computer-vision-at-the-edge-with-grove-vision-ai-module-v2-0003c7  

## 教學資源  

OmniXRI 系列文章：  
https://omnixri.blogspot.com/p/blog-page_19.html  

OmniXRI Youtube 教學影片頻道：  
https://www.youtube.com/@omnixri1784/videos  

OmniXRI Github 課程簡報及相關範例：  
https://github.com/OmniXRI/TinyML_Course_2025

---
**註：本課程非學校正式課程，現僅有老師一人，沒有教學助理可幫忙，如操作上有相關問題，請於[Youtube](https://www.youtube.com/@omnixri1784/featured), [FB Group](https://www.facebook.com/groups/edgeaitw), [Blogger](https://omnixri.blogspot.com/), [Medium](https://omnixri.medium.com/), [Hackmd](https://hackmd.io/@OmniXRI-Jack), [Github](https://github.com/OmniXRI) 各討論區中留言，老師會儘量協助，如有服務不週之處尚請見諒。**
