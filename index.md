# 개발자를 위한 mac 활용하기

## 홈브루 설치하기
app스토어외 필요한 맥용 응용프로그램을 쉽게 설치할 수 있도록 mac생태계에서는 homebrew를 사용하고 있다.
공식 홈페이지는 `https://brew.sh/index_ko`로 접속을 하면 됩니다.

터미널을 실행하여 다음과 같이 입력을 합니다.
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## 개발언어 설치하기

### php 설치하기
홈브루를 이용하여 맥에 최신의 php를 설치합니다.

기존 시스템에 php가 설치가 되어 있는지 확인을 해봅니다.
```
% php -v            
```

홈브루를 통하여 php를 설치합니다. 홈브루 사이트에서 php를 입력하면 어떤 버젼의 패키지가 설치될 것인지 미리 알 수 있습니다.

[](./images/brew_php_01.png)

php 를 설치합니다.

```
brew install php
```

## 데이터베이스

### Mysql 설치



