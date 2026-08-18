# Baru-AI — bản phát hành

Công cụ tạo video AI hàng loạt.

## Cài

1. Tải **`Baru-AI.exe`** ở mục [Releases](../../releases) về — để đâu cũng được.
2. Chạy nó. App hỏi **cài vào đâu**; chọn ổ còn nhiều chỗ, ví dụ `D:\Baru-AI`.
   App tự chép mình sang đó và tạo lối tắt ngoài Desktop.
3. Lần đầu app hiện bảng **Chuẩn bị** và tự tải:
   - **Engine** ~3,6 GB (Python + ComfyUI + thư viện)
   - **Model** ~37 GB (lõi AI, tải thẳng từ HuggingFace)

   Tải một lần, đứt mạng thì bấm lại là nối tiếp chỗ dở.
4. Nhập mã bản quyền admin cấp.

Từ lần sau mở bằng lối tắt ngoài Desktop. File tải về lúc đầu xoá được.

## Máy cần gì

- Windows, card **NVIDIA từ 8 GB VRAM**
- Khoảng **45 GB trống** trên ổ chọn cài
- Không cần cài Python

## Mọi thứ nằm chung một chỗ

Thư mục cài chứa hết: app, engine, model, kho ảnh/video và thành phẩm.
Muốn gỡ thì xoá đúng thư mục đó là sạch.

## Cập nhật

Tải `Baru-AI.exe` bản mới rồi chạy — app tự thay bản cũ ở nơi đã cài,
không phải cài lại từ đầu, không mất engine hay model.

## Lưu ý

Đừng chơi game trong lúc render — GPU bị chia phần thì một clip chậm thêm
khoảng 5 phút.
