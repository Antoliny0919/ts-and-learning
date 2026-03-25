# 학습 로그

## 메타인지 하기

### 1. 현재 TypeScript 경험

- TS를 써본 적이 있는가? 있다면 어느 정도?

사용해본적은 있으나 약 2,3년 전인거 같다.
당시에도 딱히 깊게 사용해보지 않았고 맛만 본 수준인거 같다.

### 2. 기존에 새로운 개념을 학습할 때 어떻게 했나요? (수업시간에 v1 떠올렸던 것 첨부)

개념을 얼마나 딥다이브 할까에 약간 차이가 있다.

1. 내가 정말 이 기술에 관심이 있고 깊이 들어가고 싶으면 가장 먼저 공식문서를 본다.
그정도가 아니라면 AI에게 물어보는걸로 시작하는거 같다.

2. 여러가지 체험을 해본다. 실제로 적용해보고 배우기 위해 더 좋은 방식이 있는지 찾아본다.(개인 블로그를 많이 보는거 같다.)

3. 주변에서 잘 하는거 같은 사람들에게 물어본다.
쌩판 모르는 사람에게도 이메일을 보내어 키워드를 알아본다.

4. 어느정도 지식을 정리하고 AI에게 검토받는다.

5. 회고를 하며 이 기술을 통해서 무엇을 하고 어디에 적용할지 고민해본다.

6. 5번 고민에 따라 이후의 방향성이 결정된다.

7. 정말 재밌고 흥미로운 기술이면 내부를 관찰한다. 그렇지 않다면 끝내는거 같다."

## 학습 로그 #1

**시간**: 03/24 15:30 ~ 17:00, 19:20 ~ 20:40 (약 2시간 50분)
**학습 범위**: (예: typescript-exercises #1~#3)

### 1. 첫 학습 전략 설계

- 어떤 전략으로 학습하기로 했는가?
아직 타입스크립트에 대해 아는게 없는 만큼 기본 사용방식에 대해서 학습했다.
추가로 Exercises의 초반 문제를 풀어보면서 실전 감각을 익히기 시작했다.

- 그 전략을 선택한 이유는?

기초 단계라고 생각했다.
일단 먼저 Typescript를 사용해보면서 이게 어떤 것인지 그리고 어떻게 사용하는것인지에 대한 파악이 필요했다.

- 실제로 어떻게 학습했는지 디테일한 과정을 써보세요.

typescript 기본 사용방식에 대한 공부

- https://www.typescriptlang.org/ko/docs/handbook/typescript-in-5-minutes.html
- https://www.typescriptlang.org/ko/docs/handbook/typescript-tooling-in-5-minutes.html

typescript-exercieses #1 ~ #4

<#3> - 타입 좁히기

JS에서 객체 또는 프로토타입에 특정 이름의 프로퍼티가 존재하는지 확인하는 연산자 "in"이 존재.
조건식에서 특정 속성에 접근할때 `undefined`를 통해 `if` 조건 결과를 계산하지 X
"in"을 통해 특정 속성이 존재하는지 명시적으로 확인하자. 

<#4> - 타입 프레디케이트

`parameterNames is Type`형태로 정의
이 함수가 true를 반환하면, 이 Parameter는 X 타입이다를 TypeScript에게 알려준다.

### 2. 전략 평가

- 효과적이었던 것과 그 이유

공식문서를 통해 기본 사용법에 대해서 익혔다.
일단 초기단계이기 때문에 가장 기본적인 사용방식을 공부했다.
실제로 덕분에 exercieses의 기본문제들을 쉽게 풀 수 있었다.
하지만 정말 기본적인 시작 문서만 읽었기 떄문에 3,4 번만 가도 어려웠다.
읽은 문서에 대해서 생각해보면 당연한 결과라고 생각된다.

- 비효과적이었던 것과 그 이유

exercieses를 시작하기 전에 조금 더 공부가 필요했던거 같다.
TypeScript문서의 HandBook 섹션을 전부 읽어보고 싶다.
하지만 문서만 읽으면 재미를 못느끼고 지루한 형태였을거 같다.
심지어 다른 섹션으로 넘어갈 수록 이전 섹션에 대한 기억을 잃을 가능성이 높다.
그래서 지금처럼 오히려 간단하게만 읽고 exercieses를 풀어본게 오히려 괜찮았다고 생각한다.
틀려도 괜찮으니까 틀림을 통해서 공부하는 과정을 겪으면 될거 같다.
그리고 이후에 선택적으로 HandBook섹션을 찾아봐야겠다.

### 3. AI 피드백

- 자신의 학습 전략에 대해 AI에게 피드백을 요청하고, 유용했던 제안 1가지 이상 기록

> TypeScript를 처음 시작하는 사람의 학습전략이야.
가장먼저 TypeScript 공식문서의 Get Started 섹션을 읽어봤어. 그리고 typescript-exercieses 사이트의 1 ~ 4 번 문제까지 해결해봤어.
오늘의 학습에서 내가 느꼈던점들이야.
(위 내용)
내 학습전략에 대해서 피드백해줄 수 있어?

키워드 답변: 한 가지만 제안하자면, 회고의 방향을 조금 더 구체화하면 좋을 것 같아요.

문제중 3,4 번이 어려웠던 이유가 정확히 뭐였는지에 대해서 생각하고 서술해라.

### 4. 다음 타임에 바꿀 것

- 유지할 것과 그 이유
유지할 것이다.
- 바꿀 것과 그 이유
문제를 풀고 난 뒤에 문제를 통해서 공부하는 만큼 어떤 부분이 어렵고 어떤 부분을 배웠는지에 대한 회고를 구체적으로 기록할것이다.

---

## 학습 로그 #2

**시간**: 
03/25 10:30 ~ 11:30 (약 60분)
03/25 13:10 ~ 15:00 (약 100분)

**학습 범위**:

### 1. 이번 타임의 학습 전략

- 이전에 바꾸기로 한 전략은 무엇이었고, 실행했는가?

문제를 해결했을때 더 구체적인 회고를 작성하기로 했다.
이전 회고에 비해 더 세세하게 했다.
고민했던 부분, 아쉬웠던 점, 실제 답과의 비교, 어떻게 생각했는지에 대한 부분들을 서술했다.

추가로 타입스크립트가 왜 탄생하게 되었는지에 대한 배경을 찾아봤다.
타입스크립트를 배우기전에 가장 먼저 "왜 해야하는지?"에 대해서 알아가는 시간이 필요했던거 같다. (호기심도 있다.)

- 실제로 어떻게 학습했는지 디테일한 과정을 써보세요.

#### 타입스크립트는 왜 탄생하게 되었을까?

- https://www.typescriptlang.org/why-create-typescript/

 JavaScript는 원래 웹사이트에서 단순한 인터랙션을 처리하는 소규모 프로그래밍 언어로 설계되었다.
 반면 Java는 어떤 컴퓨터에서도 실행될 수 있는 복잡한 앱을 만들기 위해 설계되었습니다.
 서로 다른 규모의 코드베이스에서 사용될 것을 예상했기 때문에, 각 언어는 서로 다른 유형의 코드를 요구했다.

 Java는 더 복잡한 프로그램을 만드는 것을 목표로 했기 때문에 변수 값에 대해 더 명시적으로 작성할 것을 요구했다.
 반면 JavaScript는 세부 정보를 생략하여 읽기 쉬움을 선택했고, 코드베이스가 훨씬 작을 것으로 예상했다.

TypeScript가 JavaScript에 추가하는 확장 기능은 Java처럼 코드에서 사용되는 데이터의 종류를 더 명시적으로 표현할 수 있도록 돕는다.

```ts
var name: string = "Danger"
console.log("Hello, " + name)
```

이 추가된 `: string`은 `name`이 항상 문자열임을 확실히 알 수 있게 한다.
이런 방식으로 변수에 주석을 달면 TypeScript가 이들이 일치하는지 검증할 수 있습니다.

변수에 담긴 값의 타입 변화를 추적하는 것은 한두 개일 때는 쉬워 보이지만, 수백 개가 되면 추적하기 매우 어려워지기 때문에 이는 매우 유용합니다.
타입을 작성하면 타입이 실수를 잡아주기 때문에 프로그래머들이 코드에 더 자신감을 가질 수 있습니다.
타입스크립트를 통해 코드가 얼마나 올바른지 미리 검증할 수 있다.
즉, 변경 사항이 나머지 프로그램에 어떤 영향을 미치는지 일일이 이해할 필요가 없어지고 훨씬 더 예측 가능해진다.

#### typescript-exercieses 5 ~ 9

Question 5
---

criteria는 User의 일부인 객체가 전달됨.
여기서 User 객체는 type, name, age, occupation 이라는 키값을 가지고 각 키마다 타입이 존재하는 상태.
그렇기 때문에 criteria의 경우에는 type만 가지는 객체거나, name만 가니는 객체가 전달되는 형태.

처음에는 [옵셔널 프로퍼티](https://www.typescriptlang.org/ko/docs/handbook/2/everyday-types.html)을 사용하여 해결.
```ts
interface PartialUser {
    type?: 'user';
    name?: string;
    age?: number;
    occupation?: string;
}
```
새로운 타입을 정의하고 각 키에 ?를 사용하여 문제를 해결할 수 있었으나 효율적인 형태는 아니었음.
(굳이 새로운 타입을 만들 필요가 없는 문제)

더 좋은 방식이 존재할거라고 생각했고 AI를 통해 `Partial` 유틸리티 사용을 권장받았다.
`Partial`은 Type의 모든 속성을 선택적으로 설정한 타입을 구성한다.
사실상 내가만든 `PartialUser`와 동일하지만 새로운 interface를 만들 필요없이 아름답게 해결할 수 있는 방안이다.

Question 6
---

함수 오버로딩과 관련된 문제였다.
personType이 'user'일 때는 `User[]`를 반환하고 personType이 'admin'일 때는 `Admin[]`를 반환해야한다.
처음 생각했던 구현방식은 다음과 같다.
```ts
export function filterPersons(persons: Person[], personType: 'user' | 'admin', criteria: Partial<Omit<User, 'type'>> | Partial<Omit<Admin, 'type'>>): User[] | Person[] {
    ...
}
```

위와 같이 만들었을때 User객체 배열이나 Person 객체 배열이 반환될 수 있다.
정도로만 끝난다.
여기서 우리는 personType과 반환값을 연결지어야 한다고 생각되었다.
그렇기 때문에 처음에는 [오버로드](https://www.typescriptlang.org/ko/docs/handbook/2/functions.html#%ED%95%A8%EC%88%98-%EC%98%A4%EB%B2%84%EB%A1%9C%EB%93%9C)가 왜 필요할까? 라는 고민이 있었는데 해결되었다.
(결국은 더 명확해지는 과정이었다.)

이후에 오버로드를 통해 다음과 같이 수정했다.
```ts
export function filterPersons(persons: Person[], personType: 'user', criteria: Partial<Omit<User, 'type'>>): User[];
export function filterPersons(persons: Person[], personType: 'admin', criteria: Partial<Omit<Admin, 'type'>>): Admin[];
export function filterPersons(persons: Person[], personType: 'user' | 'admin', criteria: Partial<Omit<User, 'type'>> | Partial<Omit<Admin, 'type'>>): Person[] {
}
```
조금 길어지기는 했지만 이제는 personType에 어떤 값이 전달되었을때 `User[]` 가 반환되는지 `Admin[]` 이 반환되는지 더 명확해졌다.
하지만 아직 해결되지 않았다.

```ts
// before

let criteriaKeys = Object.keys(criteria) as (keyof Person)[];

// after

let criteriaKeys = Object.keys(criteria) as (keyof Omit<Person, 'type'>)[];
```
수정하기 전까지 이 부분에서 왜 타입 에러가 발생할까? 고민이 있었다.
이전에 criteria같은 경우에 `Partial<Omit<Class, 'type'>>`을 사용하여 'type'
이라는 속성을 제외시켰다.
그렇기 때문에 `Object.keys(criteria)`의 결과도 정확히 말하면 Person의 키값을 가진 배열이라고 할 수 없다.
우리는 'type'이 전달되지 않을걸 알기 때문에 keyof 또한 'type'을 제거해야한다.

**정답과 비교..**

```ts
const getObjectKeys = <T>(obj: T) => Object.keys(obj) as (keyof T)[];

let criteriaKeys = getObjectKeys(criteria);
```

정답에서는 `getObjectKeys`라는 함수를 구현했다.
함수의 동작은 기존 구현과 동일하지만 제네릭 타입 파라미터를 통해 어떤 타입이 전달되더라도 반환되는 값은 해당 타입의 키라는걸 자동으로 추론한다.

만약 `getObjectKeys`와 같은 동작이 여러개였다면 동일한 타입 캐스팅을 수동으로 작성해야 했을 것이다.

Qestion7
---

[제네릭](https://www.typescriptlang.org/ko/docs/handbook/2/generics.html)을 사용하는 가장 기본적인 문제였다.
핵심은 어떤 타입이든 들어올 수 있다는것..
제네릭 타입은 타입 변수와 같다.
```ts
function identity<Type>(arg: Type): Type {
  return arg;
}
```
타입 변수는 유저가 준 타입을 캡처하고 이 정보를 나중에 사용할 수 있다.
위와 같이 identity라는 함수는 전달된 인자를 바로 반환한다.
그렇기에 Type이라는 특정 타입의 값이 전달될거고 Type이라는 특정 타입이 그대로 반환될걸 예상할 수 있다.


Question8
---

[교차타입](https://www.typescriptlang.org/docs/handbook/2/objects.html#intersection-types)을 사용하는 기본적인 문제였다.
한 가지 변수가 존재한다면 `User`, `Admin`에 type이라는 각각의 리터럴 타입이 존재한다는 것이다.
이런 형태의 타입을 교차시킬때 type: 'user' | 'admin' 이 된다.
하지만 문제는 `PowerUser` 는 교차된 type이 필요없고 본인만의 type이 필요하다.
그렇기에 이전 문제에서 사용했던 Omit을 통해 교차시킬때 'type'을 제외시킨 상태로 교차시켰다.

Question9
---
[제너릭](https://www.typescriptlang.org/ko/docs/handbook/2/generics.html)을 활용하는 문제이다.
가장 핵심적인 부분은 data의 타입이 예상되지 않는다는 것이었다.
generic을 사용하여 함수마다 예상되는 타입을 전달해주면 해결할 수 있었다.
단지 아쉬웠던 부분이 있다면 SuccessResponse에 전달된 타입의 배열을 예상했던 것이다.
```ts
type SuccessResponse<T> = {
    status: 'success';
    data: T[];
}
```
너무 User, Admin 케이스만 고려한 결과였다.
servertime, coffeeMachine까지 고려하면 SuccessResponse는 배열이 아닌 타입이 반환될 가능성이 존재했다.
```ts
type SuccessResponse<T> = {
    status: 'success';
    data: T;
}
```
위와 같이 변경했을때 더 유연하게 적용할 수 있었다.
만약 배열이 예상되면 상위에서 제너릭 변수에 직접 특정 타입의 배열을 전달해주면 된다.

### 2. 전략 평가

- 효과적이었던 것과 그 이유

세세한 회고를 작성했을때 확실히 한 문제 한 문제 정확히 이해해 나갈 수 있었던거 같다.
실제로 맞이할 패턴에 어떻게 대처해야할지에 대한 전략을 얻은거 같다.

- 비효과적이었던 것과 그 이유

문제 풀기에 많은 시간을 사용했다.
하지만 현재 단계에서는 지금 이 과정이 필요하다고 느낀다.
기본적인 베이스 지식을 늘리고 다양한 패턴에 대해서 알아가고 익숙해지는 시간이 필요한 시점이다.

### 3. AI 피드백

- 자신의 학습 전략에 대해 AI에게 피드백을 요청하고, 유용했던 제안 1가지 이상 기록

"문제 풀기에 시간이 많이 걸린다"는 것에 대한 AI 의 의견

> 막혔을 때 얼마나 고민하다가 답을 보는가?

너무 빨리 답을 보면 회고의 의미가 줄어들고, 너무 오래 붙잡으면 시간 대비 효율이 떨어진다.
15~20분 고민 후 힌트 → 다시 시도 → 그래도 안 되면 답 정도의 규칙을 정해두면 시간 관리에 도움이 될 거다.
(좀 더 체계적으로 접근해라.)

### 4. 다음 타임에 바꿀 것

- 유지할 것과 그 이유
지금처럼 문제를 풀어볼거 같다. 12번까지.

- 바꿀 것과 그 이유
문제를 푸는 과정을 체계적으로 진행할거 같다.
15분 제한을 두고 풀지 못했을때 AI에게 힌트를 받을것이다.
그럼에도 불구하고 15분 이내 풀지 못했을때는 답을 봐야겠다.

---

...

- 효과적인 학습이 왜 중요한가?
- 나의 기존 학습법 v1 떠올려보기
- 공유 및 피드백
- 효과적으로 학습하는 사람들은 어떤 모습을 하고 있나요?
- 효과적인 학습자의 특징 정리
- 학습법 v2 Refactor
- 학습법 v2 활용하여 실제로 학습해보기
- 학습 회고
- 공유
- 학습법 v3 세우기
- 회고
- 강의 피드백
