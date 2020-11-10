# demo-create-repo
+ Tuần 1 ngày 09/11/2020
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
    - ls -la (hiển thị thông tin rõ ràng hơn)
    ```
        ls -la
    ```
+ Tuần 1 ngày 10/11/2020
    - Untrackerd (Một tập tin mới được tạo thì sẽ ở trạng thái Untracked)
    ```
        touch faq.html
        git status
    ```
    - Tracked (để đưa tập tin từ untracked về tracked thì)
    ```
        git add faq.html
        git status
    ```
    - Chuyển tập tin từ tracked về untracked 
    ```
        rm faq.html
        git status
    ```
    - Tạo branch
    ```
        git branch issue1
    ```
    - Xem danh sách branch (có dấu * là branch hiện tại)
    ```
        git branch
    ```
    - Chuyển đổi branch 
    ```
        git checkout issue1
    ```
    - Tạo branch mới và checkout
    ```
        git checkout -b issue2
    ``` 
    - Xóa branch
    ```
        git branch -d issue1
    ```