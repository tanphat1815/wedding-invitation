# Mẫu Thiệp Mời Đám Cưới React.js

Đây là mẫu thiệp mời cho lễ cưới.  
Nếu bạn thích hoặc sử dụng kho lưu trữ này, hãy nhớ Star và Fork nhé😉

## Xem Trước Mẫu

### Thiệp Mời Đám Cưới
![Preview](./Preview.gif)

## Nội dung và chức năng có trong mẫu
- Hiển thị ngày cưới, địa điểm và lời chào
- Album ảnh
- Nơi để gửi tiền mừng (Hỗ trợ sao chép số tài khoản vào clipboard)
- Chức năng chia sẻ qua KakaoTalk và chia sẻ liên kết

## Hướng dẫn sử dụng Thiệp Mời Đám Cưới v1

Hãy chỉnh sửa phần `<Head>` trong `./src/pages/index.tsx` cho phù hợp.

```html
<meta content="○○○❤○○○ mời bạn đến dự lễ cưới" name="Title" />
<meta content="Ngày ○○○○ năm ○○ tháng ○○ thứ ○○, lúc ○○ giờ ○○ phút sáng" name="Description" />
<meta content="Ngày ○○○○ năm ○○ tháng ○○ thứ ○○, lúc ○○ giờ ○○ phút sáng" name="Keyword" />
<meta property="og:title" content="○○○❤○○○ mời bạn đến dự lễ cưới" />
<meta property="og:description" content="Ngày ○○○○ năm ○○ tháng ○○ thứ ○○, lúc ○○ giờ ○○ phút sáng" />
<meta property="og:url" content="https://kyuhyuk.kr/wedding-invitation" />
<meta name="theme-color" content="#BCAAA4" />
```

Chỉnh sửa `./src/data.json` để sử dụng.

```json
{
  "date": "Ngày 01 tháng 01 năm 1970, thứ Năm lúc 12 giờ 00 phút sáng",
  "location": "○○○ Wedding, tầng ○, sảnh ○○",
  "greeting": "Chúng tôi đã xây dựng tình yêu qua những ánh nhìn âu yếm,\nGiờ đây, chúng tôi muốn biến tình yêu này thành một tình yêu sâu đậm hơn, bằng cách cùng nhau nhìn về một hướng và bước đi bên nhau.\nChúng tôi sẽ trân trọng và gìn giữ tình yêu này dưới tên gọi tình yêu.\nRất mong nhận được sự chúc phúc cho con đường phía trước của chúng tôi.",
  "groom": {
    "name": "○○○",
    "account_number": "Ngân hàng ○○ ***-***-******",
    "parents": {
      "mother": {
        "name": "○○○",
        "account_number": "Ngân hàng ○○ ***-***-******"
      },
      "father": {
        "name": "○○○",
        "account_number": "Ngân hàng ○○ ***-***-******"
      }
    }
  },
  "bride": {
    "name": "○○○",
    "account_number": "Ngân hàng ○○ ***-***-******",
    "parents": {
      "mother": {
        "name": "○○○",
        "account_number": "Ngân hàng ○○ ***-***-******"
      },
      "father": {
        "name": "○○○",
        "account_number": "Ngân hàng ○○ ***-***-******"
      }
    }
  },
  "kakaotalk": {
    "api_token": "",
    "wedding_invitation_url": "",
    "share_image": ""
  }
}
```
