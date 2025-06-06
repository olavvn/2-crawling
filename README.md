# 2-crawling
크롤링 실습을 위한 레포지토리입니다.

## 제출 방법

1. 자신의 깃허브 아이디로 브랜치 만든 다음에 개인 폴더 만들어주세요.
2. 작업 하시고 커밋 후 오리진으로 푸시해주시면 됩니다.
3. main 으로 풀리퀘 날려주시면 됩니다. merge 는 하시면 안돼요! 풀리퀘 제목 : 2-crawling_[이름]

### 예시

```bash
git clone git@github.com:gdgoc-usaibility/2-crawling.git  # 클론
cd 2-crawling # 프로젝트 루트로 이동
git checkout -b olavvn # 브랜치 생성 (본인의 브랜치, 폴더 등 생성)
mkdir olavvn # 개인 폴더 만들기
cd olavvn # 개인 폴더로 이동
# dynamic-crawling 디렉토리의 파일을 복사해서 개인 폴더에 붙여넣고고 작업을 진행해주세요
git add . # 작업 후 add
git commit -m "[feat] ~~" # 커밋
git push origin Hyeonseong # 오리진에 푸시
```

### 폴더구조

```bash
.
├── api-practice # 과제: api 이용 데이터 수집
├── dynamic-crawling # 과제: 동적 크롤링
├── static-crawling # 정적 크롤링 실습
├── README.md # 프로젝트 설명 리드미 (수정X)
└── olavvn #(개인 폴더)
    └── yanolja.ipynb # python 코드 파일
    └── yanolja.py # python 코드 파일
└── .gitignore # gitignore파일(가상환경파일을 숨김처리)
└── requirements.txt # 텍스트 파일(패키지 관리 파일)
```

## 커밋 컨벤션

feat: 새로운 기능 추가  
fix: 버그 수정  
docs: 문서 수정  
style: 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우  
refactor: 코드 리팩토링  
test: 테스트 코드, 리팩토링 테스트 코드 추가  
chore: 빌드 업무 수정, 패키지 매니저 수정, production code와 무관한 부분들 (.gitignore, build.gradle 같은)  
comment: 주석 추가 및 변경  
remove: 파일, 폴더 삭제  
rename: 파일, 폴더명 수정
