<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Trang Web Server</title>
    <style>
        body {
            margin: 0; /* Loại bỏ margin mặc định của body */
            font-family: Arial, sans-serif; /* Font chữ cơ bản */
        }
        /* Định dạng cho logo */
        .logo {
            position: absolute;
            top: 10px; /* Cách viền trên 1cm (10px ~ 1cm trên màn hình tiêu chuẩn) */
            right: 10px; /* Cách viền phải 1cm */
        }
        /* Định dạng cho menu */
        .menu {
            position: absolute;
            top: 10px; /* Cách viền trên 1cm */
            left: 10px; /* Cách viền trái 1cm */
            background-color: #f4f4f4; /* Màu nền của menu */
            padding: 10px;
            border-radius: 5px; /* Bo góc nhẹ */
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.2); /* Đổ bóng nhẹ */
        }
        .menu ul {
            list-style-type: none; /* Bỏ dấu đầu dòng */
            padding: 0;
            margin: 0;
            max-height: 150px; /* Giới hạn chiều cao để tạo thanh cuộn */
            overflow-y: auto; /* Tạo thanh cuộn dọc khi nội dung vượt quá */
        }
        .menu li {
            padding: 8px;
            cursor: pointer;
        }
        .menu li:hover {
            background-color: #ddd; /* Hiệu ứng khi di chuột qua */
        }
    </style>
</head>
<body>
    <!-- Logo ở góc trên cùng bên phải -->
    <img src="logoanh.jpg" alt="Logo" class="logo" width="100" height="100">

    <!-- Menu ở góc trên cùng bên trái -->
    <div class="menu">
        <ul>
            <li>Giới thiệu server</li>
            <li>Thông tin server</li>
            <li>Thành viên server</li>
            <li>Hình ảnh server</li>
        </ul>
    </div>
</body>
</html>
