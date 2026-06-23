# TOEIC Flashcard One File v3

Bản này chỉ cần 1 file index.html.

## Chức năng mới
- Xóa thư mục tự tạo.
- Import từ vựng bằng file Excel (.xlsx/.xls/.csv).
- Có template Excel mẫu: toeic_vocab_import_template.xlsx.

## Cột Excel hỗ trợ
- English: bắt buộc
- Korean
- Vietnamese
- Topic
- Part of speech
- Folder

Nếu thiếu cột Folder, từ sẽ được thêm vào thư mục đang chọn trong web app.

## Cách cập nhật lên GitHub Pages
1. Giải nén file ZIP.
2. Lấy file index.html mới.
3. Vào repository GitHub cũ.
4. Upload file index.html mới để thay file cũ.
5. Commit changes.
6. Chờ 1-3 phút rồi mở lại link GitHub Pages.

## Lưu ý
Chức năng import Excel dùng thư viện SheetJS qua CDN. Lần đầu dùng cần có internet.
