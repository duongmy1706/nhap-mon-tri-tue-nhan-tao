# P-HUBcode

P-HUBcode là một dự án minh họa và so sánh hiệu suất giữa hai thuật toán duyệt đồ thị: **BFS (Breadth-First Search)** và **DFS (Depth-First Search)**.  
Chương trình cho phép mô phỏng, đo thời gian chạy, vẽ đồ thị, và phân tích đường đi từ một đỉnh nguồn đến đỉnh đích.

---

## Công nghệ sử dụng

- **Ngôn ngữ lập trình**: Python 3.x  
- **Thư viện**:
  - `networkx`: Xử lý cấu trúc và thuật toán đồ thị.
  - `matplotlib`: Vẽ và trực quan hóa đồ thị.
  - `collections`: Cấu trúc dữ liệu hỗ trợ (deque).
  - `time`: Đo thời gian thực thi thuật toán.
- **Môi trường phát triển**:
  - Jupyter Notebook (`.ipynb`)
  - Python script (`.py`)
  - (Tùy chọn mở rộng): Google Colab / Streamlit

---

## Giải thích cách hoạt động

### `demo.py`
- Chạy thử nghiệm thuật toán BFS và DFS trên các đồ thị định nghĩa sẵn.
- Các chức năng chính:
  - Đo thời gian chạy BFS và DFS.
  - So sánh hiệu suất giữa hai thuật toán.
  - Tìm đường đi từ điểm đầu đến điểm đích.
  - Tính tổng trọng số đường đi (với đồ thị có trọng số).
  - Vẽ đồ thị bằng `networkx` và tô màu đường đi được tìm thấy.

### `lab2.ipynb`
- Giao diện tương tác trong notebook để:
  - Trình bày lý thuyết đồ thị, ví dụ cụ thể.
  - Phân tích và giải thích thuật toán từng bước.
  - Thử nghiệm các trường hợp mẫu (đồ thị mẫu 6, mẫu 7...).
  - So sánh thời gian thực thi BFS & DFS trên các đồ thị lớn hơn.
  - Có hỗ trợ hình ảnh trực quan và biểu đồ.

---

## 🖥️ Kết quả Local

### Hình ảnh minh họa kết quả thuật toán chạy trên máy cục bộ:

![Output Local](2bce698f-64f5-4ce8-b99a-3038a081c7bf.png)

- Hình vẽ minh họa đường đi tìm được bằng thuật toán BFS hoặc DFS.
- Các cạnh có trọng số rõ ràng.
- Đường đi nổi bật bằng màu cam hoặc đỏ.

---

## Kết quả Web

- File `lab2.ipynb` có thể chạy mượt trên:
  - Google Colab
  - JupyterLab / Jupyter Notebook
- (Tùy chọn mở rộng) Có thể tích hợp `Streamlit` để xây dựng giao diện Web tương tác.
