# Nodejs - Express

# Bước 1:
- npm init (Khởi tạo project nodejs)
- npm i express --save (Cài đặt express)
- npm i nodemon --save-dev (Cài đặt nodemon)

# Bước 2:
- Cấu hình package.json "start": "nodemon --inspect index.js",
- Thêm file .gitignore (/node_modules/)
- npm i morgan --save-dev (Cài đặt morgan) -- Hiển thị khi request
- npm i express-handlebars --save (Cài đặt express-handlebars template engine)

# Bước 3:
- Bố trí cấu trúc
- src
    - index.js
    - resource/
        - scss/
        - views/  
            - layouts/
                - main.hbs
            - home.hbs
            - news.hbs
            - partials
                - header.hbs
                - footer.hbs

# Bước 4:
- Cấu hình static files
- npm i node-sass --save-dev (Cài đặt node-sass)
- Cấu hình scss -> Public css - "watch": "node-sass --watch src/resources/scss/app.scss src/public/css/app.css",
