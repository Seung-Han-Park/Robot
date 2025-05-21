# Let's update some sections to use tables for clarity.

markdown_with_tables = """
# 📘 C 언어 공부 핵심 정리 (표 포함 버전)

## ✅ 1. 기초 문법과 제어문

| 주제       | 설명 |
|------------|------|
| 프로그램 구조 | `main()` 함수 필수 |
| 자료형     | `int`, `float`, `char`, `double` 등 |
| 입출력     | `printf()`, `scanf()` 함수 사용 |
| 연산자     | 산술(`+ - * / %`), 관계(`== != > <`) 등 |
| 조건문     | `if`, `else`, `switch` |
| 반복문     | `for`, `while`, `do-while` |
| 기타       | `break`, `continue` |

---

## ✅ 2. 함수와 배열

| 항목     | 설명 |
|----------|------|
| 함수 정의 | 반환형, 이름, 매개변수 구성 |
| 함수 호출 | 값 전달, 포인터 전달 |
| 배열     | 1차원, 2차원 배열 선언 및 사용 |
| 문자열   | `char[]`, 종료문자 `\\0` 사용 |
| 문자열 함수 | `strlen`, `strcpy`, `strcmp` 등 |

---

## ✅ 3. 포인터와 구조체

| 항목     | 설명 |
|----------|------|
| 포인터 기본 | `*`, `&` 연산자 사용 |
| 배열과 포인터 | 포인터로 배열 접근 가능 |
| 구조체   | `struct` 정의 및 변수 사용 |
| 구조체 포인터 | 구조체 주소를 포인터로 처리 |
| 기타     | `union`, `typedef` 등 고급 타입 |

---

## ✅ 4. 동적 메모리와 파일 입출력

| 주제       | 함수 및 설명 |
|------------|---------------|
| 메모리 할당 | `malloc`, `calloc`, `free` |
| 포인터 배열 | 이중 포인터 사용 가능 |
| 파일 열기/닫기 | `fopen`, `fclose` |
| 파일 읽기/쓰기 | `fscanf`, `fprintf`, `fgets`, `fputs` |

---

## ✅ 5. 기타 중요한 개념

- 전처리기 지시문: `#include`, `#define`, `#ifdef`
- 저장 클래스: `static`, `extern`, `const`
- 함수 포인터
- 비트 연산자
- 컴파일 과정: 전처리 → 컴파일 → 링킹

---

## 📚 추천 학습 순서
1. 기본 문법 → 제어문 → 함수
2. 배열/문자열 → 포인터
3. 구조체 → 메모리 → 파일
4. 실습 & 알고리즘 문제풀이

---

## 🔧 연습 아이디어
- 계산기 프로그램
- 문자열 뒤집기, 비교, 검색
- 파일 처리 프로그램
- 백준, 프로그래머스 문제 풀이
"""

# Save the updated file with tables
table_file_path = "/mnt/data/C_Study_Guide_With_Tables.md"
with open(table_file_path, "w", encoding="utf-8") as f:
    f.write(markdown_with_tables)

table_file_path

