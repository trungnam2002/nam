echo "# nam" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/trungnam2002/nam.git
git push -u origin main 
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>Web Test</title>
</head>
<style>
.nav
{
   display: flex; 
 
   background-image: linear-gradient(to right, purple, pink); /*Từ trái tới phải */
  justify-content: space-between;
  position: fixed;  
  width: 100%;
  margin-top: 0;
}
.nav-item
{
  list-style: none; /* không có dấu tròn đen ở list item */
   display: inline-block;  /*các item hiện trên 1 dòng theo từng khối item  */
  color: white;
  font-size: 17px;
 text-align: center;   /* thêm cho chắc ăn */
 margin: auto 15px; /*auto là chiều dọc giữ nguyên, 10px là margin chiều ngang trái phải 10px */

}
.nav-list
{
 padding-left: 0px; /* lúc đầu padding của item lệch sang phải 40px nên phải padding left 0px  */
}
.chaomung
{
  font-size: 17px;
  font-family:Verdana, Geneva, Tahoma, sans-serif;
 margin-right: 120px;
}
body
{
  height: 1500px;
}


</style>

  
  <body>
    <!-- Navbar -->
    <div class="nav">
<ul class="nav-list">
  <li class="nav-item">Giới thiệu</li>
  <li class="nav-item">Kết nối</li>
  <li class="nav-item">Tải ứng dụng</li>
</ul>
<ul class="nav-list">
  <li class="nav-item chaomung">Chào Mừng Đến Với Trang Của Nam</li>
  
</ul>
<ul class="nav-list">
  <li class="nav-item">Đăng kí</li>
  <li class="nav-item dangnhap">Đăng nhập</li>
  
</ul>
    </div>
 
  </body>
    
</html>
