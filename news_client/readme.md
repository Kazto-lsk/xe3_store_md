<p align="center"> 
  <img src="https://raw.githubusercontent.com/xpressengine/plugin-news_client/master/icon.png">
 </p>

# XE3 News Client Plugins
이 어플리케이션은 Xpressengine3(이하 XE3)의 플러그인입니다.
이 플러그인은 XE3의 공식 홈페이지 소식을 빠르게 전달해주는 역할을 합니다.

## What can I do?

본 플러그인을 사용하여, XE3 공식 홈페이지의 소식을 남들보다 다르게 빠른속도로 얻을 수 있습니다.

# Usage


### Installtaion

### Caution
본 플러그인은 XE3에 기본 포함된 플러그인입니다.
따로 설정을 통해 활성화 하지 않아도 되지만, 다른 이유로 인해 재설치 또는 재활성화 해야하는 경우에 따라주세요.

### SSH(콘솔/터미널)로 설치하는 경우 
```
$ php artisan plugin:install plugin-news_client
```



### Web에서 설치하는 경우

-   관리자 > 플러그인 & 업데이트 > 플러그인 목록 내에 새 플러그인 설치 버튼 클릭
-   ``news client``  검색 후 설치하기

### FTP로 설치하는 경우
1. xe3경로/plugins 폴더에 압축을 푼 상태로 업로드 하거나,
   SSH(터미널)에서 ``unzip news client.zip`` 을 통해 압축을 풀어주세요.
2. ``news client`` 폴더로 이동 후 ``composer dump``명령을 실행 해 주세요
3. 관리자 대시보드( domain/settings )에 접속합니다.
4. ``플러그인 & 업데이트 > 플러그인 목록`` 에서 ``새소식`` 모듈에 체크를 한후 ``켜기`` 버튼을 눌러주세요.
5. 활성화 완료!




## Installation specification
* Minimum installation environment
   XE3, PHP 7.0 or later
* Recommended installation environment
   XE3, PHP 7.1 or later


