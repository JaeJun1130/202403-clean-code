# 4. 주석

우리는 코드로 의도를 표현하지 못해, 실패를 만회하기 위해 주석을 사용한다. 그러므로 주석이 필요한 상황에 처하면 곰곰이 생각하고, 상황을 역전해 코드로 의도를 표현할 방법이 없는지 고민해야 한다.

**부정확한 주석은 아예 없는 주석보다 훨씬 더 나쁘다.**

## 좋은 주석

[법적인 주석]

저작권 정보와 소유권 정보는 필요하고도 타당하다.

[정보를 제공하는 주석]

때로는 기본적인 정보를 주석으로 제공하면 편리하다.(예를 들어 추상 메서드가 반환할 값을 설명)

[의도를 설명하는 주석]

때때로 주석은 구현을 이해하게 도와주는 선을 넘어 결정에 깔린 의도까지 설명한다.

[의미를 명료하게 밝히는 주석]

때때로 모호한 인수나 반환값은 그 의미를 읽기 좋게 표현하면 이해하기 쉬워진다. 인수나 반환값이 표준 라이브러리나 변경하지 못하는 코드에 속한다면 의미를 명료하게 밝히는 주석이 유용하다.

[결과를 경고하는 주석]

다른 프로그래머에게 결과를 경고할 목적으로 사용되는 경우도 있다. 테스트 코드등에도 쓰이며 요즘은 JUnit4로 인해 @Ignore 에 속성을 문자열로 추가하여 표현한다.

[TODO 주석]

`앞으로 할 일` 을 //TODO 주석으로 남겨두면 편하다.

[중요성을 강조하는 주석]

자칫 대수롭지 않다고 여겨질 뭔가의 중요성을 강조하기 위해서도 주석을 사용한다.

## 나쁜주석

대다수 주석이 이 범주에 속한다. 일반적으로 대다수 주석은 허술한 코드를 지탱하거나, 엉성한 코드를 변명하거나, 미숙한 결정을 합리화 하는 등 프로그래머가 주절거리는 독백에서 크게 벗어나지 못한다.

[의무적으로 다는 주석]

모든 함수에 Javadocs를 달거나 모든 변수에 주석을 달아야 한다는 규칙은 어리석기 그지없다.

예를 들어 무조건 모든 함수에 Javadocs를 넣으라는 규칙 등이다.

[있으나 마나 한 주석]

쉽게 말해 너무 당연한 사실을 언급하며 새로운 정보를 제공하지 못하는 주석이다.

[주석으로 처리된 코드]

주석으로 처리된 코드는 다른 사람들이 지우기를 주저한다. 이유가 있어 남겨 놓았으리라고, 중요하니까 지우면 안된다고 생각한다.
