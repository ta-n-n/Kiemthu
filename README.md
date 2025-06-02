# Thực hành kiểm thử tự động End-to-End với Cypress

- **Họ tên:**Vũ Thiện Tân
- **MSSV:** BIT22047


---

##  Các kịch bản kiểm thử

### 1. Đăng nhập thành công
- **User:** `standard_user`
- **Password:** `secret_sauce`
-  Kiểm tra chuyển hướng tới `/inventory.html`



### 2. Đăng nhập thất bại
- Nhập thông tin sai → kiểm tra thông báo lỗi.



### 3. Thêm sản phẩm vào giỏ hàng
- Nhấn "Add to cart" → kiểm tra số lượng giỏ hàng = 1




### 4. Xóa sản phẩm khỏi giỏ hàng
- Nhấn "Remove" → kiểm tra badge biến mất


### 5. Sắp xếp sản phẩm theo giá
- Chọn "Price (low to high)" → xác minh sản phẩm giá thấp nhất đứng đầu.



### 6. Quy trình thanh toán
- Thêm sản phẩm → điền thông tin khách hàng:
  - First Name: John
  - Last Name: Doe
  - Zip Code: 12345
- Nhấn "Continue" → kiểm tra điều hướng đến `/checkout-step-two.html`.
- Ảnh chụp màn hình kết quả chạy kiểm thử nằm ở : cypress\e2e\screenshots

