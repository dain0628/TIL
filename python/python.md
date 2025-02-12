파이썬 코드를 터미널에서 실행하고 싶을 때는
-  python {파일 이름}
잘못 입력 했을 때 나오고 싶으면
- exit ()

## 파이썬 코드
print () : 입력 값 출력
type () : ()가 어떤 형태인지 물어보는 거 > ex. int , complex 인지 등
print (a // b) : 결과 값으로 몫을 나타냄
print (a % b) : 결과 값으로 나머지를 나타냄 
result = divmod(a, b)
print(result)

python -m venv venv
파이썬이라는 프로그램에서 모듈을 만들건데 그 모듈은 venv이고 파일 이름은 venv 야
> 그러면 파일이 여러개 생성 
> 이 파일은 무엇? 가상환경에서만 쓰게 하는 거 밖으로 못 내보냄

 source venv/Scripts/activate
 > venv/Scripts/activate 라는 파일을 활성화할거야


### 파이썬 문법
- int : 정수
- float : 소수점이 있는 숫자
- complex : 복소수 > j는 복소수 의미
- string : 글자로 이루어진 변수
- bool : 참(True)과 거짓(False)으로만 이루어진 자료형 / 0 = False , 1 = True
