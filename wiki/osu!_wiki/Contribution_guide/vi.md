---
no_native_review: true
outdated_translation: true
outdated_since: 1c921bb312848bb2dce76217542281d0db5a6825
---

# Hướng dẫn đóng góp cho osu! wiki

Cảm ơn bạn đã quan tâm đến việc làm cho osu! wiki tốt hơn! Bài viết này nói về quá trình đóng góp từng bước một. Nếu như bạn đã làm quen với GitHub, hãy tự nhiên làm theo luồng "feature-branch" thông dụng để đề nghị sửa đổi và bỏ qua đến phần [Tự kiểm tra](#Tự kiểm tra).

Nếu bạn thắc mắc hay cần giúp đỡ ở bất cứ phần nào, hãy gửi một tin nhắn vào kênh `#osu-wiki` trong [osu!dev Discord](https://discord.gg/ppy).

## Bắt đầu

### Vị trí bạn muốn làm

Nếu bạn muốn đóng góp, nhưng lại không biết bắt đầu từ đâu, [Quản lý § Công việc thường ngày của osu! wiki](/wiki/osu!_wiki/Maintenance#routines) có những công việc cần được làm thường xuyên, và cách để giúp đỡ những người chỉnh sửa wiki. Để làm quen với định dạng chữ viết(độ dày, vị trí chữ viết, ...) dùng trên wiki, xem [Markdown Cheatsheet(Mẹo Markdown)](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) của Adam Pritchard.

## Chỉnh sửa wiki

*Xem tóm tắt quá trình đóng góp tại: [GitHub flow - GitHub Docs](https://docs.github.com/en/get-started/quickstart/github-flow)*

Các bài viết của osu! wiki được lưu trữ tại [GitHub][osu_wiki]. Các bước đóng góp như sau:

0. [Tạo](https://github.com/signup) một tài khoản GitHub.
1. Mở [`ppy/osu-wiki`][osu_wiki] repo và bấm `Fork` ở góc phải bên trên để tạo một bản sao của wiki có thể chỉnh sửa. Để quay lại fork của bạn, đi tới [`ppy/osu-wiki`][osu_wiki] và lại bấm `Fork`.

  - Nếu như bạn đã tạo một fork từ một thời gian trước, đồng bộ nó theo [Các gợi ý để làm công việc của bạn tốt hơn § đồng bộ fork](/wiki/osu!_wiki/Contribution_guide/Best_practices#syncing-the-fork).

4. Nếu bạn thấy gì đó tương tự bức ảnh phía dưới có nghĩa là bạn đã tạo một fork của `ppy/osu-wiki` repo và bạn đang ở fork của bạn.

  - [GitHub chỉnh sửa trên web](/wiki/osu!_wiki/Contribution_guide/GitHub_web-based_editor) (trực tuyến, không cần cài đặt).
  - [GitHub Desktop](/wiki/osu!_wiki/Contribution_guide/GitHub_Desktop) (không trực tuyến, có thể điều khiển nhiều thứ hơn).

## Tự kiểm tra

Khi bạn đã chỉnh sửa xong, hãy đọc thử tài liệu của bạn. Kiểm tra những điều sau:

- **Cảm xúc truyền tải**: các bài viết osu! wiki, trừ trường hợp đặc biệt, không được bộc lộ cảm xúc.
- **Bố cục và ngữ pháp**: bài viết phải rõ ràng, dễ hiểu, và không quá cao siêu cho người đọc. Lời nói của bạn phải rõ ràng, đi thẳng vào vấn đề và tránh phức tạp hoá vấn đề hoặc đột ngột kết thúc câu hay không có kết luận rõ ràng. Sử dụng phần mềm chỉnh sửa có tính năng sửa chính tả, ví dụ như [Google Docs](https://docs.google.com), để tìm ra lỗi đánh và ngữ pháp hoặc cú pháp lỗi.
- **[Sự đồng nhất nội dung](/wiki/Article_styling_criteria/Writing#content-parity)**: các bản dịch phải chứa nội dung giống nhau với bài viết gốc (sự thay đổi là cách chấm câu, diễn đạt, hay bố cục hiển nhiên được lường trước). Thay vì thay đổi nội dung của bản dịch, [mở một issue](https://github.com/ppy/osu-wiki/issues/new) hoặc bổ sung thêm một pull request cho pull request gốc nếu bạn cảm thấy chưa hoàn thiện, chưa chính xác, hoặc lỗi thời.
- **Bố cục và định dạng**: xem trước bài viết với những công cụ như [jbt's Markdown Editor](https://jbt.github.io/markdown-editor/) để chắc chắn nó nhìn như bạn muốn.
- **Tất cả hình ảnh và các phương tiện không phải chữ viết** phải dưới [1 megabyte](/wiki/Article_styling_criteria/Formatting#file-size). **Ảnh chụp màn hình** phải dùng skin mặc định của osu! và [những thiết lập cụ thể](/wiki/Article_styling_criteria/Formatting#screenshots-of-gameplay), bao gồm 1280x720 là độ phân giải cao nhất.

Những cách viết đặc biệt và định dạng chuẩn, tham khảo [cách viết tiêu chuẩn](/wiki/Article_styling_criteria). Đọc hết tất cả không được khuyến khích — một người đánh giá sẽ có thể chỉ ra nếu có gì đó cần được sửa lại.

## Pull request

After the changes are double-checked, committed, and pushed to your fork, you need to propose them to the wiki maintainers by opening a pull request:

   ![](img/fork-behind.jpg "Có vẻ không ổn \(branch của bạn bị lỗi thời\)")

   ![](img/fork-ahead-behind.jpg "Có vẻ không ổn \(branch của bạn bị lỗi thời kèm theo các commit của bạn\)")

3. Đây không phải vấn đề quá to tát, ***nếu*** bạn không sửa đổi các tệp đã bị sửa bời người khác.

4. Để xử lý vấn đề này, xem phần [Branch của tôi bị lỗi thời!](/wiki/osu!_wiki/Contribution_guide/Best_practices#syncing-the-fork) trong trang Các vấn đề hay gặp.

5. Sau khi hoàn thành bước 4, tiến tới [Sửa trực tuyến hoặc cục bộ](#sửa-trực-tuyến-hoặc-cục-bộ).

## Sửa trực tuyến hoặc cục bộ

Vào lúc này, bạn có hai lựa chọn:

- [Giao diện Web GitHub](/wiki/osu!_wiki/Contribution_guide/GitHub_web-based_editor) - sửa trực tuyến; đây là lựa chọn tốt nhất khi bạn chỉ sửa một bài viết.
- [GitHub Desktop](/wiki/osu!_wiki/Contribution_guide/GitHub_Desktop) - sửa cục bộ; đây là lựa chọn tốt nhất để sửa một và/hoặc nhiều bài viết (bao gồm đăng tải, xoá, và di chuyển ảnh cũng như các tệp khác).

*Chú ý: Bạn không bị giới hạn chỉ ở hai lựa chọn trên. Để giữ hướng dẫn này ngắn gọn và đơn giản, chúng tôi sẽ không đi sâu, hoặc không đề cập đến cách sử dụng các công cụ khác. Có nhiều ứng dụng bên thứ ba khác có thể thực hiện tương tự những gì mà Giao diện Web Github và GitHub Desktop có thể làm.*

**Khi bạn hoàn thành việc chỉnh sửa thông qua *Giao diện Web GitHub* hoặc *GitHub Desktop*, bạn có thể tiếp tục đi tới phần tiếp theo.**

## Hoàn thiện

### Tạo một pull request

1. Vào [repo `ppy/osu-wiki`](https://github.com/ppy/osu-wiki).

2. Nếu bạn đủ nhanh, bạn có thể thấy một biểu ngữ nền vàng.

   ![](img/github-recent.jpg)

3. Nếu bạn thấy nó, nhấn vào nút `Compare & pull request` (nhảy tới bước 8). Nếu không, bấm vào nút `New pull request` (tiếp tục tới bước 4).

4. Ở trang tiếp theo, nếu bạn thấy hai nút giống hình bên dưới, nhấn vào `compare across forks`.

   ![](img/compare-across-forks-no.jpg "Không ổn.")

5. Nhấn vào trình đơn thả xuống `head fork` và chọn cái có chứa tên người dùng của bạn (nó thường là cái thứ hai).

   ![](img/head-fork.jpg)

6. Nhấn vào trình đơn thả xuống `compare` và chọn branch mà bạn đã tạo (danh sách này được liệt kê bảng chữ cái).

   ![](img/compare-branch.jpg)

7. Nhấn `Create pull request`.

8. Nhập tiêu đề bằng tiếng Anh, giải thích ngắn gọn những gì mà bạn sửa đổi.

   Đối với các văn bản dịch, điền thêm mã ngôn ngữ hai chữ cái vào trong ngoặc ở đầu tiêu đề. Tiêu đề có thể chỉ cần đề cập tới các bài viết mà bạn dịch. Ví dụ, `[VI] Rules` sẽ chỉ ra bạn đang cập nhật bản dịch tiếng Việt của trang [Nội quy](/wiki/Rules).

9. Điền vào hộp mô tả khái quát những thay đổi của bạn. Bạn nên đề cập đến bất cứ thông tin gì liên quan đến pull request của bạn, như là tình trạng hoàn thành và những thứ mà bạn muốn các người đánh giá biết. Bạn cũng có thể làm cho pull request của bạn tự động đóng các issue (vấn đề) sau khi được merge (hợp nhất) bằng cách viết "resolves #1" hoặc "closes #1", v.v. trong mô tả (xem [Đóng issue bằng các từ khoá](https://help.github.com/articles/closing-issues-using-keywords/) trên GitHub Help).

10. Khi bạn sẵn sàng, nhấn `Create pull request`.

    ![](img/new-pull-request.png)

11. Xem [Review (Đánh giá)](#review-(đánh-giá)) và [Merge (Hợp nhất)](#merge-(hợp-nhất)) bên dưới.

### Review (Đánh giá)

Sau khi bạn tạo pull request, các biên tập viên khác của osu! wiki có thể đánh giá những thay đổi của bạn để giúp bạn phát hiện các lỗi mà bạn bỏ lỡ. **Bạn cần theo dõi các đánh giá này**, nếu không thì pull request của bạn có thể bị từ chối và đóng! Nếu bạn muốn ai đó đánh giá pull request của bạn, bạn có thể hỏi các biên tập viên osu! wiki khác ở kênh `#osu-wiki` trong [osu!dev Discord](https://discord.gg/ppy) hoặc ở phần bình luận trên GitHub.

### Merge (Hợp nhất)

Để những thay đổi của bạn hiển thị trên osu! wiki, pull request của bạn cần được hợp nhất. Sau khi pull request của bạn được đánh giá và chấp nhận, bạn có thể bình luận trên GitHub để nhờ ai đó merge, hoặc làm điều tương tự ở kênh `#osu-wiki` trong [osu!dev Discord](https://discord.gg/ppy), thay đổi của bạn sẽ mất lên tới 5 tiếng để xuất hiện trên osu! wiki.
