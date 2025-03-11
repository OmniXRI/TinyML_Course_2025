# OmniXRI TinyML 小學堂 (2025) 

<span style="color:#FF0000;">**本課程完全免費，請勿移作商業用途！更多課程內容請參考文末教學資源連結。歡迎追蹤、留言、訂閱、點讚、轉發，讓更多需要的朋友也能一起學習。**</span>

## 1.課程緣起

去（2024）年受台大電機李宏毅老師在 Youtube 無私分享課程的感動，於是也在 Youtube 開了16週的免費網課「[OmniXRI's Edge AI & TinyML 小學堂](https://omnixri.blogspot.com/2024/02/omnixris-edge-ai-tinyml-0.html)」，期間受到大家熱烈迴響。今（2025）年為了更聚焦微型人工智慧(TinyML)，因此重新規畫了「TinyML 小學堂 2025」，預計將重點放在單晶片（微處理器/微控制器, Micro Controll Unit, MCU）的人工智慧應用上。

大家或許會覺得奇怪，當大部份人都在講生成式人工智慧(Generative AI, GenAI)或通用人工智慧（Artificial General Intelligence, AGI）才是未來時，為何要反其道而行推廣微型人工智慧或鑑別式人工智慧(Discriminative AI)呢？因為過去幾年，常有學校老師想推動基礎人工智慧應用實作課程時，卻沒有足夠的經費採購相關設備及開發工具，因此只能教授較基礎概念課程或者只採購幾套設備讓較優秀的學生製作專題參加比賽。

幸運地是，去年已有很多單晶片廠商推出自帶神經網路處理器(Neural Network Processing Unit, NPU)的晶片及開發板，且僅需花費一千台幣左右就能擁有帶有聲音、運動感測器、攝影機模組的開發板，這不僅有利於人工智慧基礎教育的推廣，更能讓傳統雲端型的智慧物聯網(AIoT)能更快轉型為邊緣型應用。

基於這個契機於是起心動念，想藉由這樣的開發板來推出一套完整課程，讓老師和學生們都能輕易上手，學習到完整的開發流程並建立起屬於自己的人工智慧應用，方便日後接觸中小型邊緣人工智慧(Edge AI)能更得心應手。

## 2.課程簡介

本課程定位為初階學習者，沒有太多人工智慧或程式基礎亦可學習。主要內容定位在如何使用 arm Cortex-M 系列單晶片及 Ethos-U 系列 MicroNPU 開發微型人工智慧應用。

前半段將依序從微型人工智慧簡介、單晶片基礎架構、機器學習與微型人工智慧基礎、硬體加速運算指令集、通用微控制器軟體介面標準、開發流程。若已熟悉基礎理論課程或不感興趣趣者，可直接跳過，待遇到不懂的地方再回頭學習即可。

後半段則以基礎案例實作為主，包括開發板介紹、常見聲音辨識、運動感測及簡易型視覺分類、物件偵測、姿態估測等應用。會依不同案例帶領大家如何使用各種開源工具來完成資料集建置、模型訓練、部署及推論測試，其中包括 Google Colab, TensorFlow Lite (TFLite), TensorFlow Lite for Microcontroller (TFLM/TFLu), Edge Impulse Studio, Roboflow, Seeed Studio SenseCraft AI等。

本課程主要使用開發板如下所示。老師並非產品代理商或商品代言人，僅方便教學使用，有需要者請自行上網到露天、蝦皮或其它代理商採購。

<img src="https://hackmd.io/_uploads/BypIweNsyx.jpg" alt="Seeed Xiao nRF52840 Sense" height="120">  
[Seeed Xiao nRF52840 Sense](https://wiki.seeedstudio.com/XIAO_BLE/)  

**註：Xiao nRF52840 Sense (Nordic nRF52840, arm Cortex-M4) 才有含數位麥克風及六軸運動感測器，Xiao nRF52840 不含任何感測器。**  

<img src="https://hackmd.io/_uploads/H1XwOxEskx.jpg" alt="Seeed Grove Vision AI Module V2" height="120">  
[Seeed Grove Vision AI Module V2 kit](https://wiki.seeedstudio.com/grove_vision_ai_v2/)  

**註：完整 kit 含 Seeed Grove Vision AI Module V2 (Himax WiseEye2 HX6538, arm Cortex-M55 + Ethos-U55), Raspberry Pi OV5647 Camera Module, Xiao ESP32C3。**  

**YOUTUBE 課程直播時間： 2025/3/12 ~ 2024/5/28，每週三晚上20：00 ~ 21：00，一小時課程（可視情況彈性延長半小時問答），共12週，視情況再加開進階課程。
所有直播內容結束後會保留在 YOUTUBE，如遇特殊狀況需調整上課時間或改成預錄播出會另行公告處理方式。**

## 3.講師簡介

![JackHsu](https://hackmd.io/_uploads/Hyll8QXi1l.png)  
**許哲豪 (Jack Hsu) 博士**

**連絡方式：**  
電子郵件： omnixri@gmail.com  

**個人簡介：**  
* [歐尼克斯實境互動工作室](https://omnixri.blogspot.com/)(OmniXRI Studio) 創辦人 (2017/11 ~ now)
* Facebook 【[Edge AI Taiwan邊緣智能交流區](https://www.facebook.com/groups/edgeaitw)】 社團創辦人 (2020/5 ~ now)
* Arm 開發者大使（台灣地區首位, 2024/10 ~ now）
* Intel 創新大使（台灣地區首位, 2023/5 ~ now）
* [MakerPRO](https://makerpro.cc/jack-hsu-column/), [vMaker](https://vmaker.tw/archives/category/%e5%b0%88%e6%ac%84/jack-omnixri)等單位Edge AI專欄作家
* 多家公司兼任技術/新創顧問

**專長：**  
機電整合、半導體封裝、電腦視覺、立體顯示、實境互動、人工智慧、智財技轉、新創輔導。

**經歷：**  
* 臺灣科技大學 資訊工程系 產碩專班 「人工智慧與邊緣運算實務」 兼任助理教授 (2021/2 ~ 2023/6)
* 開南大學 健康產業管理系 健康產業應用課程 「健康資料處理與分析」、「智慧醫療」 協同計畫主持人暨部份課程教學講師 (2022/9 ~ 2023/6)
* 開源人年會 Coscup 2023 【Open Edge AI & TinyML】 議程召集人 (2023/7)
* 2019 【Intel OpenVINO x Edge AI 創意應用競賽】 課程講師/活動顧問/競賽評審

**榮譽：**  
* 2024 [總統盃黑客松](https://www.president.gov.tw/News/28977)五強─「寧靜追蹤師」（技術支援）
* iThome 2021(13屆) 鐵人賽【Arm Platforms組】 冠軍
「[爭什麼，把AI和MCU摻在一起做tinyML就對了](https://ithelp.ithome.com.tw/2020-12th-ironman/articles/4855)」 （筆名：史蒂芬周）

## 4.課程大綱

本課程大綱為暫訂內容，部份課程內容和去(2004)年「[OmniXRI's Edge AI & TinyML 小學堂](https://omnixri.blogspot.com/2024/06/omnixris-edge-ai-tinyml-youtube.html)」類似，大家可先作預習，實際內容會隨課程展開後進行滾動式修正。實作課程會搭配特定的開發板，請自行準備。

所有課程簡報、範例、影片會於課後提供相關連結，並發佈到 FB Group, Blogger, Medium, Hackmd, Github 等媒體，方便大家透過自己習慣的管道學習。

* **<font color="#0000ff">2025/03/12</font> Ch_0 課程簡介**  
* **<font color="#0000ff">2025/03/12</font> Ch_1 微型人工智慧(TinyML)簡介**  
    1.1. 智慧物聯網與微型人工智慧  
    1.2. 常見應用  
    1.3. 常見開發板  
    1.4. 常見開發工具  
* **<font color="#0000ff">2025/03/19</font> Ch_2 單晶片基礎**  
    2.1. 硬體架構與分類  
    2.2. arm Cortex-M演進  
    2.3. 基本週邊控制  
    2.4. 即時作業系統  
* **<font color="#0000ff">2025/03/19</font> Ch_3 微型人工智慧基礎**  
    3.1. 數字系統  
    3.2. 機器學習算法(ML)  
    3.3. 卷積神經網路(CNN)  
    3.4. 循環神經網路(RNN)  
* **<font color="#0000ff">2025/04/02</font> Ch_4 arm 單晶片加速運算**  
    4.1. Thumb 指令集  
    4.2. DSP (SIMD) 指令集  
    4.3. Helium (MVE) 指令集  
    4.4. Ethos-U MicroNPU 
* **<font color="#0000ff">2025/04/09</font> Ch_5 通用微控制器軟體介面標準(CMSIS)**  
    5.1. CMSIS 基本介紹  
    5.2. CMSIS-Core  
    5.3. CMSIS-DSP  
    5.4. CMSIS-NN  
* **<font color="#0000ff">2025/04/16</font> Ch_6 TinyML開發流程**  
    6.1. 資料集建立  
    6.2. 模型選用與訓練  
    6.3. 模型轉換及優化  
    6.4. 模型部署與整合  
* **<font color="#0000ff">2025/04/23</font> Ch_7 實驗開發板介紹**  
    7.1. Arduino Nano 33 BLE Sense  
    7.2. Seeed Xiao nRF52840 Sense  
    7.3. Seeed Grove Vision AI Module V2 Kit  
    7.4. Seeed SenseCap Watcher  
* **<font color="#0000ff">2025/04/30</font> Ch_8 聲音辨識應用─環境音辨識  
    (Xiao nRF52840 Sense)**  
    8.1. TensorFlow Lite 開發環境建置  
    8.2. 聲音資料集建置  
    8.3. 模型選用與訓練  
    8.4. 模型部署與測試  
* **<font color="#0000ff">2025/05/07</font> Ch_9 運動感測器應用─手勢辨識  
    (Xiao nRF52840 Sense)**  
    9.1. Edge Impulse Studio 開發環境建置  
    9.2. 運資料集建置  
    9.3. 模型選用與訓練  
    9.4. 模型部署與測試  
* **<font color="#0000ff">2025/05/14</font> Ch_10 影像應用─影像分類  
    (Xiao Grove Vision AI V2 Kit)**  
    10.1. Seeed SenseCraft AI 開發環建置  
    10.2. 影像資料集建置  
    10.3. 模型選用與訓練  
    10.4. 模型部署與測試  
* **<font color="#0000ff">2025/05/21</font> Ch_11 影像應用─物件偵測  
    (Xiao Grove Vision AI V2 Kit)**  
    11.1. Edge Impulse 開發環建置  
    11.2. 影像資料集建置  
    11.3. 模型選用與訓練  
    11.4. 模型部署與測試  
* **<font color="#0000ff">2025/05/28</font> Ch_12 影像應用─姿態偵測  
    (Xiao Grove Vision AI V2 Kit)**  
    12.1. Himax SDK 開發環境建置  
    12.2. Yolov8n 姿態資料集與模型  
    12.3. 程式編譯  
    12.4. 模型部署與測試    
* **<font color="#0000ff">2025/06/04</font> Ch_13 雲端與邊緣整合應用 <font color="#ff0000">（暫訂）</font>**
    **<font color="#0000ff">(Seeed SenseCap Watcher)</font>**   

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
