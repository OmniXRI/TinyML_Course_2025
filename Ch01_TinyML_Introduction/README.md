# OmniXRI TinyML 小學堂 (2025)  第 1 講 微型人工智慧簡介

<img src="https://raw.githubusercontent.com/OmniXRI/TinyML_Course_2025/refs/heads/main/images/2025_TinyML%E5%B0%8F%E5%AD%B8%E5%A0%82%E8%AA%B2%E7%A8%8B%E7%9B%B4%E6%92%AD%E5%9C%96%E7%A4%BA_Ch1.JPG" alt="" width="640">  

<span style="color:#FF0000;">**本課程完全免費，請勿移作商業用途！更多課程內容請參考文末教學資源連結。歡迎追蹤、留言、訂閱、點讚、轉發，讓更多需要的朋友也能一起學習。**</span>

**課程直播日期： 2025/03/12**  
**課程直播連結： https://youtu.be/3WGp3QFOLMw**  
**課程簡報名稱： 20250312_TInyML_Course_Ch01_OmniXRI_Jack.pdf**  

## 課程內容

1.1. 智慧物聯網與微型人工智慧  
* 傳統物聯網 (IoT) 工作流程  
* 工業物聯網 (IIoT) 架構  
* 智慧物聯網 (AIoT) 架構  
* 智慧健康（穿戴式）物聯網  
* 邊緣智慧 vs. 生成智慧  
* Edge AI 是什麼？  
* 邊緣智慧 (Edge AI) 誰說了算？  
* 何謂微型人工智慧 (TinyML)  
* TinyML 相關論文   
* MCU等級TinyML常見應用及限制  
* 智慧物聯網 vs. 微型人工智慧  

1.2. TinyML 常見應用  
* [TinyML案例分享（技術分類）](https://github.com/user-attachments/assets/9ae2f439-8c1d-40ed-999e-5e8aafdb4757)  
* [TinyML案例分享 ─ Hackster.io](https://www.hackster.io/search?q=tinyml&i=projects)  
* [TinyML案例分享 ─ Edge Impulse Blog](https://www.edgeimpulse.com/blog/)  
* [TinyML案例分享 ─ Arduino TinyML Blog](https://search.arduino.cc/search?tab=&q=tinyML)  
* [TinyML案例分享 ─ Edge AI基金會(Youtube)](https://www.youtube.com/@edgeaifoundation/videos)  

1.3. TinyML 常見開發板  
* MCU vs. MPU / SoC  
* MCU等級主要核心晶片分類  
* 常見tinyML開發板(智能感測)  
* 常見tinyML開發板(自帶攝影機)  
* 常見具視覺TinyML開發板  
* TinyML MCU 等級相關開發板  
* Arm Cortex-M55/M85 + Ethos-U55/U65  
* 單晶片推論速度與耗能比較  
* [各式TinyML視覺開發板效能比較](https://www.hackster.io/mjrobot/computer-vision-at-the-edge-with-grove-vision-ai-module-v2-0003c7)  

1.4. TinyML 常見開發工具  
* TinyML 應用開發流程  
* 資料集建置工具
    * [Edge Impulse Data acquisition - Data Source](https://docs.edgeimpulse.com/docs/edge-impulse-studio/data-acquisition/data-sources)  
    * [SensiML Data Capture Lab](https://sensiml.com/documentation/data-studio/data-collection-overview.html)  
    * [CVAT](https://www.cvat.ai/)  
    * [Roboflow](https://roboflow.com/)  
    * [SenseCraft AI](https://sensecraft.seeed.cc/ai/)  
* 開發框架與工具 (MCU)  
* TinyML 開發平台與技術供應商  
* 開發框架 (CPU / GPU / NPU / MCU)
    * [TensorFlow](https://www.tensorflow.org/?hl=zh-tw)  
    * [TensorFlow Lite (TFL)](https://www.tensorflow.org/lite/guide?hl=zh-tw)  
    * [TensorFlow Lite for Microcontrollers (TFLM, TFLu)](https://www.tensorflow.org/lite/microcontrollers?hl=zh-tw)  
    * [PyTorch](https://pytorch.org/)  
    * [PyTorch Mobile](https://pytorch.org/mobile/home/)  
    * [ExecuTorch](https://pytorch.org/executorch-overview)  
    * [uTensor](https://github.com/uTensor/uTensor)  
    * [microTVM](https://tvm.hyper.ai/docs/topic/microtvm/)
    * [AIfES](https://github.com/Fraunhofer-IMS/AIfES_for_Arduino)  
* MCU硬體廠商收購TinyML軟體開發商  
* [ML Commons (MLPerf) Benchmarks:Tiny](https://mlcommons.org/benchmarks/inference-tiny/)  

## 參考文獻

[1] 許哲豪，NTUST Edge AI 人工智慧與邊緣運算實務  
https://omnixri.blogspot.com/p/ntust-edge-ai.html  

[2] 許哲豪，OmniXRI's Edge AI & TinyML 小學堂 Youtube 直播課程總結  
https://omnixri.blogspot.com/2024/06/omnixris-edge-ai-tinyml-youtube.html  

[3] 許哲豪，OmniXRI系列發文─TinyML(MCU AI)系列  
https://hackmd.io/1PK1URhIQ7GutcWgpgsWbg#TinyMLMCU-AI%E7%B3%BB%E5%88%97  

## 延伸閱讀

* [Edge Impulse Studio Document](https://docs.edgeimpulse.com/docs)
* [Seeed Studio SenseCraft AI](https://sensecraft.seeed.cc/ai/)
* [Google TensorFlow Lite](https://www.tensorflow.org/lite/guide?hl=zh-tw)
* [TensorFlow Lite for Microcontrollers](https://www.tensorflow.org/lite/microcontrollers?hl=zh-tw)
* [Roboflow](https://roboflow.com/)
* [arm Cortex-M55 Processor](https://developer.arm.com/processors/cortex-m55)
* [arm Ethos-U55 MicroNPU](https://developer.arm.com/Processors/Ethos-U55)
* [arm Common Microcontroller Software Interface Standard (CMSIS) V6 Document](https://github.com/ARM-software/CMSIS_6)
* [Github - HimaxWiseEyePlus / Seeed_Grove_Vision_AI_Module_V2](https://github.com/HimaxWiseEyePlus/Seeed_Grove_Vision_AI_Module_V2)

## 教學資源

OmniXRI 系列文章：  
https://omnixri.blogspot.com/p/blog-page_19.html  

OmniXRI Youtube 教學影片頻道：  
https://www.youtube.com/@omnixri1784/videos  

OmniXRI Github 課程簡報及相關範例：  
https://github.com/OmniXRI/TinyML_Course_2025

---
**註：本課程非學校正式課程，現僅有老師一人，沒有教學助理可幫忙，如操作上有相關問題，請於[Youtube](https://www.youtube.com/@omnixri1784/featured), [FB Group](https://www.facebook.com/groups/edgeaitw), [Blogger](https://omnixri.blogspot.com/), [Medium](https://omnixri.medium.com/), [Hackmd](https://hackmd.io/@OmniXRI-Jack), [Github](https://github.com/OmniXRI) 各討論區中留言，老師會儘量協助，如有服務不週之處尚請見諒。**
