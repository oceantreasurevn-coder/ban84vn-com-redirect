# ban84vn.com → ban84.vn

Trang chuyển hướng của tên miền cũ **ban84vn.com** sang tên miền chính **ban84.vn** (từ 13/10/2026).

- GitHub Pages phục vụ `ban84vn.com` từ repo này (tệp `CNAME`, bật Enforce HTTPS).
- Mỗi trang cũ có một tệp riêng cùng đường dẫn (`index.html`, `ai-meetup.html`, `chu-de/*.html`, `bai/*.html`…):
  trả về 200, `meta refresh` 0 giây + `canonical` tới đúng URL mới trên ban84.vn (Google coi là chuyển hướng vĩnh viễn).
- Đường dẫn khác rơi vào `404.html`: JavaScript chuyển sang cùng đường dẫn trên ban84.vn (không có JavaScript thì về trang chủ).
- Khi site chính có trang mới, không cần thêm gì ở đây: 404.html vẫn chuyển đúng đường dẫn.
- Nội dung trang thật nằm ở repo `oceantreasurevn-coder/ban84vn.com` (tên miền `ban84.vn`).
- Email `Infor@ban84vn.com` không đổi: DNS của ban84vn.com vẫn giữ MX và SPF.
