
BT.01  
```
Tình huống:
Giả sử bạn đang làm việc với một hệ thống nhận diện vân tay, hệ thống này yêu cầu một người dùng đăng ký vân tay của mình vào cơ sở dữ liệu và sau đó xác nhận lại khi muốn truy cập vào một hệ thống. 

Số người dùng trong cơ sở dữ liệu: 100 người.
Số bản ghi vân tay hợp lệ trong cơ sở dữ liệu: 100 bản ghi (mỗi người có 1 bản ghi vân tay).
Số thử nghiệm kiểm tra xác thực: 1000 lần thử nghiệm (bao gồm cả thử nghiệm hợp lệ và không hợp lệ).

Trong số 1000 thử nghiệm:
- Có 950 lần thử nghiệm là của người dùng hợp lệ.
- Có 50 lần thử nghiệm là của người không hợp lệ.
- Trong số 950 lần thử nghiệm hợp lệ, có 20 lần bị từ chối không hợp lệ (False Rejections).
- Trong số 50 lần thử nghiệm không hợp lệ, có 5 lần bị chấp nhận sai (False Acceptances).

Câu hỏi:
- False Rejection Rate (FRR): Tính tỷ lệ bị từ chối sai (FRR).
- False Acceptance Rate (FAR): Tính tỷ lệ chấp nhận sai (FAR).
```


BT.02   
```
Cho các số đo:
Accuracy (Độ chính xác / xác thực:  TP + TN / TP + TN + FP + FN) =	0.85
Precision (Tính đúng: TP/ TP+FP) =	0.85
Recall (Độ nhạy: TPR = TP/TP+FN)	= 0.83

Và số lượng: FP=7, FN=8

Tính TP, TN

```
