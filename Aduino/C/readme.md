# Let's condense the steps into fewer categories and update the markdown content.

condensed_markdown = """
# 📘 C 언어 공부 핵심 정리 (간략 버전)

## ✅ 1. 기초 문법과 제어문
- C 언어의 구조 (`main()` 함수 등)
- 자료형 (`int`, `float`, `char`, `double`)
- 출력/입력 함수: `printf()`, `scanf()`
- 연산자: 산술, 관계, 논리, 대입 등
- 조건문: `if`, `switch`
- 반복문: `for`, `while`, `do-while`
- `break`, `continue`

## ✅ 2. 함수와 배열
- 함수 정의 및 호출
- 매개변수, 반환값
- 재귀 함수
- 1차원 / 2차원 배열
- 문자열 (`char[]`, `\\0` 종료)
- 문자열 처리 함수 (`strlen`, `strcpy`, `strcmp` 등)

## ✅ 3. 포인터와 구조체
- 포인터 선언과 연산 (`*`, `&`)
- 배열과 포인터의 관계
- 함수에 포인터 전달
- 구조체(`struct`) 정의 및 사용
- 구조체 포인터
- 공용체(`union`), `typedef`

## ✅ 4. 동적 메모리와 파일 입출력
- 동적 할당: `malloc`, `calloc`, `free`
- 포인터 배열
- 파일 입출력: `fopen`, `fclose`, `fscanf`, `fprintf`, `fgets`, `fputs`

## ✅ 5. 기타 중요한 개념
- 전처리기: `#include`, `#define`, `#ifdef`
- 변수 저장 클래스: `static`, `extern`, `const`
- 함수 포인터
- 비트 연산자
- 컴파일 과정 이해

## 📚 추천 학습 순서
1. 기본 문법 → 제어문 → 함수
2. 배열/문자열 → 포인터
3. 구조체 → 메모리 → 파일
4. 실습 & 알고리즘 문제풀이

## 🔧 연습 아이디어
- 계산기 프로그램
- 문자열 뒤집기, 비교, 검색
- 파일 처리 프로그램
- 백준, 프로그래머스 문제 풀이
"""

# Save condensed version
condensed_file_path = "/mnt/data/C_Study_Guide_Condensed.md"
with open(condensed_file_path, "w", encoding="utf-8") as f:
    f.write(condensed_markdown)

condensed_file_path

