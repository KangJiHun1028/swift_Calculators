* Calculator 클래스
    * Calculator 클래스는 계산기를 나타내는 클래스로, 사칙연산을 수행하는 기능을 제공합니다.
* calculate 메서드
    * calculate 메서드는 사칙연산 기능을 수행하는 함수로, 세 개의 매개변수를 받습니다.
    * operator는 연산자를 나타내는 문자열을 받습니다. (예: "+", "-", "*")
    * firstNumber와 secondNumber는 연산을 수행할 두 개의 숫자를 나타냅니다.
    * 해당 연산자에 따라 firstNumber와 secondNumber를 이용하여 계산을 수행하고, 결과를 Double로 반환합니다.
* 계산기 사용
    * Calculator 클래스를 이용하여 계산기 객체 calculator를 생성합니다.
    * operatorString, firstNumber, secondNumber에 각각 덧셈을 나타내는 "+", 5.0, 3.0을 할당합니다.
    * calculator의 calculate 메서드를 호출하여 사칙연산 결과를 계산하고, 옵셔널 바인딩을 사용하여 결과를 확인합니다.
    * 결과가 nil이 아니라면 "결과: [계산 결과]"를 출력하고, nil이라면 "잘못된 연산자입니다."를 출력합니다.
