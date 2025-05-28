# OmniXRI TinyML 小學堂 (2025) 【第 12 講】影像應用─姿態估測

<img src="https://raw.githubusercontent.com/OmniXRI/TinyML_Course_2025/refs/heads/main/images/2025_TinyML%E5%B0%8F%E5%AD%B8%E5%A0%82%E8%AA%B2%E7%A8%8B%E7%9B%B4%E6%92%AD%E5%9C%96%E7%A4%BA_Ch12.JPG" alt="" width="640">  

<span style="color:#FF0000;">**本課程完全免費，請勿移作商業用途！更多課程內容請參考文末教學資源連結。歡迎追蹤、留言、訂閱、點讚、轉發，讓更多需要的朋友也能一起學習。**</span>

**課程直播日期： 2025/05/28**  
**課程直播連結：https://youtu.be/3SnCn-qKP0Q**  
**課程簡報名稱： 20250528_TInyML_Course_Ch12_OmniXRI_Jack.pdf**  

## 課程內容

12.1. Himax SDK 開發環境建置  
* Seeed Grove Vision AI V2 Kit  
* [Grove Vision AI Module V2 技術文件](https://wiki.seeedstudio.com/grove_vision_ai_v2/)  
* TinyML 開發流程選項  
* [Github - Himax - Grove Vision AI Module V2](https://github.com/HimaxWiseEyePlus/Seeed_Grove_Vision_AI_Module_V2)  
* Yolov8n Pose 參考文件及預編譯模型  
* 準備 Windows 編譯環境  

12.2. Yolov8n 姿態資料集與模型  
* 常見姿態估測資料集 – [OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose)  
* 常見姿態估測資料集 – [Google MediaPipe](https://ai.google.dev/edge/mediapipe/solutions/guide?hl=zh-tw)  
* 常見姿態估測資料集 – [Microsoft COCO](https://cocodataset.org/#keypoints-2017)  
* Yolov8 主要功能  
* Yolov8 模型名稱  
* [YOLOv8 姿態估測模型及效能](https://docs.ultralytics.com/zh/models/yolov8/#performance-metrics)  
* YOLOv8 姿態輸出結果  
* [SenseCraft Web Toolkit](https://seeed-studio.github.io/SenseCraft-Web-Toolkit/) – 姿態估測  

12.3. 程式編譯  
* [EPII_CM55M_APP_S 待編譯程式](https://github.com/HimaxWiseEyePlus/Seeed_Grove_Vision_AI_Module_V2) 
* 如何在 Windows 環境編譯  

12.4. 模型部署與測試  
* 安裝驅動程式 (USB Virtual COM)   
* 開發板組裝 ─ 連接USB  
* 燒錄方式1 ─ 使用 [Edge Impulse CLI](https://docs.edgeimpulse.com/docs/tools/edge-impulse-cli/cli-installation)  
* 燒錄方式2 ─ 使用 Python + xmodem  

## 參考文獻  

* 許哲豪，臺灣科技大學資訊工程系「人工智慧與邊緣運算實務」（2021~2023）  
https://omnixri.blogspot.com/p/ntust-edge-ai.html  

* 許哲豪，OmniXRI's Edge AI & TinyML 小學堂 Youtube 直播課程總結  
https://omnixri.blogspot.com/2024/06/omnixris-edge-ai-tinyml-youtube.html  

* 許哲豪，歐尼克斯實境互動工作室系列發文─TinyML(MCU AI)系列  
https://hackmd.io/1PK1URhIQ7GutcWgpgsWbg#TinyMLMCU-AI%E7%B3%BB%E5%88%97  

* Edge Impulse, Seeed Grove Vision AI Module V2 (WiseEye2)  
https://docs.edgeimpulse.com/docs/edge-ai-hardware/mcu-+-ai-accelerators/himax-seeed-grove-vision-ai-module-v2-wise-eye-2  

* Github – HimaxWiseEyePlus / YOLOv8_on_WE2  
https://github.com/HimaxWiseEyePlus/YOLOv8_on_WE2  

## 延伸閱讀  

* Edge Impulse CLI Installation  
https://docs.edgeimpulse.com/docs/tools/edge-impulse-cli/cli-installation  

* Seeed Studio Grove Vision AI Module V2  
https://wiki.seeedstudio.com/grove_vision_ai_v2/  

* Seeed SenseCraft Web Toolkit  
https://seeed-studio.github.io/SenseCraft-Web-Toolkit/#/setup/process  

* MJRoBot (Marcelo Rovai), MJRoBot (Marcelo Rovai)Computer Vision at the Edge with Grove Vision AI Module V2  
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
