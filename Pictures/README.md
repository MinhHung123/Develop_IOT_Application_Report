# Thư mục Hình Ảnh (Pictures Folder)

Đây là thư mục dành cho lưu trữ tất cả hình ảnh, sơ đồ, và biểu đồ sử dụng trong báo cáo.

## Cấu trúc tổ chức

```
Pictures/
├── Task1/          # Hình ảnh liên quan đến Task 1: LED Blink
├── Task2/          # Hình ảnh liên quan đến Task 2: NeoPixel
├── Task3/          # Hình ảnh liên quan đến Task 3: LCD Display
├── Task4/          # Hình ảnh liên quan đến Task 4: Web Server
├── Task5/          # Hình ảnh liên quan đến Task 5: TinyML
├── Task6/          # Hình ảnh liên quan đến Task 6: CoreIOT
├── Hardware/       # Ảnh các thành phần phần cứng
├── Diagrams/       # Sơ đồ kiến trúc, FSM, flow charts
├── Results/        # Ảnh kết quả thử nghiệm, biểu đồ
└── Screenshots/    # Ảnh màn hình giao diện
```

## Hướng dẫn sử dụng hình ảnh trong LaTeX

Để chèn hình ảnh vào báo cáo, sử dụng lệnh:

```latex
\begin{figure}[H]
    \centering
    \includegraphics[width=0.7\textwidth]{Pictures/folder/image.png}
    \caption{Mô tả hình ảnh}
    \label{fig:ten_hinh}
\end{figure}
```

## Định dạng file được hỗ trợ
- PNG (.png)
- JPG/JPEG (.jpg, .jpeg)
- PDF (.pdf)
- EPS (.eps)

## Lưu ý
- Đặt tên file rõ ràng, tránh khoảng trắng
- Sử dụng tiếng Anh hoặc số cho tên file
- Nén ảnh trước khi upload để giảm dung lượng
