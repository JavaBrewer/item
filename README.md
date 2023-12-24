<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>상품 페이지</title>
</head>
<body>

    <!-- 이미지와 스티커를 담은 컨테이너 -->
    <div class="product-container">
        <!-- 상품 이미지 -->
        <a href="https://example.com">
            <img class="product-image" src="https://via.placeholder.com/400" alt="상품 이미지">
        </a>

        <!-- 스티커로 표시된 특가, 할인 정보 -->
        <div class="sticker-container">
            <span class="sticker">특가</span>
            <span class="sticker">hit</span>
            <span class="sticker free-shipping">무료 배송</span>
        </div>
    </div>

</body>
</html>

---

<style>
        /* 스타일링을 위한 CSS 코드 */
        .product-container {
            text-align: center; /* 가운데 정렬 */
        }

        .product-image {
            max-width: 100%; /* 이미지가 부모 요소에 맞게 크기 조절 */
            height: auto; /* 비율 유지 */
        }

        .sticker-container {
            margin-top: 10px; /* 스티커와 이미지 사이 여백 조절 */
        }

        .sticker {
            display: inline-block;
            padding: 5px 10px;
            background-color: #ff0000; /* 배경색 설정 */
            color: #ffffff; /* 글자색 설정 */
            font-size: 12px; /* 글자 크기 설정 */
            margin-right: 1px; /* 오른쪽 여백 설정 */
        }

        .free-shipping {
            background-color: #009900; /* 배경색 설정 */
        }
    </style>
