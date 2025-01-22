## Info

- hyperledger besu
- 2023

## Usage

1. VS Code EXTENSIONS: Install the PlantUML plugin from the marketplace.

2. You can preview the UML diagram by pressing Shift + Command + P and selecting the 'PlantUML: Preview Current Diagram' option.

## UML

### 관계

- 속이 빈 삼각형
  - `<|..` 실체화 관계 (인터페이스와 구현체 관계)
  - `<|.` 
  - `<|--` 일반화 관계 (상속 관계)
  - `<|-` 
- 화살표
  - `<..` 의존 관계
  - `<.`
  - `<--` 연관 관계
  - `<-`
- 속이 빈 다이아몬드 
  - `o--` 집약 관계
  - `o-`
- 속이 찬 다이아몬드 
  - `*--` 합성 관계
  - `*-` 
- 위치 관계 참조 
  - `..` 상하로 위치
  - `.`  좌우로 위치
  - `--` 상하로 위치
  - `-`  좌우로 위치

### 기호

- 대시 (-): private
- 더하기 (+) : public
- 해시 (#) : protected

### 참조

- UML_Allow.png
