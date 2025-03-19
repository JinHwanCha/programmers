## 연관된 이슈

<!-- close #이슈변호 -->

## 풀이

<!-- 풀이 내용 작성 -->
- 차진환 풀이

function solution(numbers, num1, num2) {
    
    const length = Math.floor(Math.random() * 29) + 2; // 2 이상 30 이하
    const numbers = Array.from({ length }, () => Math.floor(Math.random() * 1001)); // 0 이상 1000 이하 랜덤 값
    const num1 = Math.floor(Math.random() * (length - 1)); 
    const num2 = Math.floor(Math.random() * (length - num1 - 1)) + num1 + 1; // num1보다 큰 값

    return numbers.slice(num1, num2+1);
}


## 질문

<!-- 없으면 생략 가능 -->