HTML

<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>العريفي ماركت</title>
<style>
body{font-family:Arial;background:#f3f4f6;margin:0;color:#222}
header{background:#123d32;color:white;text-align:center;padding:25px}
header h1{margin:0}
nav{background:#fff;padding:15px;text-align:center}
main{padding:15px}
.search{width:95%;padding:12px;border:1px solid #ddd;border-radius:8px}
.products{display:grid;grid-template-columns:repeat(2,1fr);gap:12px;margin-top:20px}
.product{background:white;padding:12px;border-radius:10px;text-align:center}
.product img{width:100%;height:110px;object-fit:contain}
button{background:#137b54;color:white;border:0;padding:10px;border-radius:7px;width:100%}
footer{text-align:center;padding:20px;color:#666}
</style>
</head>
<body>
<header>
<h1>العريفي ماركت</h1>
<p>تسوق بسهولة وأمان</p>
</header>
<nav>الرئيسية | المنتجات | سلة المشتريات</nav>
<main>
<input class="search" placeholder="ابحث عن منتج...">
<h2>منتجاتنا</h2>
<div class="products">
<div class="product">
<h3>منتج تجريبي</h3>
<p>السعر: 1000 ريال يمني</p>
<button>إضافة للسلة</button>
</div>
</div>
</main>
<footer>جميع الحقوق محفوظة © العريفي ماركت</footer>
</body>
</html>
