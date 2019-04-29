# 대괄호 오류 전처리기 무시

이 사전처리기에서는 백셋 오류를 무시하도록 스크립트를 설정하십시오.  
이것은 당신의 스크립트를 어떤 식으로든, 모양을 만들거나 또는 마법처럼 수정하지 않는다. 그것은 오류 로그를 압축한다.

## 호출

스크립트 파일 안에 `#ignoreBracketErrors `을 넣어 대괄호 오류 사전 처리기 무시를 호출할 수 있다.  
이 사전처리기는 파일마다 다르기 때문에 한 파일에 호출하는 것은 다른 파일에는 영향을 미치지 않는다.(적어도 처리기에 관한 것은 아니다.)

## 그것이 하는 일

파일에 사전처리기가 호출되면 대괄호 오류에 대한 모든 오류 로그가 압축된다.  
이것은 어떤 식으로든 영향을 받는 선을 바꾸지 않는다. 대신, 유일한 변화는 당신의 로그에 관련된 줄이 포함되어 있지 않다는 것이다.