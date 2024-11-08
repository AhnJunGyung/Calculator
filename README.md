# 🧮 Swift로 계산기 만들기

<img src="https://velog.velcdn.com/images/ekdlrkzm/post/5a46d70d-6027-4da6-95c3-85b132dd5293/image.webp">

## 📖 목차
1. [프로젝트 소개](#프로젝트-소개)
2. [프로젝트 계기](#프로젝트-계기)
4. [구현목표](#구현목표)
5. [개발기간](#개발기간)
6. [기술스택](#기술스택)
7. [Language](#Language)
8. [Trouble Shooting](#trouble-shooting)
    
## 👨‍🏫 프로젝트 소개
더하기, 빼기, 나누기, 곱하기 연산을 수행할 수 있는 Calculator 클래스를 만들기

## 프로젝트 계기
스파르타코딩클럽에서 iOS를 수강 중 swift문법 기초 주차에 과제로 부여받은 개인프로젝트입니다.

## 구현목표
        
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
           2️⃣ 기존에 구현한 AddOperation(더하기), SubtractOperation(빼기), MultiplyOperation(곱하기), 
              DivideOperation(나누기) 클래스들과 관계를 맺고 Calculator 클래스의 내부 코드를 변경
           * Hint! 클래스간의 결합도, 의존성(의존성 역전 원칙)


## ⏲️ 개발기간
- 2024.10.28(월) ~ 2024.10.31(목)

## 📚️ 기술스택
<img src="https://img.shields.io/badge/Xcode-147EFB?style=flat-square&logo=Xcode&logoColor=white"/>


### ✔️ Language 
<img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=Swift&logoColor=white"/>

## Trouble Shooting
- 나머지 기능에서 0으로 나눴을 때 무한루프에 빠지는 오류에 대한 예외처리를 놓쳤습니다. 나누는 값으로 0이 입력되면 문구를 출력하도록 수정하였습니다.
- 오류는 아니었지만 프로토콜 사용법이 미숙했습니다. 튜터님의 피드백을 받고 올바른 사용법으로 수정하였습니다. 

