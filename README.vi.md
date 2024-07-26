# Vietnamese Accent Recognition
[![en](https://img.shields.io/badge/lang-en-blue.svg)](https://github.com/TUT888/VietnameseAccentRecognition/blob/main/README.md)
[![vi](https://img.shields.io/badge/lang-vi-red.svg)](https://github.com/TUT888/VietnameseAccentRecognition/blob/main/README.vi.md)

Đề tài: Nhận dạng âm thanh vùng miền bằng phương pháp học sâu <br>

## Project Description

Dự án được chạy trên `Google Colab`, bao gồm các phần:
- Đọc dữ liệu âm thanh và trích xuất đặc trưng bằng MFCC (Mel Frequency Cepstral Coefficients)
- Sử dụng 2 loại mô hình để huấn luyện và dự đoán: CNN (Convolutional Neural Network) và RNN (Recurrent Neural Network)

## Dataset
- Dữ liệu được sử dụng trong dự án có nguồn gốc từ tập dữ liệu Vietnamese Common Voice được cung cấp bởi Mozilla. Mozilla bắt đầu dự án Common Voice nhằm tạo ra một cơ sở dữ liệu miễn phí cho mọi người phát triển các phần mềm nhận dạng giọng nói. Hiện nay, Mozilla đã phát triển các tập dữ liệu (datasets) với nhiều loại ngôn ngữ, trong đó có cả tiếng Việt. **Chi tiết tại**: [Mozilla Common Voice](https://commonvoice.mozilla.org/en/datasets)
- Dự án sử dụng một phần của bộ dữ liệu Common Voice Corpus 9.0 được cập nhật vào ngày 27/04/2022. Dữ liệu tải về chứa các file ghi âm giọng nói của nhiều người ở nhiều độ tuổi và vùng miền khác nhau, kèm theo file excel chứa thông tin câu nói tương ứng với từng file ghi âm.

## Files in repository
- File vietnamese_accent_recognition.ipynb: file Jupyter Notebook của dự án
- File audio_record_details.xlsx: file Excel lưu thông tin của các file ghi âm
- Folder audio_records: chứa các file ghi âm giọng vùng miền.
  
## Authors
Dự án được thực hiện bởi nhóm gồm 2 thành viên:
- Tất Uyển Tâm [Github](https://github.com/TUT888)
- Dương Thủy Tiên [Github](https://github.com/tienduong-21)
