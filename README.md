# wanted_challenge
프리 온보딩 챌린지
사전과제 

Q1. 내가 생각하는 클린 코드란?
다른 사람이 이해하기 쉬운 코드

Q2. 내가 생각하는 (프론트엔드에서의) 클린 코드란?
리액트 기준으로 폴더링이 잘 되어있고 컴포넌트가 잘 나눠져 있는 코드.
코드 자체에서 로직은 비슷하다고 생각해서 범위를 넓게 가져가서 구조 단위에서 살피는게 좋다고 생각한다.

Q3. 내가 클린코드보다 중요하게 생각하는 것은?
기획의도에 맞는 기능 구현

Q4. 다음 중 선호하는 방식과 그 이유는?
1.
Tab vs Space

-> Tap
굳이 스페이스를 2 or 4번 누를 이유가 없다.

2.
세미콜론 O vs 세미콜론 X

-> 세미콜론 O
을 구분해준면 훨씬 보기 좋다.

4.
count++; vs count += 1; vs count = count + 1;

-> count++;
1의 경우는 count++가 있는데 굳이 다른 것을 쓸 필요가 없다. 만약 +2나 +3이 있다면 2,3번 옵션 고려. 나느 2번 옵션 선택.

5.
if (isLogin) {} vs if (isLogin === true) {}

-> isLogin === true
다른 사람과 함께 이해해야하기에 직관적인 코드가 좋다. 굳이 값 존재 유무보다가는 ture, false를 따지는 문제이기 때문에 명확하게 명시하는 것이 좋다. 코드 읽을 때 논리 구조 이해 이상으로 머리를 쓰게 만드는 것은 비효율적이라고 생각.

6.
isLogin && <HelloWanted /> vs isLogin ? <HelloWanted /> : <></> vs isLogin ? <HelloWanted /> : null vs isLogin ? <HelloWanted /> : undefined

-> 별 상황 조건이 없다면 1번을 쓰겟으나 null 따져야할 경우에 따라 선택할 것이다. undefined는 리액트에서 사용할 일이 있을지 모르겠다.
