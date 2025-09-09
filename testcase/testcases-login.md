# Test Cases - Login

| Test Case ID | Mô tả | Input | Expected Result |
|--------------|-------|-------|-----------------|
| TC01 | Login với đúng username & password | user=admin, pass=123456 | Login thành công, chuyển vào Dashboard |
| TC02 | Login sai password | user=admin, pass=wrong | Thông báo "Sai mật khẩu" |
| TC03 | Username rỗng | user="", pass=123456 | Hiện cảnh báo "Vui lòng nhập username" |
| TC04 | Password rỗng | user=admin, pass="" | Hiện cảnh báo "Vui lòng nhập password" |
| TC05 | Nhập username đặc biệt | user="!@#", pass=123456 | Hiện cảnh báo "Sai định dạng" |
