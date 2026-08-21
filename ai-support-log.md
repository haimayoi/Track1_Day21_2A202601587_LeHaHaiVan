# AI Support Log

| # | Bước | AI dùng để làm gì | Bạn kiểm chứng kết quả thế nào |
|---|---|---|---|
| 1 | Grid/dataset | Gợi ý 24 scenario và metadata | Đối chiếu corpus; giữ pending tới team review. Team đã review xong |
| 2 | Rubric/routing | Formalize blocker và tuyến chấm | Đối chiếu output contract và evaluator. Team đã đối chiếu |
| 3 | Code checks | Viết check scope enum/follow-up | Chạy test offline và output thật. Team đã chạy lại với output thật |
| 4 | Judge prompt | Làm rõ deixis, adversarial, false-pass | So confusion matrix trên cùng dev set |
| 5 | Report | Dựng quyết định và placeholder | Chỉ thay TBD bằng số từ evidence |
