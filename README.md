# Mô tả:
- Chương trình dùng để chuyển đổi folder zip chứa các ảnh jpg sang mảng byte để sử dụng trên vi điều khiển
- Cú pháp:
  ```
  python main.py path_to_file_zip output_filename.h
  Ex: python main.py ./video_jpg_files.zip video01.h
  ==> Đọc tất cả các file jpg trong video_jpg_files.zip và tạo một file header chứa các mảng byte của mỗi ảnh jpg
  ```
