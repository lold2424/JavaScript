# 2 자바스크립트와 친해지기

# 1 개발환경 준비하기

## 크롬 브라우저 설치하기

해당 책에서는 크롬 브라우저를 사용한다 했기 때문에 기존에 깔아둔 크롬을 그대로 이용했다.

## 비주얼 스튜디오 코드 설치하기

해당 책에서는 비주얼 스튜디오 코드를 설치한다고 하였기에 기존에 깔아둔 비주얼 스튜디오 설정에서 조금만 수정하여 사용하였다.

# 2 비주얼 스튜디오 코드와 인사하기

## 작업 폴더를 설정하고 파일 열어 보기

### 실습 파일 내려받기

우선 이지스퍼블리싱 홈페이지로 들어가 자료실에서 실습파일을 다운하였다.

다운한 뒤 압축파일을 해제하면 된다.

참고로 DO IT시리즈의 책들은 여기에 대부분의 파일이 있어서 필자도 종종 들어가는 사이트이다.

### 작업 폴더 설정하기

비주얼 스튜디오 코드에서 폴더 열기를 눌러 작업 폴더를 설정해준다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled.png)

위 사진은 폴더 설정을 완료한 모습이다.

만약 코드를 두가지이상 비교를 하거나 동시에 작업할 경우 보기 편하도록 하는 기능이다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%201.png)

위 사진처럼 열 파일 및 코드를 우클릭하여 측면에서 열기를 누르거나 Ctrl + Enter키를 누르면 측면에 파일이 열려 동시에 작업하기 편하다.

## 라이브 서버 확장 기능 사용하기

### 라이브 서버 설치하기

왼쪽 메뉴에서 확장아이콘을 누르면 왼쪽에 확장 기능 목록이 나타난다.

사용 영역에는 현재 설치된 기능이, 권장 영역에는 비주얼 스튜디오 코드에서 권장하는 기능이 나타난다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%202.png)

검색 창에 Live Server를 입력하여 설치해준다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%203.png)

### 라이브 서버 실행하기

live-server.html을 눌러 편집 화면을 열고, 편집 화면의 빈 공간에 우클릭을 하여 Open with Liver Server를 눌러보자.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%204.png)

그러면 크롬 부라우저 화면에 live-server.html의 실행 결과가 바로 나타난다.

주소 표시줄에 나타난 127.0.0.1 숫자는 라이브 서버 확장 기능이 가상으로 만든 서버 주소이다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%205.png)

라이브 서버는 소스를 수정후 저장만 해도 웹 브라우저에 결과가 그대로 반영된다.

<body>태그를 찾아 태그 안에 내용을 추가해보자.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%206.png)

수정 한 후 Ctrl + S를 눌러 소스를 저장 후 크롬을 확인하면 바뀐것을 확인할 수 있다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%207.png)

# 3 자바스크립트 소스 작성하고 실행하기

자바스크립트 소스를 작성하는 방법은 2가지로 나뉜다.

## 1. HTML 문서 내에 자바스크립트 소스 작성하기

HTML 문서에 자바스크립트 소스를 작성하려면 문장을 입력하듯이 <script> 태그 안에 작성하면 된다.

단 아래 규칙에 주의하여 작성하여야 한다.

1. <script> 태그는 HTML 문서 어디에든 사용이 가능하다.
2. <script> 태그는 한 문서 내에서 여러 개를 사용해도 된다.
3. <script> 태그는 삽입된 위치에서 소스가 실행된다.

### <script> 태그와 함께 작성된 자바스크립트 소스 확인하기

change-1.html 파일을 열어 <script> 태그의 위치를 확인해보자.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%208.png)

<script> 태그 안에 자바스크립트 소스가 들어있는걸 확인이 가능하다.

### 자바스크립트 작동 결과 확인하기

자바스크립트가 포함된 HTML 문서는 브라우저에서 확인이 가능하다.

change-1.html을 열어 브라우저 화면에 나타난 ‘자바스크립트’라는 글자를 누르면 작성한 자바스크립트 소스가 적용되어 글자 색이 변경된다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%209.png)

<script> 태그는 HTML 문서 어디에 있던 상관없다.

하지만 매번 <script>의 위치를 고려하는 것은 번거롭기 때문에 보통 HTML문서 내용이 끝나는 </body> 태그 앞에 삽입한다.

때문에 이제부터는 <script> 태그는 </body> 앞에 삽입하도록 하겠다.

## 외부 스크립트 파일을 연결하는 이유

HTML 문서와 자바스크립트 소스를 분리하여 작합하기 위해 외부 스크립트 파일을 연결하는 방법을 알아보겠다.

보통 **실무에서는 자바스크립트 소스를 따로 작성하여 HTML 문서에 연결하는 것을 ‘외부 스크립트 파일을 연결한다’**라고 말한다.

**왜 이런 작업이 필요할까?**

규모가 큰 프로젝트인 경우에는 분리하는것이 더 효율적이기 때문이다.

100개의 HTML 문서가 있다면 이를 자바스크립트를 일일히 넣기보다는 따로 만들어 연결하는게 더 효율적이기 때문이다.

> 글자 색을 파란색에서 빨간색으로 바꿔 주는 자바 스크립트를 5개의 HTML 문서에 사용시 각 HTML 문서에 복사 붙여넣기를 하면 된다.
> 

하지만 위의 예시처럼 5개가 아닌 100개가 넘는 문서일 경우에는 수작업이 매우 번거로워진다.

때문에 보통 자바스크립트를 따로 작성해 HTML 문서에 연결한다.

**해당 방법은 HTML 문서와 자바스크립트 코드가 섞이지 않는 장점도 있어 실무에서 많이 사용한다.**

## 외부 스크립트 파일 연결하기

### js 파일 생성하기

js-file 폴더를 작업 폴더로 지정후 Ctrl + N을 눌러 새 문서를 만들어보자.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2010.png)

만든 문서를 Ctrl + S를 눌러 js - file - 02 - js 폴더에 저장한다.

그러면 탐색기에서 change.js 파일이 생긴것을 확인이 가능하다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2011.png)

### 자바스크립트 소스 코드 저장하기

탐색기 화면에서 change-2.html을 누르고 <script> 태그 안에 들어 있는 자바 스크립트 소스를 드래그후 우클릭하여 [잘라내기]를 선택한다. 또는 Ctrl + X를 눌러도 된다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2012.png)

그런 다음 <script> 태그와 </script> 태그를 전부 지우고 Ctrl + S를 눌러 저장한다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2013.png)

그 후 change.js 파일에 잘라낸 코드를 붙여넣기 해준 후 Ctrl + S로 저장해준다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2014.png)

### js 파일과 html 파일 연결하기

change-2.html을 다시 열고 앞에서 완성한 change.js 파일을 HTML 문서에 연결하면 된다.

</body> 태그 앞에 작성하면 된다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2015.png)

src 속성에 입력한 **“js/change.js”**의 뜻은 **js 폴더에 저장한 change.js 파일을 현재 HTML 문서에 불러오라는 뜻**이다.

라이브 서버를 사용해 change-2.html을 열어서 글자를 누르면 글자 색이 바뀐다면 잘 적용한것이다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2016.png)

# 4 나의 첫 번째 자바스크립트 프로그램

## 인사하는 브라우저 만들기

해당 JavaScript 책에서 나오는 문제들은 HTML 과 CSS가 완성되어 있는 파일을 제공한다.

때문에, 파일을 열어 자바스크립트 소스만 입력하면 된다.

greeting.html 파일을 라이브 서버로 열어보자

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2017.png)

열게되면 해당 화면이 나타나는데 우리는 이 파일을 수정하여 제대로 인사하는 프로그램을 만들어 볼것이다.

아까 열었던 greeting.html 파일에 소스를 입력 후 Ctrl + S를 눌러 저장한다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2018.png)

여기서 var name은 var을 통해서 name이라는 **변수를 선언한다는 뜻**이다.

**name에 promt**를 사용해서 **문자열을 입력**받는다.

**document.write**는 자바스크립트의 출력문이다.

**<b>** 태그는 bold 태그의 약자로 **글자를 굵게 표시**해주고 **<big>** 태그는 **글자를 크게 표시**해준다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2019.png)

그리고 아까 열어둔 페이지로 돌아가면 이름을 입력하라는 문구가 나타난다.

이 문구에 자신의 이름을 입력 한 후 [확인]을 누르면 자신의 이름을 환영한다는 사이트가 나온다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2020.png)

greeting.html의 소스의 구조를 분석해보자.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2021.png)

1. 1번 줄의 <!DOCTYPE html>는 HTML 문서의 시작을 알리는 HTML 태그이다.
    
    이후 2번 줄과 22번 줄 사이의 html 태그 사이의 내용을 HTML5 표준에 맞춰 분석해준다.
    
2. HTML 분석기는 주로 HTML 태그의 순서와 포함 관계를 확인한다.
    
    즉 HTML 분석기를 통해 크롬 브라우저의 <head> 태그 안에는 3개의 <meta> 태그와 <title>, <style> 태그가 있고 <body> 태그 내에는 <h1>, <script> 태그가 있다는 것을 알 수 있다.
    
3. CSS 분석기는 HTML 분석기가 태그 분석을 끝낸 다음 <style> 태그 사이의 스타일 정보를 분석한다.
4. 마지막으로 자바스크립트 해석기가 <script> 태그 사이의  자바스크립트 소스를 해석한다.

# 5 자바스크립트의 입력과 출력

## 크롬 브라우저의 콘솔 도구와 함께 공부하기

입, 출력을 알아보기 전 간단한 실습을 위해 자주 사용하게 될 크롬 브라우저의 콘솔 도구에 대해 알아보자.

크롬 브라우저를 실행하여 주소 표시줄에 about:blank라고 입력하면 빈 창이 나오고 Ctrl + Shift + J (또는 F12)를 눌러주면 콘솔 창이 열린다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2022.png)

이후 Console 창에 var age = 20; 코드를 입력후 Enter키를 입력하면 undefined가 표시된다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2023.png)

콘솔에 자바스크립트 소스를 입력시 다음줄에는 결괏값을 출력하는데 오류가 없고 마땅한 출력값이 없다면 undefined를 출력한다.

## 사용자 입력값 받기 - prompt() 함수

사용자에게 어떤 값을 입력받을 때 사용하는 prompt() 함수에 대해 알아보자.

pormpt() 함수를 실행시 사용자가 값을 입력 가능하도록 작은 창을 만들어 준다.

콘솔창에 prompt(); 를 입력해보자.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2024.png)

prompt()를 입력시 프롬프트 창이 나타나고 해당 창에 아무 말이나 입력해보자.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2025.png)

그러면 콘솔 창에서 입력한 값을 확인할 수 있다.

prompt() 함수를 사용시 소괄호 내에 따움표를 사용해 원하는 문장을 넣어 프롬프트 창에 표시할 수 있다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2026.png)

콘솔 창에 prompt(”이름을 입력하세요”, “윤혜진”) 코드를 입력하면 아래 사진처럼 프롬프트 창의 텍스트 필드 내 기본 값을 표시할 수 있다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2027.png)

## 알림 창으로 출력하기 - alert() 함수

웹 브라우저 화면에서 간단한 알림 내용을 표시하려 할 때 alert() 함수를 사용한다.

alert() 함수의 사용 방법은 소괄호 안에 원하는 내용을 따옴표로 감싸주면 된다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2028.png)

## 웹 브라우저 화면에 출력하기 - document.write() 함수

자바스크립트로 웹 브라우저에 출력하는 document.write()함수에 대해 알아보자.

해당 함수는 괄호 안의 내용을 크롬 브라우저 화면에 표시하는 역할을 담당한다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2029.png)

document.write() 함수는 prompt() 함수와 다르게 document. 가 함수 이름 앞에 붙어있다.

그 이유는 write() 함수가 docunemt 객체에 포함되어 있기 때문이다.

## 콘솔에 출력하기 - console.log() 함수

console.log() 함수는 관호 안의 내용을 콘솔 창에 출력한다. 사용 방법은 document.write() 함수와 같다.

아래의 소스를 입력해보자.

```jsx
var name = prompt("이름: ");
console.log(name + "님, 어서오세요!");
```

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2030.png)

## 크롬 브라우저 콘솔로 오류 찾아내기

콘솔에서 오류를 찾아내는 방법을 공부해보자.

js-time.html을 크롬으로 열게되면 오류가 발생하여 화면에 아무것도 표시되지 않는다.

콘솔창을 열어 확인하면 빨간색 글자로 오류 내용이 표시되어 있다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2031.png)

우측 혹은 아래에 js-time.html:19를 누르면 오류가 발생한 파일로 이동한다.

![Untitled](2%20%E1%84%8C%E1%85%A1%E1%84%87%E1%85%A1%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%B8%E1%84%90%E1%85%B3%E1%84%8B%E1%85%AA%20%E1%84%8E%E1%85%B5%E1%86%AB%E1%84%92%E1%85%A2%E1%84%8C%E1%85%B5%E1%84%80%E1%85%B5%20b6d112c6b66e423aa481be7ec5eed149/Untitled%2032.png)

해당 화면에서 오류 개수와 오류 내용, 발생 위치를 확인할 수 있다.

document.write() 함수를 사용해야 하는 위치에 e를 적지 않았음을 알 수 있다.

버츄얼 스튜디오 코드로 돌아가 코드를 수정하고 저장하면 프로그램이 정상 작동됨을 확인이 가능하다.

![Untitled](https://github.com/lold2424/JavaScript/blob/main/JavaScript%20Do%20It/2%EC%9E%A5/2%EC%9E%A5%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%99%80%20%EC%B9%9C%ED%95%B4%EC%A7%80%EA%B8%B0/Untitled%2033.png)

# 6 자바스크립트 소스를 작성할 때 지켜야 할 규칙

## 1. 대소문자를 구별하여 소스를 작성한다.

자바스크립트는 sum, Sum, SUM을 모두 다르게 인식한다.

## 2. 읽기 쉽게 들여 쓰는 습관을 들인다

자바스크립트 해석기는 소스 처리시 들여쓰기를 신경 쓰지않으나, 읽기 편하기 위해서 들여쓰는 습관을 들이는게 좋다.

## 3. 세미콜론으로 문장을 구분한다

자바스크립트에서는 세미콜론을 사용하지 않더라도 잘 실행된다.

```jsx
var num1
var num2

var num1;
var num2;
```

하지만 줄바꿈을 하지않는다면 오류가 발생하니 세미콜론을 쓰는것이 좋다.

```jsx
var num1 var num2
// 오류 발생

var num1; var num2;
// 오류 발생하지 않음
```

## 4. 자바스크립트 소스에 메모를 하려면 주석을 사용한다

작성한 소스를 타인에게 설명하거나, 나중을 위해 안내 표시를 위해 주석을 사용한다.

주석은 2가지로 나뉜다.

### 1. 한줄 주석 기본형

```jsx
// 한 줄 주석은 이렇게 입력한다.
var today = new Date(); // 날짜를 가져온다
var h = today.getHours(); // 시를 추출한다
```

### 2. 여러 줄 주석 기본형

```jsx
/*
	현재 날짜를 가져와
	시와 분, 초로 추출하고
	화면에 표시하는 스크립트
*/
function sTartTime() {}
```

## 5. 식별자는 정해진 규칙을 지켜 작성한다.

식별자란 자바스크립트 문법의 핵심 요소인 변수, 함수, 속성 등을 구별하기 위해 이름 붙인 특정 단어를 의미한다.

```jsx
var name = prompt("이름을 입력하세요.")_
```

식별자의 첫 글자는 반드시 영문자나 밑줄, 또는 달러기호로 시작해야 한다.

두 단어 이상이 모여 하나의 식별자를 만들 경우 단어 사이에 공백 대신 하이픈이나 밑줄을 사용한다.

하이픈이나 밑줄없이 두 단어를 붙여 사용할경우 첫 단어는 소문자로 시작하고, 두번째 단어는 대문자로 시작한다.

```jsx
num1
_doSomething
checkTime()
```

## 6. 예약어는 식별자로 사용할 수 없다

예약어란 자바스크립트에 먼저 등록된 요소를 가르킨다.

var을 예로 들자면 var을 이용해서 변수를 선언하기 때문에 var로 식별어로 사용할 경우 오류가 발생한다.
