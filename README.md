# APIDataTDMUNote

# LẤY DANH SÁCH BÀI VIẾT MỚI NHẤT

http://localhost:3000/api/news


# LẤY DANH SÁCH BÀI VIẾT THEO CHUYÊN MỤC
http://localhost:3000/api/news?cat=9

- `cat` là id chuyên mục, theo bảng bên dưới

Tin tổng hợp:         9

Công đoàn - Đoàn TN:  12

Tin đào tạo:          13

Hợp tác đối ngoại:    16

Nghiên cứu Khoa học:  21

# LẤY DANH SÁCH BÀI VIẾT TỪ VỊ TRÍ
http://localhost:3000/api/news?cat=10

- Lấy danh sách bài viết bắt đầu từ vị trí thứ 10 (nhỏ nhất 1)


# XEM CHI TIẾT BÀI VIẾT
http://localhost:3000/api/news/{CAT_NAME}|{ID_NAME}

- Xem chi tiết bài viết, {CAT_NAME} và {ID_NAME} lấy từ danh sách sách bài viết

VD:

{CAT_NAME} = 'tin-dao-tao'

{ID_NAME} = 'nhung-nganh-hoc-moi-dap-ung-nhu-cau-lao-dong-cong-nghe-ky-thuat-cao-1'

http://localhost:3000/api/news/tin-dao-tao|nhung-nganh-hoc-moi-dap-ung-nhu-cau-lao-dong-cong-nghe-ky-thuat-cao-1

