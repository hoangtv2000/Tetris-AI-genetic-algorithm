# Ứng dụng thuật giải di truyền vào game xếp hình Tetris

**Abstract.** Tetris là trò chơi tiêu chuẩn cho những nghiên cứu về Trí tuệ nhân tạo và Máy học. Bài viết của chúng tôi
đầu tiên sẽ giới thiệu khái quát về trò chơi Tetris. Tiếp theo là lược sử hình thành và phát triển của các
thuật toán áp dụng, qua đó là những thách thức mới. Từ những tài liệu nghiên cứu tiền nhiệm, chúng tôi
nhận thấy Approximate dynamic programming (quy hoạch động thích nghi), Genetic algorithms (giải
thuật di truyền) và Reinforcement learning (học tăng cường) đã góp phần tạo nên những giải pháp hiệu
quả. Học hỏi từ các công trình tiền nhiệm, chúng tôi quyết định xây dựng một thuật toán A.I với chiến
lược tham lam (greedy stralegy) với một hàm đánh giá meta-heuristic. Số điểm (score) đạt được sẽ đánh
giá độ hiệu quả của thuật toán này, nó tương ứng với những hàng đã xóa. Và nếu thuật toán của chúng
tôi đủ tốt, nó có thể tiến tới vô hạn. Trên thực tế, chúng tôi đã triển khai thuật toán này trên game Tetris
có bàn cờ kích thước 22x10, với độ khó tăng dần và chưa có dấu hiệu thua cuộc. 

**Keywords**: genetic algorithm, artificial intelligence, bfs algorithm

## File báo cáo
[Ứng dụng giải thuật di truyền vào game xếp hình Tetris](https://github.com/hoangtv2000/Tetris-AI-genetic-algorithm/blob/main/AI_Project.pdf)

## Hướng dẫn sử dụng
Clone project này về máy tính của bạn và mở file **index.html**, chương trình sẽ xuất hiện trên nền web. 

Nhấn nút **Run AI** để bật/tắt chế độ AI.

Nhấn nút **Reset** để đặt bàn cờ về trạng thái ban đầu.

**Preview**


![plot](https://github.com/hoangtv2000/Tetris-AI-genetic-algorithm/blob/main/preview.png?raw=true)
