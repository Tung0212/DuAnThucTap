# Django Blog Website
Website Tùng Blog
================

*** Các chức năng chính của blog
   + CRUD blog
   + Custom user
   + Đăng ký
   + Xác thực thông qua tên người dùng cộng với email
   + Quản lý hồ sơ cá nhân
   + Lọc blog theo các tiêu chí khác nhau (tiêu đề, danh mục, thẻ)
   + Tìm kiếm blog theo các tiêu chí khác nhau
   + Thích blog
   + Bình luận và trả lời trên blog
   + Theo dõi hủy theo dõi người dùng khác
   + Hệ thống thông báo

Cách sử dụng
=================

- Đầu tiên tải và cài đặt python
- Sau đó cài đặt môi trường ảo để sử dụng

    $ pip install virtualenv
    
- Bây giờ tạo môi trường ảo của riêng mình để chạy.

     $ virtualenv venv_name

- Sau khi tạo, truy cập vào trong venv_name/Scripts để chạy lệnh activate
    

    $ cd venv_name/Scripts
    $ activate
    $ cd ../../
    
    
- Bây giờ qua trở lại thư mục gốc và cài đặt các gói packages đã khai báo sắn trong file requirement.txt 

    $ pip install -r requirements.txt
    
Well your environment is ready now.

- Sau đó khởi tạo db và user đầu tiên cho việc truy cập

    $ python manage.py migrate
    $ python manage.py createsuperuser

- Sau khi đã hoàn thành các công đoạn cài đặt, ta chạy sự án

    $ python manage.py runserver
    
- Bây giờ mở website trên địa chỉ locahost::8000 để truy cập blog.



______________________________THANK_________________________________

