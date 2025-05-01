# OmniXRI TinyML 小學堂 (2025) 【第 8 講】 聲音辨識應用─環境音辨識

<img src="https://raw.githubusercontent.com/OmniXRI/TinyML_Course_2025/refs/heads/main/images/2025_TinyML%E5%B0%8F%E5%AD%B8%E5%A0%82%E8%AA%B2%E7%A8%8B%E7%9B%B4%E6%92%AD%E5%9C%96%E7%A4%BA_Ch8.JPG" alt="" width="640">  

<span style="color:#FF0000;">**本課程完全免費，請勿移作商業用途！更多課程內容請參考文末教學資源連結。歡迎追蹤、留言、訂閱、點讚、轉發，讓更多需要的朋友也能一起學習。**</span>

**課程直播日期： 2025/04/30**  
**課程直播連結： https://youtu.be/xXD8g-BXriU**  
**課程簡報名稱： 20250430_TInyML_Course_Ch08_OmniXRI_Jack.pdf**  

## 課程內容

8.1. 喚醒詞偵測簡介  
* 喚醒詞偵測  
* 案例分享 ─ 聲控電風扇  
    [正確示範（美女版）](https://www.youtube.com/shorts/X8yJjRj7Uus)  
    [錯誤示範（阿媽版）](https://www.youtube.com/shorts/xlz1m2Cp3IY)  
    [正確示範（台灣國語）](https://youtu.be/vpZgt0VQf8Y)  
* 案例分享 ─ 2024 總統盃黑客松卓越團隊  

8.2. 聲音資料集建置  
* 感測器類比/數位信號互換  
* 常見錄音裝置  
* Xiao nRF52840 Sense 模組 ─ 參考電路  
* 聲音訊號─取樣、量化  
* 常見聲音訊號波形（時間域） 
* 特徵提取 ─ 時間域、頻率域轉換  
* 特徵提取 ─ 線性頻譜、梅爾倒頻譜表示法  
* [Google Speech Commands 公開資料集](https://www.tensorflow.org/datasets/catalog/speech_commands)  
* [ESC-50 環境音公開資料集](https://github.com/karolpiczak/ESC-50)  
* [Google AudioSet 聲音公開資料集](https://research.google.com/audioset/)  
* 自定義語音命令錄音技巧  
* [聲音分割開源工具 Audacity](https://www.audacityteam.org/)  
* Edge Impulse 連續信號自動分割工具  

8.3. TensorFlow Lite模型訓練  
* TinyML 開發流程選項  
* 深度學習模型聲音分類  
* 關鍵詞偵測(KWS) 特徵提取  
* Arduino 新增開發板設定  
* 安裝Seeed nRF52840函式庫  
* 指定工作開發板及埠號  
* Xiao nRF52840 Sense 語音辨識  
* Aruino 預安裝模組  
* 啟動 Google Colab 模型訓練範例  
* 修正 Colab 範例訓練參數  
* Colab 開始執行模型訓練  
* Colab 完成模型訓練  

8.4. Arduino 模型部署與測試  
* 更新函式庫  
* NO Code 測試結果  
* Arduino 2.0 快速(增量)編譯  

## 參考文獻

[1] 許哲豪，臺灣科技大學資訊工程系「人工智慧與邊緣運算實務」（2021~2023）  
https://omnixri.blogspot.com/p/ntust-edge-ai.html  

[2] 許哲豪，OmniXRI's Edge AI & TinyML 小學堂 Youtube 直播課程總結  
https://omnixri.blogspot.com/2024/06/omnixris-edge-ai-tinyml-youtube.html  

[3] 許哲豪，歐尼克斯實境互動工作室系列發文─TinyML(MCU AI)系列  
https://hackmd.io/1PK1URhIQ7GutcWgpgsWbg#TinyMLMCU-AI%E7%B3%BB%E5%88%97  

[4] 許哲豪，如何讓 Arduino 2.0 快速編譯（增量編譯）  
https://omnixri.blogspot.com/2024/10/arduino-20.html  

## 延伸閱讀  

* Seeed, Xiao nRF52840 Sense – Embedded ML - Speech Recognition on Seeed Studio XIAO nRF52840 Sense  
https://wiki.seeedstudio.com/XIAO-BLE-Sense-TFLite-Mic/  

* Github, lakshanthad / tflite-micro-arduino-examples  
https://github.com/lakshanthad/tflite-micro-arduino-examples  

* Google, Colab Example - train_micro_speech_model.ipynb  
https://colab.research.google.com/github/tensorflow/tflite-micro/blob/main/tensorflow/lite/micro/examples/micro_speech/train/train_micro_speech_model.ipynb  

* Google, Speech Commands  
https://www.tensorflow.org/datasets/catalog/speech_commands  

## 教學資源

OmniXRI 系列文章：  
https://omnixri.blogspot.com/p/blog-page_19.html  

OmniXRI Youtube 教學影片頻道：  
https://www.youtube.com/@omnixri1784/videos  

OmniXRI Github 課程簡報及相關範例：  
https://github.com/OmniXRI/TinyML_Course_2025

---
**註：本課程非學校正式課程，現僅有老師一人，沒有教學助理可幫忙，如操作上有相關問題，請於[Youtube](https://www.youtube.com/@omnixri1784/featured), [FB Group](https://www.facebook.com/groups/edgeaitw), [Blogger](https://omnixri.blogspot.com/), [Medium](https://omnixri.medium.com/), [Hackmd](https://hackmd.io/@OmniXRI-Jack), [Github](https://github.com/OmniXRI) 各討論區中留言，老師會儘量協助，如有服務不週之處尚請見諒。**
