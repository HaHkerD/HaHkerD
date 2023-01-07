### Hi there 👋
**TÔi SẼ GIỚI THIỆU CÁCH CÀI PHẦN MỀN QUẢN LÝ NHÂN SỰ**

## Phần mền cần thiết
Visual Studio 2022

SQL Server 2014 Management Studio(có thể phiên bản mới hơn)

## Cách cài đặt

Giải nén file tải về

Chạy file SQLQuery1.sql trên SqlServer

Mở file BTL.sln trong Visual Studio 2022(tệp BTL.sln trong file QLNhanVien)

Thay đổi ConnectionString tại file App.config
![image](https://user-images.githubusercontent.com/122134341/211126480-3463bdd6-5740-4e6a-a932-d18d52720f69.png)
bằng cách vô view>Server Explorer>Conncect to Database(như hình ở dưới)

![image](https://user-images.githubusercontent.com/122134341/211126780-2c1a47ad-d3e6-46aa-badf-7d08b21ae69a.png)

Nhập Tên Server và Database name Bấm thử Test Connection nếu nó kết nối thất bại xem nhập lại thông tin bước bày còn thành công thì ấn ok
Vào Advanced... copy link dưới khung Datasource

![image](https://user-images.githubusercontent.com/122134341/211127223-315daeb5-4738-4a68-9109-dc288cd0175f.png)

thay connectionString="Data Source=SIEULANG-PC;Initial Catalog=BTL;Integrated Security=True" ở file App.config thành connectionString=""(Ctrl + V vào giữa "")

run Start để chạy chương trình


<!--
**HaHkerD/HaHkerD** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
