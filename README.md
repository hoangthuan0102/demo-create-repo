# demo-create-repo
First repo
+ Tuần 1 ngày 11/09/2020
    - Lệnh git config (dùng để set user name và email)
    ```
        git config --global user.name "hoangthuan"
        git config --global user.email "thuanlh0102@gmail.com"
    ``` 
    - Lệnh git init (dùng để Khởi tạo 1 git repository 1 project mới hoặc đã có)
    ```
        git init
    ```
    - Lệnh git clone (dùng để khởi tạo 1 git repository 1 project mới hoặc đã có)
    ```
        git clone https://github.com/hoangthuan0102/demo-create-repo.git
    ```
    - Lệnh git add (dùng để thêm thay đổi đến stage/index trong thư mục làm việc)
    ```
        touch test.html
        git add test.html
    ```
    - Lệnh git commit (dùng để commit thay đổi từ đầu)
    ```
        git commit -m "note thay đổi"
    ```
    - Lệnh git status (dùng để hiển thị danh sách thay đổi của files được thêm hoặc commited)
    ```
        git status
    ```
    - Lệnh git push (dùng để gửi thay đổi tới master branch của repositorys)
    ```
        git push
    ```