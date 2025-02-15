# 100 Mini Projects Challenge
100개의 파이썬 미니 프로젝트를 만들며 성장하는 개발 기록

## 📜 진행 상황
✅ 12/100 완료
📅 목표: 2025년 5월까지 100개 완성  

## 📂 프로젝트 목록

### 1️⃣ 🎸 Band Name Generator  
- **설명:** 사용자의 고향 도시와 반려동물 이름을 입력받아 밴드 이름을 생성하는 간단한 프로그램  
- **사용 기술:** Python, Input Handling, String Manipulation  

### 2️⃣ 💰 Tip Calculator
- **설명:** 총 계산서 금액과 팁 비율을 입력하면, 인원수에 따라 각자 부담해야 할 금액을 계산
- **사용 기술:** Python, Math Operations, f-strings
- 
## 3️⃣ 🏝️ Treasure Island Adventure
- **설명:** 선택에 따라 진행되는 텍스트 기반 어드벤처 게임. 올바른 선택을 하면 보물을 찾을 수 있지만, 잘못된 선택을 하면 게임 오버됩니다!  
- **사용 기술:** Python, Conditional Statements (`if-else`), User Input Handling

## 4️⃣ 🎢 Rollercoaster Ride Checker
- **설명:** 키와 나이를 입력하면 롤러코스터를 탈 수 있는지 확인하고, 나이에 따라 티켓 가격을 계산하는 프로그램 
  - 사진 촬영을 원하면 추가 요금 $3 부과  
- **사용 기술:** Python, Conditional Statements (`if-elif-else`), User Input Handling

## 5️⃣ ✌️ Rock Paper Scissors Game
- **설명:** 사용자가 `가위(2)`, `바위(0)`, `보(1)` 중 하나를 선택하면, 컴퓨터도 랜덤으로 선택하여 승패를 결정하는 게임
  - ASCII 아트를 활용해 가위바위보 그림을 출력합니다.  
  - 컴퓨터와 동일한 선택을 하면 무승부, 이기면 "You win!", 지면 "You lose!" 메시지 출력
- **사용 기술:** Python, `random` 모듈, List Indexing, Conditional Statements

## 6️⃣ 🔐 PyPassword Generator
- **설명:**  
  이 프로젝트는 Python을 활용한 간단한 비밀번호 생성기입니다.  
  사용자로부터 포함할 **문자(letters)**, **숫자(numbers)**, **특수문자(symbols)**의 개수를 입력받아,  
  각 목록에서 랜덤하게 선택한 후 섞어 최종 비밀번호를 생성합니다.

- **사용 기술:**  
  Python, `random` 모듈, 리스트 조작, 사용자 입력 처리

## 7️⃣ 🧭 Maze Solver (Reeborg's World)

- **설명:**  
  이 프로젝트는 [Reeborg's World](https://reeborg.ca/reeborg.html?lang=en&mode=python&menu=worlds%2Fmenus%2Freeborg_intro_en.json&name=Maze&url=worlds%2Ftutorial_en%2Fmaze1.json)에서 제공하는 미로 문제를 해결하는 코드입니다.  
  간단한 조건문과 반복문을 사용해 로봇이 미로를 탈출할 수 있도록 동작을 구현했습니다.  
  - 오른쪽이 열려있으면 오른쪽으로 회전 후 이동  
  - 앞쪽이 열려있으면 이동  
  - 둘 다 막혀있으면 왼쪽으로 회전  
  방식으로 진행됩니다.

- **사용 기술:**  
  Python, 조건문(`if-elif-else`), 반복문(`while`)

- **실행 방법:**  
  1. 위의 [Reeborg's World 링크](https://reeborg.ca/reeborg.html?lang=en&mode=python&menu=worlds%2Fmenus%2Freeborg_intro_en.json&name=Maze&url=worlds%2Ftutorial_en%2Fmaze1.json)로 이동  
  2. 에디터에 코드를 복사하여 붙여넣고 실행하면 미로를 탈출하는 로봇의 움직임을 확인할 수 있습니다.
 
 ## 8️⃣ 🎮 Hangman Game

- **설명:**  
  이 프로젝트는 Python으로 구현한 **행맨 게임(Hangman Game)** 입니다.  
  사용자는 숨겨진 단어를 한 글자씩 추측하여 맞춰야 하며, 틀릴 경우 목숨(lives)이 줄어듭니다.  
  - 모든 목숨이 소진되면 게임 오버!  
  - 단어를 모두 맞히면 승리합니다.  
  - 단어 목록은 `hangman_words.py` 파일에서, 게임 로고와 행맨 그림은 `hangman_art.py` 파일에서 가져옵니다.

- **사용 기술:**  
  Python, 조건문, 반복문, 리스트, 사용자 입력, 모듈 임포트, ASCII Art

  - **모듈 구조:**  
  - **hangman_words.py**: 단어 목록(`word_list`)을 제공  
  - **hangman_art.py**: 게임 로고(`logo`)와 각 목숨 단계에 따른 행맨 그림(`stages`)을 제공

## 9️⃣ 🔄 Caesar Cipher
- **설명:**  
  이 프로젝트는 Python으로 구현한 **Caesar Cipher** 프로그램입니다.  
  사용자가 입력한 메시지를 지정한 만큼의 문자 위치를 이동시켜 암호화(encode) 또는 복호화(decode)할 수 있습니다.  
  프로그램 시작 시, `art.py` 파일에 정의된 로고(ASCII 아트)를 출력하여 멋진 시작 화면을 보여줍니다.
  
- **특징:**  
  - 알파벳 이외의 문자(숫자, 기호, 공백)는 그대로 유지됩니다.
  - 프로그램 종료 후, 재시작할 수 있도록 반복 실행 기능을 제공합니다.

- **사용 기술:**  
  Python, 문자열 조작, 리스트, 조건문, 반복문, 모듈 임포트

## 1️⃣0️⃣ 💰 Secret Auction Program
- **설명:**  
  이 프로젝트는 Python으로 구현한 **비밀 경매 프로그램**입니다.  
  여러 사용자가 입찰할 수 있으며, 최종적으로 가장 높은 입찰 금액을 제시한 사람이 낙찰됩니다.  
  프로그램 시작 시, `art.py` 파일에 있는 ASCII 아트 로고를 출력하여 경매 분위기를 연출합니다.

- **특징:**  
  - 사용자 이름과 입찰 금액을 입력받아 저장  
  - 여러 명이 입찰 가능하며, 입찰이 끝나면 최고 입찰자를 자동으로 선정  
  - 다른 사용자의 입찰 내용을 볼 수 없도록 터미널 화면을 지우는 기능 포함  

- **사용 기술:**  
  Python, 딕셔너리, 조건문, 반복문, 사용자 입력 처리

  ## 1️⃣1️⃣ 🧮 Simple Calculator

- **설명:**  
  이 프로젝트는 Python으로 구현한 **기본 사칙연산 계산기**입니다.  
  사용자가 입력한 두 숫자와 연산 기호(+, -, *, /)를 이용하여 계산을 수행하며,  
  연속 계산 기능을 지원하여 이전 결과를 이용한 추가 연산이 가능합니다.  
  프로그램 시작 시 `art.py` 파일에 있는 ASCII 아트 로고를 출력합니다.

- **특징:**  
  - 덧셈(+), 뺄셈(-), 곱셈(*), 나눗셈(/) 기능 제공  
  - 연속 계산 기능 지원 (이전 결과값을 이용해 추가 연산 가능)  
  - 새로운 계산을 원할 경우 프로그램이 재시작됨  

- **사용 기술:**  
  Python, 함수, 딕셔너리, 재귀 함수, 사용자 입력 처리

  ## 1️⃣2️⃣ ♠️ Blackjack Game

- **설명:**  
  이 프로젝트는 Python으로 구현한 **블랙잭(Blackjack) 게임**입니다.  
  사용자가 딜러(컴퓨터)와 함께 21을 목표로 카드를 받고, 점수에 따라 승패를 결정합니다.  
  프로그램 시작 시 `art.py` 파일에 있는 블랙잭 로고(ASCII 아트)를 출력합니다.

- **특징:**  
  - 기본 블랙잭 규칙 적용 (A는 1 또는 11로 계산)  
  - 사용자와 컴퓨터가 번갈아 가며 카드를 받습니다.  
  - 승패는 점수 비교 및 블랙잭 여부에 따라 결정됩니다.  

- **게임 규칙:**  
  - 카드는 2장에서 시작되며, 21을 초과하면 패배합니다.  
  - 딜러는 17 이상이 될 때까지 카드를 받습니다.
  - 블랙잭(카드 2장 합이 21) 시 즉시 승리합니다.  

- **사용 기술:**  
  Python, 리스트, 함수, 조건문, 반복문, 랜덤 모듈  

## 📧 Contact
- GitHub: [@JIYUN000000](https://github.com/username)
- Email: brilliantstar120@gmail.com
