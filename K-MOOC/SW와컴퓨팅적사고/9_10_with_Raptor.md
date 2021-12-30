# 9주차: 프로그래밍 언어를 이용한 컴퓨터와의 소통

## 프로그래밍 언어

- 기계 중심의 저급 엉어(Low-level language)
  - 기계어(Machine language)
    - 컴퓨터 내부의 동작을 0,1로 표현
    - 처리속도 빠름
    - 다른 컴퓨터와 호환 X, 하드웨어에 종속적
  - 어셈블리어
  - ![image](https://user-images.githubusercontent.com/68841702/147690591-d3d4ad76-fb00-404d-8b37-0f25807fccd0.png)
    - 기계명령을 알기쉬운 기호로 표현
    - 하드웨어를 직접 제어하는 용도로 활용
- 고급 언어(high-level)
  - 문법구조와 데이터 구조화에 대한 규칙이 있음
  - 접근성이 용이하도록 만들어진 인공적인 언어

## 프로그램의 실행방법

- 고급언어로 작성된 프로그램을 기계어로 번역해서 컴퓨터 실행

- 컴파일러 방식

![image](https://user-images.githubusercontent.com/68841702/147690845-6418c39c-98bc-4683-992b-1ad70d333d07.png)

- 인터프리터 방식

![image](https://user-images.githubusercontent.com/68841702/147690884-5380e8a9-8f50-448e-bf97-ae9360f8a97d.png)

- 하이브리드 방식

![image-20211230030412265](md-images/image-20211230030412265.png)



## 랩터(RAPTOR)

- 전투기 조종사들의 코딩교육을 위해 개발된 프로그래밍 언어
- 순서도를 기반으로 알고리즘을 구성하고 실행하는 비주얼 프로그래밍 언어

- 설치: https://raptor.martincarlisle.com/

![image](https://user-images.githubusercontent.com/68841702/147691399-619ac8fd-657d-4d1a-b243-48ea4653c240.png)

#### 랩터의 장점

- 알고리즘의 흐름을 이해하고 개선하기 쉬움
- 랩터로 작성한 순서도는 C, 파이썬을 이용한 코드 작성의 기초 자료로 활용 가능
- 고급 프로그래밍 언어로 변환될 수 있는 기능 탑재



## 알고리즘

- 주어진 문제를 해결하기 위해 일련의 논리적인 절차나 방법을 체계적으로 표현하는 것

### 논리적 절차

- 명확성
  - 기술된 명령이 한 가지 이상의 의미를 포함하지 않도록 함
- 효과성
  - 기술된 명령은 반드시 주어진 상황에 영향을 주어서 실제로 상황을 변화시키는 효과가 있어야 함
- 입력과 출력
  - 적어도 한 가지 이상의 문제 해결 결과에 따른 출력이 반드시 생성되어야 함
- 유한성
  - 알고리즘에 있는 명령이 수행되면 한정된 단계를 처리한 후에 반드시 종료되어야 함

![image](https://user-images.githubusercontent.com/68841702/147691939-49530bec-dbee-42ab-951c-f6f256b2bff5.png)

## 랩터

- 배정(Assignment)
- 프로시저 호출(call)
  - 함수라고도 함

![image](https://user-images.githubusercontent.com/68841702/147692143-b08d6338-421c-459f-a96a-7964c1742771.png)



## 알고리즘

![image](https://user-images.githubusercontent.com/68841702/147692415-ccf9b81f-8a4e-4070-991b-02d94703c4a0.png)

- 추상화
  - 정보를 재구성하고 필요한 속성으로 간소화
- 알고리즘 생성
  - 문제 해결을 위한 프로세스를 생성
- 프로그래밍
  - 알고리즘 구현

## 프로그램 논리

![image](https://user-images.githubusercontent.com/68841702/147692518-4fbce764-2dc1-4c07-81e2-c8879484a9c1.png)

![image](https://user-images.githubusercontent.com/68841702/147692532-70c671e6-413f-4e98-96a8-e80149ed0498.png)
- 선택논리 
	- if, else구문
	![image](https://user-images.githubusercontent.com/68841702/147692537-a3cd755b-cb11-41ea-9ed6-d648b137d92b.png)
- 반복논리
	- Loop문, while, for
	![image](https://user-images.githubusercontent.com/68841702/147692549-a18bb245-bce4-4639-8abc-b887111852c8.png)



# 10주차: 순서도와 알고리즘 구현

## 변수(Variable)

- 변하는 또는 변할 수 있는 어떤 것
- 데이터 기억장소, 데이터 운반자



## 식별자(Identifier)

- 변수를 구분하고 관리
- 데이터의 특징을 반영하여 식별자의 이름을 지음

![image](https://user-images.githubusercontent.com/68841702/147694097-83e1a3af-b10f-4811-b6cc-b74cf1eda325.png)

## 선언(Declaration)

![image](https://user-images.githubusercontent.com/68841702/147694144-79a3d052-9d71-43c5-8faf-42b76bf1b65b.png)

![image](https://user-images.githubusercontent.com/68841702/147694178-1a979781-e224-4e82-ad3e-1b87f75056ab.png)



## 데이터 연산

![image](https://user-images.githubusercontent.com/68841702/147694370-c12d05a2-31c8-4db9-8918-7ebf7824078f.png)

## 관계 연산과 논리 연산

- 관계 연산 : 부등호, ==
- 논리 연산: and, or, not. xor 등
