<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>금왕설렁탕 주문</title>
</head>
<body>
  <h1>금왕설렁탕 주문</h1>
  <p>전통적인 설렁탕을 제공합니다.</p>
  <h2>메뉴</h2>
  <ul>
    <li>설렁탕: 11,000원</li>
  </ul>
  <h2>주문하기</h2>
  <form>
    <label for="quantity">수량:</label>
    <button type="button" id="decrement">-</button>
    <input type="number" id="quantity" min="1" max="10" value="1">
    <button type="button" id="increment">+</button>
    <br>
    <label for="address">주소:</label>
    <input type="text" id="address">
    <br>
    <label for="name">이름:</label>
    <input type="text" id="name">
    <br>
    <label for="phone">연락처:</label>
    <input type="text" id="phone">
    <br>
    <input type="submit" value="주문하기">
  </form>
  <p>주문이 완료되면 총 금액이 표시됩니다.</p>
  <p>주문 내역은 연락처로 문자메시지를 보냅니다.</p>
</body>
</html>
