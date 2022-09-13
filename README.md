### 🔸목차🔸
1. [프로젝트 및 팀 소개 (시연영상)](#프로젝트-및-팀-소개)
2. [프로젝트 목표](#프로젝트-목표)
3. [구현한 기능](#구현한-기능) 
4. [개인 별 구현 사항](#개인-별-구현-사항)
5. Reference





# 🔸프로젝트 및 팀 소개🔸

<img width="1324" alt="리드미 표지" src="https://user-images.githubusercontent.com/108933466/189675387-bc8387f1-cdda-477d-857d-682eed5704dd.png">


- 로컬 푸드 마켓 ‘미래식당‘ 사이트를 참고하여 개발한 클론 프로젝트  
  <br/>

### 유튜브 시연영상
- 약 4분정도 되는 영상입니다. 많은 시청 부탁드립니다 :)

  [!['미래식당' 클론프로젝트 시연영상](https://img.youtube.com/vi/f1He2K5uwyI/0.jpg)](https://www.youtube.com/watch?v=f1He2K5uwyI&t=1s)

<br/>

### 클론사이트로 '미래식당'을 선정한 이유

- 팀원 모두가 처음으로 진행하는 프로젝트인 만큼<br/>**웹서비스에서 보편적으로 구현되는 기능**들을 이해하고, 적용할 수 있는 것을 목표로 선정했다.  
  <br/>
  
### 개발인원 및 기간

- 개발기간 : 2022/8/29 ~ 2022/9/8 (약 2주)
- 개발인원 : 프론트엔드 4명, 백엔드 2명
- [백엔드 gitbub 링크](https://github.com/wecode-bootcamp-korea/justcode-6-1st-coding-restaurant-back)

| 프론트엔드 | 블로그 | 깃허브 | 이메일 |
| ------ | ------ | ------ | ------ |
| 박예선 | https://velog.io/@lynn080 | https://github.com/YesunPark | lynn08082@gmail.com |
| 박찬영 | https://poylib.tistory.com/ | https://github.com/Poylib | poy.alev@gmail.com |
| 이은지 | - | https://github.com/Chooteacher | zmz14s@gmail.com |
| 임지영 | https://roxylife-twinkledawn101.tistory.com/ |  https://github.com/Roxy100 | misoamy16@gmail.com |

  <br/>

# 🔸프로젝트 목표🔸

### 팀 전체 목표

- **Git, Github 의 사용법**을 익혀 협업에 활용할 수 있다.
- 협업 시 **소통에 적극적으로 참여**하고, 자신의 **의견을 올바르게 전달**할 수 있다.
- 소통을 통해 **역할을 적절하게 분담**하고, 프로젝트의 **일정을 관리**할 수 있다.
- 프론트엔드와 백엔드의 **업무를 분리**하여 각각의 기능을 개발하고 통신할 수 있다.


### 프론트엔드 목표

- **사용자에게 필요한 기능을 파악**하고 구현할 수 있다.
- UI를 구성할 때 **서버에서 가져와야 하는 데이터를 파악**하여 백엔드에 요청할 수 있다.
- 재사용이 가능한 컴포넌트의 특징을 이용해 코드를 **간결하고 가독성좋게** 작성할 수 있다

<br/>

# 🔸구현한 기능🔸

### 헤더
- 로그인/회원가입 버튼 <-> 로그인 시 마이페이지 버튼 전환
- 카테고리 클릭 시 해당 카테고리 페이지로 이동
- 로그아웃 클릭 시 로컬스토리지 토큰 삭제 후 메인페이지로 이동
- 장바구니에 담긴 상품 개수 표시


### 메인페이지

- 메인 캐러셀
- 서브 캐러셀 ( 간편요리, 주문 순, 인기많은 순)
- 서브 캐러셀 클릭 시 카테고리페이지 또는 상세페이지로 이동

### 제품상세페이지

- 제품 이름, 설명, 이미지 조회
- 마이페이지에서 등록한 리뷰 조회
- 옵션, 수량 선택, 장바구니 담기
- 5만원 이상 선택 시 무료배송 표시

### 장바구니페이지

- 장바구니에 담은 상품 조회
- 수량 변경
- 상품 별 합계, 총 합계, 총 배송비 확인
- 장바구니에서 상품 삭제

### 마이페이지

- 주문내역, 리뷰내역, 포인트, 내 정보 조회
- 리뷰 등록, 수정
- 내 정보(전화번호, 주소, 생년월일) 수정

### 회원가입페이지

- 이메일 유효성검사 (@포함, '.' 2개 이상 포함)
- 비밀번호 유효성검사 (10자리 이상)
- 이름 유효성검사 (한글2~4자리)
- 전화번호 유효성검사 (010으로 시작, 10~11자리)
- 생년월일 유효성검사 (1900년대생, 올바른 월/일 입력)

### 로그인페이지
- 이메일 유효성검사 (@포함, '.' 2개 이상 포함)
- 비밀번호 유효성 검사 (10자리 이상)
- 회원여부 확인


<br/>

# 🔸개인 별 구현 사항🔸


### 박예선

- UI
  - 메인페이지 메인 캐러셀
  - 장바구니페이지
  - 제품상세페이지
  - 마이페이지 내 정보 수정기능
- API
  - 상세페이지 조회
  - 헤더 장바구니숫자 반영
  - 마이페이지 프로필 조회
  - 마이페이지 내 정보 수정
  
  ---

### 박찬영

- UI
  - 메인페이지 서브 캐러셀
  - 헤더
  - 카테고리
- API
  - 메인페이지 서브 캐러셀
  - 카테고리

  ---
### 이은지

- UI
  - 마이페이지 (주문내역, 리뷰내역, 포인트, 내 정보)
- API
  - 마이페이지 (주문내역, 리뷰내역, 포인트, 내 정보) 조회
  - 리뷰 등록
  - 장바구니 추가

  ---
### 임지영

- UI
  - 회원가입, 로그인 페이지
  - Footer
- API

  - 회원가입, 로그인
  - 장바구니 조회, 삭제, 수정
  
  ---

    <br/>

# 🔸Reference🔸

- 이 프로젝트는 [미래식당](https://meesig.com/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
