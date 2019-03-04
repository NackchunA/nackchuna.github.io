---
layout: post
comments: true
categories: React&nbsp;Start
---
# QuickStart for Windows

&nbsp;

### 리액트 시작을 위해 필요한 것들

리액트 프로젝트를 제대로 작업하려면 여러분의 컴퓨터에

#### <a href='https://nodejs.org/ko/download/'>Node.js</a>
#### <a href='https://yarnpkg.com/en/docs/install#windows-stable'>Yarn</a>
#### <a href='https://code.visualstudio.com/'>VSCode</a>
#### <a href='https://gitforwindows.org/'>Git Bash</a>

가 필요합니다. 각 링크에서 다운로드 후 설치하시면 됩니다.

&nbsp;

### 참고 사항
명령프롬프트 실행법은 윈도우키 + R 로 실행창을 띄워서<br>
```
cmd
```
를 입력해 주면 됩니다.

&nbsp;

### create-react-app 설치

create-react-app 은 리액트 앱을 만들어 주는 도구입니다.<br>
명령프롬프트에
```
yarn global add create-react-app
```
를 입력해 줍니다.<br><br>
![](/assets/img/React-QuickStart00.png)<br>
이런 화면이 뜨면 설치 완료입니다.
&nbsp;

### create-react-app 사용

명령프롬프트에 들어가 원하는 작업 폴더로 이동한 후에
```
create-react-app hello-react
```
를 입력해 줍니다.<br><br>
자동으로 필요한 세팅이 완료 되면 다음과 같이 뜹니다.<br>
![](/assets/img/React-QuickStart01.png)<br>
해당 폴더에서 화면에 표시된 것과 같이 입력해 주면 됩니다.
```
cd hello-react
yarn start
```
를 입력하면 리액트 프로젝트가 시작되고, 브라우저창에 기본 리액트 페이지가 나타나게 됩니다.<br>
![](/assets/img/React-QuickStart02.png)<br>
![](/assets/img/React-QuickStart03.png)<br>


# QuickStart for Mac
## 1. Node install
* Nodejs - Mac(OSX)에 nodejs를 설치하는 최고의 방법 : http://hochulshin.com/node-install-osx/
1. Ruby Install
```ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
2. node install by brew
```
brew install node
```
3. npm Install
```
echo "export PATH=$PATH:/usr/local/Cellar/node/11.10.1/bin" >> ~/.profile
. ~/.profile
```

## 2. Make Test project
```
npm install -g create-react-app

create-react-app my-app
cd my-app/
npm start


출처: https://aspdotnet.tistory.com/2001 [심재운 블로그]
```


# QuickStart for Linux
