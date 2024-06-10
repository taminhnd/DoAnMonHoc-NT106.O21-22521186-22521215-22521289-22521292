# Đồ án Network Tamper
## Các thành viên
1. 22521186 - Phạm Minh Quân
2. 22521215 - Nguyễn Văn Quốc
3. 22521289 - Vũ Bá Tài
4. 22521292 - Nguyễn Đinh Minh Tâm
## Các tính năng
### Bắt gói tin
  - Mục DeviceIA và DeviceIB chứa danh sách tất cả những giao diện mạng của máy, người dùng có thể chọn 1 giao diện mạng trong danh sách.<br>
  - Khi bấm vào nút "Start Capture", phần mềm sẽ tiến thành bắt gói tin từ giao diện mạng đã chọn ở mục DeviceIA.<br>
  (Lưu ý: Phải chọn đủ cả DeviceIA và DeviceIB để sử dụng chức năng này)<br> 
  - Gói tin bắt được sẽ được hiển thị dưới dạng danh sách. Thông tin hiển thị được bao gồm số thứ tự, địa chỉ IP nguồn và đích, cổng nguồn và cổng đích, địa chỉ MAC nguồn và đích.<br>
  - Khi bấm vào nút "Stop Capture", phần mềm sẽ dừng việc bắt gói tin lại.<br>
  - Ngoài ra, người dùng có thể nhấp đúp chuột vào 1 gói tin để xem thông tin chi tiết hơn của gói tin đó.<br>
### Lưu, tải, xóa gói tin và xuất danh sách gói tin
  - Nhấp vào 1 gói tin, sau đó bấm vào nút "Save Packet", khi đó cửa sổ chọn thư mục sẽ hiện lên, người dùng chọn thư mục muốn lưu gói tin và bấm Save để hoàn thành quá trình lưu.<br>
  - Bấm vào nút "Load Packets" sẽ hiện lên cửa sổ chọn thư mục, chọn 1 gói tin muốn tải lên phần mềm và bấm Open. Tập tin vừa được chọn sẽ được hiển thị ở danh sách tập tin ở bên dưới.<br>
  - Nhấp vào 1 gói tin, sau đó bấm vào nút "Delete", gói tin được chọn sẽ bị xóa khỏi danh sách.<br>
  - Bấm vào nút "Export" sẽ hiện lên cửa sổ chọn thư mục, chọn thư mục muốn lưu gói tin và bấm Save, phần mềm sẽ xuất ra file có chứa thông tin của tất cả các tập tin trong danh sách.<br>
### Gửi gói tin
  - Người dùng nhập đầy đủ thông tin về địa chỉ IP nguồn và đích, cổng nguồn và đích muốn chỉnh sửa vào 4 ô tương ứng.<br>
  - Bấm vào nút "Send Captured Packet", các gói tin sẽ được gửi đi bằng giao diện mạng DeviceIB với thông tin đã được chỉnh sửa.<br>
### Lọc gói tin hiển thị
  - Ở ô "Search" người dùng nhập các cú pháp để lọc gói tin muốn xem.<br>
  - Các cú pháp như sau:<br>
    - ip addr = <địa chỉ IP> <br>
    - ip src = <địa chỉ IP nguồn> <br>
    - ip des = <địa chỉ IP đích> <br>
    - ip port = <cổng> <br>
    - ip psrc = <cổng nguồn> <br>
    - ip pdes = <cổng đích> <br>
### Link video demo: 
https://drive.google.com/file/d/1fPxXMPS1k7ajF791gONUQXLI2bglCxnA/view?usp=sharing
