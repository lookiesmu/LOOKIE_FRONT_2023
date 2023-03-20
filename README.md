# LOOKIE_FRONT_2023
## **2023 ver.**

### **Week 07. OkHttp()에 대하여 알아보자.**

1. OkHttp와 Retrofit 차이 조사하기
2. OKHttp에 대한 조사하고 공부한 내용 올리기
- 이번 주는 쉬어가는 개념 정리 과제!(과제 관련 패스트 캠퍼스 강의 들을 필요없습니다.)

---

### **Week6. 안드로이드 Network 실습**

1. 패스트 캠퍼스 05 Essential 69강까지 수강
2. 패스트 캠퍼스 강의 내에 있는 Network 61~67강 실습 화면 캡쳐 및 강의 내용 정리 Issue 에 올리기
- 안드로이드 네트워크 관련 개념

### **Week5. 안드로이드 RecyclerView 실습**

1. 패스트 캠퍼스 05 Essential 50강까지 수강(Tablayout, Pager까지)
2. 나만의 여름방학 계획표 작성하기
    - 기능 1. Recycler View 로 계획표 날짜, 내용이 보이도록 함
    - 기능 2. 새로운 계획을 추가할 수 있도록 함
    - class file 3개 (main, plan, planAdapter), XML file 3개 (main, planview, dialogview)
        
          `class | main: (-)
                  plan: 계획의 정보 (날짜, 내용)을 담을 클래스
                  planAdapter: main의 RecyclerView에 장착할 CustomAdapter
          XML   | main: Button 1개,RecyclerView 1개
                  planview: TextView 2개 (날짜, 내용)
                  dialogview: EditText 3개 (날짜, 내용)`
        
    - 설명 :
        
          `main화면의 Button 클릭 시 Dialog 보여진다.
          Dialog내에서 2개의 값 입력후 추가 버튼 클릭 시 main화면에 해당 계획정보가 추가되고 Dialog가 종료된다.
          취소 버튼 클릭 시 아무런 동작없이 Dialog가 종료된다.`
        
    - 조건 :
        
          `계획 정보는 항상 리스트의 가장 위에 추가된다. Dialog의 editText값들이 채워지지 않은 경우는 고려하지 않는다.(예외처리 필요없음)`
        
- Dialog가 어려운 경우 [https://juyeop.tistory.com/7](https://juyeop.tistory.com/7) 사이트 참고하여 기능을 구현해도 됩니다.

### **Week4. 안드로이드 Fragment 실습**

1. 패스트 캠퍼스 05 Essential 24강까지 수강
2. MainActivity에서 버튼 제어로 연결된 Fragment 띄우기 기능 구현하기
    - 버튼 최소 4개 → fragment 4개 구현
    - 4개의 fragment 디자인 다 다르게 할 것
3. 파일 pull request하고 issue에 빌드된 화면을 캡쳐해서 올리기

### **Week3. 안드로이드 액티비티 및 Intent 실습. **

1. 05 Essential 수강 19강까지 수강
2. Activity 에서 버튼을 누를 시 다른 Activity로 전환 되는 기능을 구현하여 빌드

ex)

`1) MainActivity - A,B,C 버튼 생성
    - A버튼 클릭 시 AActivity로 이동
    - B버튼 클릭 시 BActivity로 이동
    - C버튼 클릭 시 CActivity로 이동
2) AActivity - 뒤로 가기 버튼 생성 → 클릭 시 MainActivity로 이동
3) BActivity - 뒤로 가기 버튼 생성 → 클릭 시 MainActivity로 이동
4) CActivity - 뒤로 가기 버튼 생성 → 클릭 시 MainActivity로 이동`

1. 조건 : 액티비티 간 Intent로 연결할 것.
2. 프로젝트 파일을 fork뜬 자신의 레포지토리에 push후 스터디 레포지토리/자신의 LOOKIE 브랜치에 Pull request까지 하기

### **Week 2) 안드로이드 UI.**

1. 패스트 캠퍼스 04 안드로이드 Essential - UI 부분 학습하기 (핵심 개념 : Scrollview, Imageview, Linearlayout)
2. 자신의 취향 or 친한친구가 담긴 Image를 등록하고 Scroll 하여 Image를 볼 수 있도록 만들기
3. build 한 화면 캡쳐해서 issue에 올리기

### **Week 1) Kotlin입문 및 Git 실습.**
0. 패스트 캠퍼스 03 안드로이드 Essential - Kotlin 부분 학습하기
1. Kotlin의 장점에 대해 적어보자.
2. Kotlin의 기본 문법을 정리해보자.
- 변수
- 자료형
- 함수
- 분기문
- 반복문. 
3. Github 2022 Lookie Front 를 fork 해서 자신의 레포지토리에 push해보기

### **Week 0) 프론트 스터디 OT.**
1. 8주 커리큘럼 소개 및 패스트캠퍼스 아이디 공유
2. GitHub 사용법 교육
3. 스터디 진행 방법 소개
ㅡ
ㅡㅡ
