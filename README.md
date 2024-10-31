# Calculator
- 최초작성 : 2024.10.31
- 코드 작성 기간 : 10.28 - 10.31
- 소개 : 주어진 과제를 따라 Xcode의 playground를 사용해 간단한 swift 계산기를 만들어보았습니다.
        과제의 구현 목표는 다음과 같습니다.
        1. [필수]Lv1
           1️⃣ 더하기, 빼기, 나누기, 곱하기 연산을 수행할 수 있는 Calculator 클래스를 만들기
           2️⃣ 생성한 클래스를 이용하여 연산을 진행하고 출력
        2. [필수]Lv2
           1️⃣ Lv1에서 만든 Calculator 클래스에 “나머지 연산”이 가능하도록 코드를 추가하고, 연산 진행 후 출력
        3. [필수]Lv3
           1️⃣ 아래 각각의 클래스들을 만들고 클래스간의 관계를 고려하여 Calculator 클래스와 관계 맺기
             - AddOperation(더하기)
             - SubtractOperation(빼기)
             - MultiplyOperation(곱하기)
             - DivideOperation(나누기)
           2️⃣ Calculator 클래스의 내부코드를 변경
             - 관계를 맺은 후 필요하다면 별도로 만든 연산 클래스의 인스턴스를 Calculator 내부에서 사용
           * Hint! 클래스의 책임(단일책임원칙)
         4. [선택]Lv4
           1️⃣ AbstractOperation라는 추상화된 프로토콜 만들기
           2️⃣ 기존에 구현한 AddOperation(더하기), SubtractOperation(빼기), MultiplyOperation(곱하기), DivideOperation(나누기) 클래스들과 관계를 맺고 Calculator 클래스의 내부 코드를 변경
           * Hint! 클래스간의 결합도, 의존성(의존성 역전 원칙)
        
