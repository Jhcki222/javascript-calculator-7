# javascript-calculator-precourse

구현 기능 목록

#1 입력 문자열 파싱 기능
입력받은 문자열에서 숫자를 추출하고, 기본 구분자인 쉼표(,)와 콜론(:)을 기준으로 구분한다.
입력이 빈 문자열일 경우 0을 반환한다.

#2 기본 구분자를 사용한 덧셈 기능
쉼표(,)와 콜론(:)을 구분자로 사용해 문자열 내의 숫자들을 더한 값을 반환한다.

#3 커스텀 구분자 처리 기능
문자열 맨 앞에 "//"와 "\n" 사이에 위치한 커스텀 구분자를 기준으로 문자열을 분리하여 덧셈한다.

#4 숫자 이외의 입력에 대한 예외 처리
입력 값이 잘못된 형식이거나 숫자가 아닐 경우, [ERROR]로 시작하는 오류 메시지를 출력하고, 프로그램을 종료한다.

위 기능별로 계산기를 구현한다.
기능 목록 단위로 커밋을 추가한다.
e.g. feat#1 입력 문자열 파싱 기능 추가

커밋 규칙

<type>(<scope>): <subject>
<BLANK LINE>

<body>
<BLANK LINE>
<footer>

<type> 종류

feat: 새로운 기능 추가
fix: 버그 수정
refactor: 코드 리팩토링
test: 테스트 추가 및 수정
style: 코드 포맷팅, 세미콜론 누락 등 스타일 변경
docs: 문서 수정
chore: 빌드 업무 수정, 패키지 매니저 수정 등 기타 변경
perf: 성능 개선 관련 수정
