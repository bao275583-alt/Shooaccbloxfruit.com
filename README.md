<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<title>Shop Acc Blox Fruit</title>

<style>
body {
  font-family: Arial;
  background: #f2f2f2;
  margin: 0;
}

/* Header */
.header {
  background: #fff;
  padding: 15px;
  text-align: center;
  font-weight: bold;
  border-bottom: 1px solid #ccc;
}

/* Card sản phẩm */
.card {
  background: #fff;
  margin: 15px;
  padding: 15px;
  border-radius: 10px;
  box-shadow: 0 0 5px rgba(0,0,0,0.1);
}

.title {
  font-weight: bold;
  margin-bottom: 10px;
}

.stock {
  display: inline-block;
  background: purple;
  color: white;
  padding: 5px 10px;
  border-radius: 5px;
  margin-bottom: 10px;
}

.price {
  color: #00aaff;
  font-size: 20px;
  margin-bottom: 10px;
}

/* Nút */
.buttons {
  display: flex;
  gap: 10px;
}

.btn {
  flex: 1;
  padding: 10px;
  border: none;
  border-radius: 8px;
}

.detail {
  background: #ddd;
}

.buy {
  background: #007b8f;
  color: white;
}
</style>

</head>

<body>

<div class="header">🔥 SHOP ACC BLOX FRUIT 🔥</div>

<!-- Sản phẩm -->
<div class="card">
  <div class="title">ACC BLOX FRUIT - GODHUMAN + SKULL GUITAR</div>
  <div class="stock">Kho hàng: 1</div>
  <div class="price">70.000đ</div>

  <div class="buttons">
    <button class="btn detail">Chi tiết</button>
    <button class="btn buy" onclick="alert('Liên hệ Zalo để mua')">MUA NGAY</button>
  </div>
</div>

<div class="card">
  <div class="title">LEVEL MAX + GODHUMAN + KITSUNE</div>
  <div class="stock">Kho hàng: 1</div>
  <div class="price">80.000đ</div>

  <div class="buttons">
    <button class="btn detail">Chi tiết</button>
    <button class="btn buy" onclick="alert('Liên hệ Zalo để mua')">MUA NGAY</button>
  </div>
</div>

<div class="card">
  <div class="title">CDK + SKULL GUITAR + TRÁI KITSUNE</div>
  <div class="stock">Kho hàng: 1</div>
  <div class="price">90.000đ</div>

  <div class="buttons">
    <button class="btn detail">Chi tiết</button>
    <button class="btn buy" onclick="alert('Liên hệ Zalo để mua')">MUA NGAY</button>
  </div>
</div>

</body>
</html>
