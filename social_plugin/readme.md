<p align="center"> 
  <img src="https://raw.githubusercontent.com/xpressengine/plugin-social_login/master/icon.png">
 </p>

# XE3 Social Login
이 어플리케이션은 Xpressengine3(이하 XE3)의 플러그인입니다.
이 플러그인은 XE3에서 Social Login 기능을 제공합니다.

<p align="center"> 
  <img src="https://raw.githubusercontent.com/xpressengine/plugin-social_login/develop/social_preview.PNG">
 </p>
 

## What can I do?

본 플러그인을 사용함으로, SNS 계정으로 로그인하는 OAuth 기능을 제공할 수 있습니다.
보다 손쉬운 회원가입으로 회원 유치를 할 수 있습니다.

본 플러그인은 아래의 기능을 지원합니다.

* 페이스북 계정으로 로그인
* 네이버 아이디로 로그인
* 트위터 계정으로 로그인
* 깃허브 계정으로 로그인
* 이메일 계정으로 로그인 (기본 로그인)
   (추천만 사용하거나, 비추천만 사용할 수도 있으며, 둘다 사용할 수도 있습니다.)


# Usage


### Installtaion

### Caution
본 플러그인은 XE3에 기본 포함된 플러그인이 아닙니다.
설치할때에는 본인의 웹사이트와 동일한 환경의 테스트 환경을 만든 후 충분한 테스트 이후 적용하시기 바랍니다.

### SSH(콘솔/터미널)로 설치하는 경우 
```
$ php artisan plugin:install social_login
```

### Web에서 설치하는 경우

-   관리자 > 플러그인 & 업데이트 > 플러그인 목록 내에 새 플러그인 설치 버튼 클릭
-   `social_login`  검색 후 설치하기

### FTP로 설치하는 경우
1. xe3경로/plugins 폴더에 압축을 푼 상태로 업로드 하거나,
   SSH(터미널)에서 ``unzip social_plugin.zip`` 을 통해 압축을 풀어주세요.
2. 관리자 대시보드( domain/settings )에 접속합니다.
3. ``플러그인 & 업데이트 > 플러그인 목록`` 에서 ``소셜 플러그인`` 모듈에 체크를 한후 ``켜기`` 버튼을 눌러주세요.
4. 활성화 완료!


### SNS 토큰을 설정 & 발급 받는 방법

``관리페이지 > 회원 > 소셜 로그인``에서 사용하려는 서비스의 ``소셜로그인 프로바이더 설정``을 등록 후 사용할 수 있습니다.

``소셜로그인 프로바이더 설정``에서 서비스 별로 발급한 client_id와 client_secret 값을 입력할 수 있으며, 각 서비스의 애플리케이션 등록 시 필요한 callback url을 확인할 수 있습니다.

### plug-in settings
* Naver의 네아로(네이버 아이디로 로그인) 서비스는 [이곳](https://developers.naver.com/apps/#/list) 에서 관리 & 생성 할 수 있습니다.
* Facebook의 로그인 API는 [이곳](https://developers.facebook.com/apps/)에서 관리 & 생성 할 수 있습니다.
* Twitter의 로그인 API는 [이곳](https://developer.twitter.com/en/apps)에서 관리 & 생성 할 수 있습니다.
* Github의 로그인 API는 [이곳](https://github.com/settings/developers)에서 관리 & 생성 할 수 있습니다.
* Google의 로그인 API는 [이곳](https://console.developers.google.com/)에서 관리 & 생성 할 수 있습니다.

### 스킨을 설정하는 방법
소셜로그인의 스킨을 변경할 수 있습니다.
스킨을 제작, 변경 하려면 아래를 따라주세요.

1. ``관리페이지 > 회원 > 소셜로그인`` 을 클릭해주세요.
2. 최상단의 ``스킨``란에 있는 사용하려는 스킨을 클릭해주세요.
3. 스킨 바로 아래의 저장버튼을 누르면 완료!

## Installation specification
* Minimum installation environment
   XE3, PHP 7.0 or later
* Recommended installation environment
   XE3, PHP 7.1 or later



