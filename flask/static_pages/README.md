# Flask 정적 페이지 로딩 예제
Flask를 이용한 정적 페이지 로딩 예제

[Flask 설치]
1. sudo apt-get install python-virtualenv
2. mkdir myproject
3. cd myproject
4. virtualenv env
5. source env/bin/activate
6. pip install Flask

[디렉토리 구조]
.
├── README.md
├── app.py
├── env
│   ├── bin
│   │   ├── activate
├── static
│   ├── images
│   │   └── default.gif
│   ├── print.css
│   └── style.css
└── templates
    └── hello.html

[실행]
python app.py
