# Tài liệu ShutterBug

Tài liệu hướng dẫn sử dụng và quản trị plugin ShutterBug.

## Xem trước trên máy cục bộ

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

Mở `http://127.0.0.1:8000/` để xem Wiki trên máy.

## Xuất bản

Quy trình GitHub Actions được thiết lập sẵn sẽ tự động xây dựng Wiki bằng MkDocs và đưa phiên bản hoàn chỉnh lên GitHub Pages thông qua nhánh `gh-pages`.

Sau khi lần đầu xuất bản thành công, hãy bật GitHub Pages trong phần cài đặt của kho lưu trữ:

- Nguồn: Triển khai từ nhánh
- Nhánh: `gh-pages`
- Thư mục: `/`

Sau đó, thêm địa chỉ Wiki đã xuất bản vào tệp cấu hình của plugin ShutterBug:

```yml
guide-url: 'https://kernel-person.github.io/shutterbug-docs/'
```
