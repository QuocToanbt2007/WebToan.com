
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Với Bố Cục Yêu Cầu</title>
    <style>
		h1{
			display: none;
			}
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom, #add8e6, #ffffff); /* Xanh dương nhạt sang trắng */
        }
        .header {
            padding: 20px;
            text-align: center;
            background-color: #add8e6; /* Xanh dương nhạt */
            font-size: 2em;
            font-weight: bold;
            color: #333;
        }
        .content-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
        }
        .text-section {
            flex: 1;
            margin: 10px;
        }
        .image-section {
            flex: 1;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        img {
            max-width: 100%;
            max-height: 300px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .footer {
            background-color: #add8e6; /* Xanh dương nhạt */
            padding: 20px;
            text-align: center;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        table, th, td {
            border: 1px solid #ccc;
        }
        th, td {
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #add8e6; /* Màu xanh dương nhạt */
        }
		p {text-indent: 30px; /* Lùi đầu dòng 30px */
            font-family: 'Patrick Hand', sans-serif; /* Sử dụng phông Patrick Hand */
            font-size: 20px;               /* Kích thước chữ */
            color: #00008B;               /* Màu chữ hồng dễ thương */}
    </style>
</head>
<body>

    <!-- Tiêu đề trang -->
    <div class="header"> NGUYỄN KHÁNH QUỐC TOẢN</div>

    <!-- Hình bên trái cùng hàng với văn bản -->
    <div class="content-container">
        <div class="image-section">
            <img src="https://s.net.vn/mXj7" alt="Hình ảnh bên trái">
        </div>
        <div class="text-section">
            <h2>Giới thiệu bản thân </h2>
            <p>
                Xin chào các bạn, mình là Quốc Toản. Hiện tại mình học lớp 12 chuyên lý tại trường THPT Chuyên Bến Tre, mình cũng không biết vì sao hồi lớp 9 mình thích môn lý. Có thể vì sự tò mò của mình và sự thú vị từ các hiện tượng vật lý. Qua 2 năm học, mình cũng cảm thấy để chinh phục vật lý không chỉ mỗi sở thích mà còn là năng khiếu. Tuy không còn mặn mà với lý nữa nhưng mình cũng rất cố gắng để hoàn thành việc học chuyên lý trên lớp. Mình hy vọng trong tương lai mình sẽ được làm việc trong môi trường nghệ thuật và sáng tạo. Vì đó là lợi thế cho người thuộc cung sư tử và số chủ đạo 7 như mình. Họ thích sáng tạo, nghệ thuật và trải nghiệm.
			</p>
   
        </div>
    </div>
    <!-- Footer với bảng -->
    <div class="footer">
        <h2>THÔNG TIN CÁ NHÂN </h2>
        <table>
            <thead>
                <tr>
                    <th>Chiều cao</th>
                    <th> Cân nặng</th>
                    <th>Số điện thoại</th>
                    <th>Email</th>
                    <th>Cung hoàng đạo</th>
                    <th>Nickname</</th>
                    <th>liên hệ facebook</th>
                </tr>
            </thead>
            <tbody>
                <!-- 2 hàng -->
                <tr>
                    <td>1,79m </td>
                    <td>66 kg</td>
                    <td>0912487242</td>
                    <td>quoctoanbt2007@gmail.com</td>
                    <td>Sư Tử</td>
                    <td>Phúc Luân</td>
                    <td><a href="https://s.net.vn/kOrN">Phúc Luân</a></td>
                </tr>
            </tbody>
        </table>
    </div>

</body>
</html>
