## Safe Call과 Elvis Operator
##### Safe Call (`?.`)
##### Elvis Operator (`?:`)
##### Non-null Assertion (`!!`)
##### let, run, apply, also와 null 처리

## 제어 흐름 <sub>Control Flow</sub>
##### If 표현식
##### When 표현식
##### For 루프
##### While 루프
##### Break와 Continue

## 가시성 지시자 <sub>Visibility Modifiers</sub>
##### `public`
##### `private`
##### `protected`
##### `internal`
##### 모듈과 가시성

## 예외 처리 <sub>Exception Handling</sub>
##### `try-catch-finally`
##### `throw` 표현식
##### Checked Exception vs Unchecked Exception (Kotlin의 접근 방식)

## 단일 표현식 함수 <sub>Single-Expression Functions</sub>
##### 정의 및 사용법
##### 반환 타입 추론

## 타입 별칭 <sub>Type Aliases</sub>
##### 정의 및 사용법
##### 활용 사례

## 스코프 함수 <sub>Scope Functions</sub>
##### let
##### run
##### with
##### apply
##### also
##### 각 함수의 차이점 및 사용 시점

## 구조적 동등성 <sub>Structural Equality</sub>
##### `==` (구조적 동등성)
##### `===` (참조적 동등성)
##### equals() 메소드
##### Java와 비교
- 구조적 동등성이란 쉽게 말하면 **내용물이 똑같은지** 보는 것이다.
- `==`: 두 객체의 내용물이 같은지 비교한다. (구조적 동등성)
    - 내부적으로 `equals()`를 안전하게 호출해준다.
- `===`: 두 변수가 메모리에서 똑같은 하나의 객체를 가리키고 있는지 확인한다. (참조적 동등성)
##### JavaScript와 비교

| 구분    | Kotlin              | JavaScript             |
| ----- | ------------------- | ---------------------- |
| `==`  | 구조적 동등성 (내용 비교)     | 느슨한 동등성 (타입 변환 후 값 비교) |
| `===` | 참조적 동등성 (메모리 주소 비교) | 엄격한 동등성 (타입과 값 모두 비교)  |

## 클래스 <sub>Class</sub>
##### 클래스 선언 및 인스턴스화
##### 주 생성자와 보조 생성자
##### 속성 (Properties)
##### 메소드 (Methods)
##### 중첩 클래스와 내부 클래스
##### Enum Class
##### Sealed Class
##### Data Class
##### Companion Object
##### 확장 함수 <sub>Extension Functions</sub>
##### 연산자 오버로딩

## 상속 <sub>Inheritance</sub>
##### 클래스 상속
##### `open` 키워드
##### 오버라이딩
##### 추상 클래스

## 인터페이스 <sub>Interface</sub>
##### 인터페이스 정의 및 구현
##### 추상 메소드와 기본 구현
##### 프로퍼티 선언

## 구조분해 선언 <sub>Destructuring Declaration</sub>
##### 정의 및 사용법
##### Data Class와 함께 사용
##### Map과 함께 사용

## 객체 지향 심화
##### 위임 (Delegation)
##### 속성 위임 (Property Delegation)
##### 클래스 위임 (Class Delegation)
##### 객체 표현식 (Object Expressions)
##### 객체 선언 (Object Declarations - Singleton)

## 컬렉션 <sub>Collections</sub>
##### List, Set, Map
##### 가변 컬렉션과 불변 컬렉션
##### 컬렉션 빌더
##### 함수형 API

## 제네릭 <sub>Generics</sub>
##### 제네릭 클래스 및 함수
##### Star-projection
##### 함수 제네릭
##### 제약 <sub>Constraints</sub>
##### 공변성, 반공변성
- 읽기 전용 - 공변성(`out`)
- 읽기/쓰기 - 불공변성
- 쓰기 전용 - 반공변성(`in`)

## 코루틴 <sub>Coroutine</sub>
##### 코루틴이란?
##### suspend 함수
##### CoroutineScope와 CoroutineContext
##### launch와 async
##### Dispatchers
##### Job과 Deferred
##### 예외 처리
##### 구조화된 동시성 <sub>Structured Concurrency</sub>