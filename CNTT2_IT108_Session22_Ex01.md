# Bài 1: Tìm kiếm tài liệu học tập chính thống bằng Google

## 1. Chuỗi truy vấn (Query)

```
"giáo trình nhập môn công nghệ thông tin" filetype:pdf site:ptit.edu.vn -site:scribd.com -site:123docz.net
```

(Nếu trường mình không phải PTIT thì thay `ptit.edu.vn` bằng tên miền của trường.)

## 2. Giải thích từng toán tử

| Toán tử | Tác dụng |
|---|---|
| `"..."` | Chỉ hiện kết quả có đúng cụm từ này, không bị lẫn bài viết lung tung |
| `filetype:pdf` | Chỉ lấy file PDF |
| `site:ptit.edu.vn` | Chỉ tìm trên máy chủ của trường |
| `-site:scribd.com` `-site:123docz.net` | Loại 2 trang web "rác" hay hiện ra (bắt nạp tiền, đăng ký, nhiều quảng cáo) |

## 3. Vì sao dùng `filetype:` tiết kiệm thời gian hơn gõ "tải sách..."?

- Gõ "tải sách..." thì Google trả về cả trang quảng cáo, bài blog, trang bắt đăng ký, mình phải mở từng cái để kiểm tra.
- Dùng `filetype:pdf` thì kết quả đầu tiên đã là file PDF luôn, bấm vào là đọc được, không phải lọc thủ công.
- Kết hợp thêm `site:` thì tài liệu lấy từ nguồn của trường nên chính thống, không lo mã độc hay phiên bản sai.

## 4. Ảnh chụp màn hình

> *(Dán ảnh chụp 3 kết quả đầu tiên sau khi gõ "Combo toán tử" vào đây. Nhớ che thông tin cá nhân nếu có.)*

![3 kết quả đầu tiên](anh_bai1.png)
