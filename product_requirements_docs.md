### How to write Product Requirements Docs

#### What is Product Requirements Docs(PRD)?

- What is the feature trying to achieve?
- Details of how the feature should work.

#### PRD sections
- Vision
  + Bạn thực sự muốn đạt được thành quả gì?
  + Exp: Tao thấy cái Landing Page này cùi quá, CRV quá thấp, 2%, tao muốn cải thiện và nâng nó lên 3%
- Background research
  + Trước khi bắt tay vào làm, bạn đã investigate cái gì?
  + Căn cứ voà đâu? có thể dựa vào user hearing/data/journey map
    +  Journey map khá hay, nên google để biết nó là gì nhoé 
  + Exp: 
    + Sau khi check log data, thì tao thấy user vào rồi thì scroll mỗi section đầu tiên
    + Hero section quá nhạt, xem 2s users quit rồi
    + Button để đi tới form đăng ký, để tận cuối trang, nên users phải scoll tận cuối mới thao tác được
- Goal & Non-goals
  + Muốn đạt được cái gì, scope như nào, rõ ràng, nói thẳng luôn là tao làm cái này để đạt được cái A, cái B chứ không phải là C, là D
  + Exp: 
    + Tao muốn nâng CRV của LP lên 3% -> tăng tỉ lệ new registration user
    + Chứ tao méo liên quan tới daily active user (DAU) or monthly active user (MAU)
- Metrics
  + Dùng metrics gì để đánh giá?
  + Được chia thành global metrics(toàn bộ product) vs local metrics (riêng function)
  + Exp: 
    + Global metrics: CRV
    + Local metrics: CRV cho các sections trong LP, cho các button, các link, các form
- Detailed design 
  + Specs rất sơ khai cho feature, có thể có prototype minh hoạ
  + Exp: LP rất quan trọng first view, nên tao sẽ dùng server-side rendering để render nhanh nhất có thể.
- Launch plan
  + Lúc release, chắc chắn 100% users méo biết tý gì về cái new feature mà bạn vừa dev vài tháng, nên làm sao để user biết?
  + Chia thành các phase release, ví dụ level 1 là 1/3 users, level 2 là 1/2 users, level 3 là all
  + Exp: 
    + Khi release globally sẽ rất risky, có thể drop CRV của toàn hệ thống xuống 0%
    + Nên plan là trước mắt release cho 1/3 japanese users, nếu thấy CRV được cải thiện, tiếp theo sẽ là 1/2 và globally
- Risk
  + List up lý do mà feature méo chạy như ý muốn
  + Có thể minh hoạ kiểu trade-off