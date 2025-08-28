## link data: [link](https://drive.google.com/file/d/1nxR07ebVNc5bSgfTQjeUcAoyoaNuuH6s/view)
### comment
  + đây là bài toán dựa vào đoạn text đầu dự đoán ra nhãn là positive, hay negative.
  + Các bước xử lí, labelencode để đưa nhãn về 0, 1. Transform tập train, dùng tfidfvectorize với feature = 10000, sau đó sử dụng các mô hình học máy để dự đoán.
  + Báo cáo độ chính xác của mô hình:
     - Decision tree: 0.715
     - Random forest: 0.8428
     - Adaboost: 0.766
     - Gradient boost: 0.796
     - Xgboost: 0.846
