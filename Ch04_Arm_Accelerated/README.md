# OmniXRI TinyML 小學堂 (2025) 【第4講】arm 單晶片加速運算

<img src="https://raw.githubusercontent.com/OmniXRI/TinyML_Course_2025/refs/heads/main/images/2025_TinyML%E5%B0%8F%E5%AD%B8%E5%A0%82%E8%AA%B2%E7%A8%8B%E7%9B%B4%E6%92%AD%E5%9C%96%E7%A4%BA_Ch4.JPG" alt="" width="640">  

<span style="color:#FF0000;">**本課程完全免費，請勿移作商業用途！更多課程內容請參考文末教學資源連結。歡迎追蹤、留言、訂閱、點讚、轉發，讓更多需要的朋友也能一起學習。**</span>

**課程直播日期： 2025/04/02**
**課程直播連結： https://youtu.be/TYyz88IhGd8**
**課程簡報名稱： 20250402_TInyML_Course_Ch04_OmniXRI_Jack.pdf**

## 課程內容

4.1. 常見硬體加速手法  
* 神經網路基本計算量  
* 為什麼要加速？  
* 硬體加速手法 ─ 提高工作時脈  
* 硬體加速手法 ─ 平行/向量指令集加速  
* 硬體加速手法 ─ 多核心加速  
* 硬體加速手法 ─ NPU神經網路加速器  

4.2. DSP (SIMD) 指令集  
* 常見 Arm 晶片CPU等級及指令集  
* arm Cortex-M 指令集（v6m, v7m)  
* arm Cortex-M 指令集（v8m)  
* 基本乘法指令 MUL  
* 基本乘加指令 MLA  
* 常見 SIMD 並行指令  
* SIMD 飽和加法指令 QADD  
* 浮點運算指令  

4.3. Helium (MVE) 指令集  
* Cortex-M 指令加速操作比較  
* Cortex-M 指令集與加速計算  
* Cortex-M55 工作流水線  
* Cortex-M55 雙節拍工作模式  
* DSP / Helium 指令集比較  

4.4. Ethos-U MicroNPU  
* arm Micro NPU  
* Ethos-U55 系統架構圖  
* Ethos-U55 可支援算子及操作  
* Ethos-U55 開發流程  

## 參考文獻

[1] 許哲豪，NTUST Edge AI 人工智慧與邊緣運算實務  
https://omnixri.blogspot.com/p/ntust-edge-ai.html  

[2] 許哲豪，OmniXRI's Edge AI & TinyML 小學堂 Youtube 直播課程總結  
https://omnixri.blogspot.com/2024/06/omnixris-edge-ai-tinyml-youtube.html  

[3] 許哲豪，OmniXRI系列發文─TinyML(MCU AI)系列  
https://hackmd.io/1PK1URhIQ7GutcWgpgsWbg#TinyMLMCU-AI%E7%B3%BB%E5%88%97  

[4] 許哲豪，歐尼克斯實境互動工作室系列發文─TinyML(MCU AI)系列  
https://hackmd.io/1PK1URhIQ7GutcWgpgsWbg#TinyMLMCU-AI%E7%B3%BB%E5%88%97  

[5] Wiki – ARM Cortex-M  
https://zh.wikipedia.org/wiki/ARM_Cortex-M  

[6] 許哲豪，MCU攜手NPU讓tinyML邁向新里程碑  
https://omnixri.blogspot.com/2022/10/mcunputinyml.html  

[7] 許哲豪，誰說單晶片沒有神經網路加速器NPU就不能玩微型AI應用？  
https://omnixri.blogspot.com/2024/01/vmaker-edge-ai-13-npuai.html  

[8] Arm Cortex-M & Ethos-U55 ML開發者指南  
https://hackmd.io/@OmniXRI-Jack/arm_developer_cortexm55_ethosu55_guide  

[9] Arm Cortex-M55 處理器介紹  
https://armkeil.blob.core.windows.net/developer/Files/pdf/white-paper/arm-cortex-m55-processor-wp-tw.pdf  

## 教學資源

OmniXRI 系列文章：  
https://omnixri.blogspot.com/p/blog-page_19.html  

OmniXRI Youtube 教學影片頻道：  
https://www.youtube.com/@omnixri1784/videos  

OmniXRI Github 課程簡報及相關範例：  
https://github.com/OmniXRI/TinyML_Course_2025

---
**註：本課程非學校正式課程，現僅有老師一人，沒有教學助理可幫忙，如操作上有相關問題，請於[Youtube](https://www.youtube.com/@omnixri1784/featured), [FB Group](https://www.facebook.com/groups/edgeaitw), [Blogger](https://omnixri.blogspot.com/), [Medium](https://omnixri.medium.com/), [Hackmd](https://hackmd.io/@OmniXRI-Jack), [Github](https://github.com/OmniXRI) 各討論區中留言，老師會儘量協助，如有服務不週之處尚請見諒。**
