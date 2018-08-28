---
theme : "moon"
transition: "zoom"
highlightTheme: "darkula"
---

# Wavus 
# 일학습병행제
## 이주영


---

# 목차

1. 이상음원감지
2. 비상벨 솔루션
3. WeFramework

---

# 1. 이상음원  </p>  감지

--

## 목적
비명소리 감지를 통해 도시의 안전 확보

![비명인식](https://d2mxuefqeaa7sj.cloudfront.net/s_1AC57684C32D227149AAE5AE12D2DFA914C1537492A2BBE0E1E3C3438739353B_1535418922770_pic1.jpg)
--

## 클래스
> https://urbansounddataset.weebly.com


10개의 클래스 중에서 생활에서 제일 널리 발견되는 소리 4개를 선택해 트레이닝 도입.
- 사이렌 소리 
- 차 경적소리
- 강아지 짖는 소리
- 차 시동소리
- 비명 소리

--

## 라이브러리
![케라스](https://cdn-images-1.medium.com/max/1200/1*qllYdaKrZLMhK-nK1zUVEQ.png)

파이썬 베이스 딥러닝 라이브러리로 효율적인 신경망 구축에 탁월 & 단순한 인터페이스 특화

--
## 프로세스

![프로세스](https://d2mxuefqeaa7sj.cloudfront.net/s_1AC57684C32D227149AAE5AE12D2DFA914C1537492A2BBE0E1E3C3438739353B_1535420404601_image.png)

--
## 특징추출
스펙트로그램 : 음성을 가시화하여 시간축과 주파수 축의 변화를 확인 가능

![스펙트로그램](https://ccrma.stanford.edu/~jcaceres/yamaha/documentation/noise_bands_fs/noise_bands_fs_02.png)

--

## 트레이닝 결과

> https://github.com/Brit7777/scream-classifier/blob/master/training_prediction.ipynb

---

# 2. 비상벨 </p> 솔루션

--

## 목적
단가가 비교적 저렴한 라즈베리를 활용해 통화/카메라 연결 가능한 비상벨 제작
![라즈베리](https://3.bp.blogspot.com/-UM6YUIs1qX4/WIT5pWslUyI/AAAAAAAAInY/ytHiwijn0IsNh40Q9YzRpSlZOvso5Iu8gCLcB/s640/button_cased.jpg)

--

## 시스템 아키텍쳐
![아키텍처](https://d2mxuefqeaa7sj.cloudfront.net/s_1AC57684C32D227149AAE5AE12D2DFA914C1537492A2BBE0E1E3C3438739353B_1535423119652_image.png)

--

## 주된 업무
![림폰](https://d2mxuefqeaa7sj.cloudfront.net/s_1AC57684C32D227149AAE5AE12D2DFA914C1537492A2BBE0E1E3C3438739353B_1535437884919_image.png)

--

## 겪었던 어려움
- 라즈베리파이?
- 생소한 운영체제 = 리눅스 프로그래밍
- 새로 접한 오픈소스 ex) linphone, wiringPi등

---

# 3. WeFramework

--

## 목적
전자정부프레임워크를 기반으로 사내개발표준화 진행
![사내개발표준화](https://d2mxuefqeaa7sj.cloudfront.net/s_1AC57684C32D227149AAE5AE12D2DFA914C1537492A2BBE0E1E3C3438739353B_1535422576780_image.png)

--

## 스프링
![스프링](https://t1.daumcdn.net/cfile/tistory/22032F465925A2211D)

자바(JAVA) 플랫폼을 위한 오픈소스(Open Source) 어플리케이션 프레임워크

> 철저한 오브젝트 중심 = 객체지향적

--

## 주된 업무
- 메소드 및 변수명 지정된 명명규칙에 맞게 적용
- 메뉴얼 작업 

![메뉴얼](https://d2mxuefqeaa7sj.cloudfront.net/s_1AC57684C32D227149AAE5AE12D2DFA914C1537492A2BBE0E1E3C3438739353B_1535437129030_image.png)

--

## 개발 전 준비 단계

- DB 설계
- 화면 구현
- 클래스 설계

--

## 구현

![플로우](https://d2mxuefqeaa7sj.cloudfront.net/s_1AC57684C32D227149AAE5AE12D2DFA914C1537492A2BBE0E1E3C3438739353B_1535430059718_image.png)

--

- 메세지 처리
- validator 설정

![벨리데이터](https://d2mxuefqeaa7sj.cloudfront.net/s_1AC57684C32D227149AAE5AE12D2DFA914C1537492A2BBE0E1E3C3438739353B_1535430467457_image.png)

---
지난 7개월동안 수고하셨습니다:)
