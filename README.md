# touching_detection
# 【智慧生活】─觸碰偵測
### NTUST CS5149701 人工智慧與邊緣運算實務 期末專題 DEMO
學號 : M11007319 <br>姓名 : 莊士頡

---

## 摘要說明
本系統為解決騷擾事件發生時，被害者會因為慌亂、恐懼等等負面情緒影響，抑或是事件過後才察覺不舒服，而未能在第一時間保存證據。

本系統利用了MediaPipe Pose、MediaPipe Multiple Hands結合了一Binary classification模型， 建構2 stage的多人動作辨識器，主要任務為辨識是否有人觸碰使用者，如果判定觸碰事件發生則觸發錄影並儲存影片，以此作為騷擾事件判斷依據。
