## 運用人工智慧於空拍影像之車輛識別
### 實驗環境
- 硬體設備:空拍機DJI Mavic 2 -> 蒐集訓練的資料集
- labelImg -> 影像車輛標註
- Google Colab -> 進行訓練
- Python、OpenCV、Darknet -> 神經網路框架
![image](https://github.com/jui-pung/VehicleRecognition_YOLO/labelImg_process.png)
### 專案實踐結果
- 以YOLOv3結合車輛的空拍影像資料集，使用物件偵測演算法訓練在空拍影像中，車輛的辨識能力
- 蒐集與拍攝400張車輛空拍影像，訓練、驗證資料依8:2比例隨機區分
- mAP:0.8314
### Reference
https://medium.com/ching-i/yolo-c49f70241aa7
https://mropengate.blogspot.com/2018/06/yolo-yolov3.html
