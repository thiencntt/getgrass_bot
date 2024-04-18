# Quét mã QR để tham gia nhóm giao lưu

![image](https://github.com/ymmmmmmmm/getgrass_bot/assets/51306299/36b45b13-fe65-4c5f-80f5-ea83aebecf01)

# getgrass_bot

Mở tập tin main.py để sửa user_id và danh sách sock5 ở gần cuối tập tin
Nếu không sử dụng proxy thì chạy tập tin no_proxy.py

### Liên kết lời mời

[https://app.getgrass.io/register/?referralCode=igL12FvaVTjLZyP](https://app.getgrass.io/register/?referralCode=igL12FvaVTjLZyP)

### Cách lấy user_id

1. Đăng nhập và trang https://app.getgrass.io/dashboard

2. Nhấn F12 để mở bảng và chọn thẻ Console sau đó nhập mã (Gõ bằng tay chứ Chrome không cho copy dán)

`localStorage.getItem('userId')`

Những gì được in là user_id của người dùng hiện tại.

![0001](https://github.com/ymmmmmmmm/getgrass_bot/assets/51306299/31d0e16e-df2f-443a-a141-910d16052ed9)

Nếu bạn không biết sửa mã nguồn, vui lòng sử dụng phiên bản có giao diện (tập tin ui.py)

![3333](https://github.com/ymmmmmmmm/getgrass_bot/assets/51306299/80e18c1f-da5d-40d4-a361-3506b44c6602)

# CÁCH CHẠY BOT

Mở CMD và cài đặt các gói cần thiết để chạy
`pip3 install websockets_proxy`
`pip3 install loguru`

Chạy tập tin nào thì CD đến thư mục có tập tin và chạy lệnh 
`python tentaptin.py`
