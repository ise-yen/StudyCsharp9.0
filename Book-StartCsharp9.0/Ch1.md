## 1.1 닷넷 프레임워크

### 닷넷 프레임워크(.NET Framework)

- 개발 환경, 프로세스 가상 머신

### CLR(Common Language Runtime)

- 프로세스(EXE)가 실행되면 메모리에 함께 적재돼 실행
- CLR 구성요소가 로드돼 실행되고, CLR이 EXE/DLL에 함께 저장돼 있는 닷넷 코드를 실행

### C#

- C# 컴파일러: 소스코드 -> EXE/DLL 파일 내부에 IL(Intermediate Language, 중간언어)로 생성
- 프로그램 실행: EXE 파일 내부에 CLR을 로드하는 코드를 추가(자동)
- 로드/실행 순서: CLR 로더 코드 실행 -> 사용자의 중간언어 코드 실행
