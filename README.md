# Test-CI-CD
chào mừng đến với quy trình CI/CD devops
1. kiểm soát phiên bản
 - Phần quan trọng của CI / CD là hệ thống kiểm soát phiên bản để quản lý mã . Ngoài ra, tôi cần một dịch vụ lưu trữ kho lưu trữ mà các bước xây dựng và triển khai của chúng tôi sẽ gắn liền với nó. sử dụng git
 
2. tạo ứng dụng
 - Trong phần này, ta sẽ tạo một ứng dụng Spring Boot đơn giản để tham gia vào quá trình này. Chúng tôi cũng sẽ sử dụng Maven làm công cụ xây dựng của mình.
 
3. đẩy lên
 - Cho dù sử dụng Spring Initializr hay tạo dự án theo cách thủ công, tôi hiện đã sẵn sàng cam kết và đẩy các thay đổi của mình vào kho lưu trữ của  tôi.
    git add .
    git commit -m 'Initialize application'
    git push
4. Tự động hóa xây dựng
 - Một phần khác của quy trình CI / CD là một dịch vụ sẽ xây dựng và kiểm tra mã được đẩy của tôi. tôi sẽ sử dụng Travis CI ở đây, nhưng bất kỳ dịch vụ xây dựng nào cũng sẽ hoạt động.
 
 5. 

