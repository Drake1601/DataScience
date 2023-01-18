# DataScience
Load data from mongodb to postgreSQL:
  - Mở pgadmin 4 ( link trong docker container )
  - Đăng nhập với tài khoản admin@admin.com, mật khẩu admin
  - Nhấn vào server rồi chọn register server
  - đặt tên cho server rồi chuyển sang tab connection
  - phần hostname/address điền địa chỉ ip address của postgres
    - Để lấy được ip của postgres thì:
    - Mở cmd gõ docker ps (sẽ hiện ra id của các container )
    - gõ tiếp docker inspect abcd (abcd là mấy chữ đầu của id của cái postgres ở trên )
    - lấy địa chỉ ip address ở đấy 
   - phần user password đều điền test1
   - chọn save 
   - sau đấy chạy theo file notebook mongo2postgre để connect vào database để đọc,ghi dữ liệu
    
