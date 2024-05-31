Kiểm tra hiệu năng trang web
Mục tiêu:
•	Sử dụng jMeter để tạo một kịch bản kiểm tra mô phỏng người dùng truy cập trang web: https://codelearn.io/
•	Chạy kịch bản kiểm tra và ghi lại kết quả.
•	Phân tích kết quả kiểm tra, bao gồm thời gian phản hồi, số lượng yêu cầu thành công, số lượng yêu cầu thất bại, v.v.
•	Dựa trên kết quả phân tích, đưa ra kết luận về hiệu năng của trang web.
Kịch bản kiểm tra:
  Thread Group:
•	Số lượng thread: 100
•	Thời gian chạy: 60 giây = Ramp-up period: 10 giây HTTP Request:
•	URL: https://www.w3schools.com/
•	Method: GET
•	Content encoding: UTF-8 Listeners:
•	View Results Tree
•	Aggregate Report  
Kết quả kiểm tra:
 ![image](https://github.com/Vuthibichngoc212/BT_JMeter/assets/96900628/15f1b551-9158-4680-8ef4-2a18a7ebbb39)
![image](https://github.com/Vuthibichngoc212/BT_JMeter/assets/96900628/00b71064-4208-4e28-98bf-fe81b9b935bd)
![image](https://github.com/Vuthibichngoc212/BT_JMeter/assets/96900628/12947e3e-14f7-42c3-8290-11d6e1bbaf99)

Kết luận:
	Trang web https://codelearn.io/ có hiệu năng tốt. Số lượng yêu cầu thành công rất cao (100%), số lượng yêu cầu thất bại rất thấp (0,00%). Thời gian phản hồi trung bình, trung vị và percentil 90 đều ở mức thấp (dưới 100 ms). Chuyển tải của trang web cũng khá cao (12 yêu cầu/giây).

