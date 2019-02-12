<p align="center"> 
  <img src="https://raw.githubusercontent.com/xpressengine/plugin-external_page/master/icon.png">
 </p>

# XE3 External Page Plugins
이 어플리케이션은 Xpressengine3(이하 XE3)의 플러그인입니다.
이 플러그인은 XE3에서 외부 페이지 출력 기능을 제공합니다.

## What can I do?

본 플러그인을 사용함으로, 내 FTP에 존재하는 HTML또는 PHP 또는 외부 위젯 등을 가져올 수 있습니다.
본 플러그인은 아래의 기능을 지원합니다.

* 내 FTP(또는 서버)에 존재하는 HTML/PHP 파일 출력
* 외부 페이지 embed 기능 (가져오기)



# Usage


### Installtaion

### Caution

따로 설정을 통해 활성화 하지 않아도 되지만, 다른 이유로 인해 재설치 또는 재활성화 해야하는 경우에 따라주세요.

#### FTP로 설치하는 경우
1. xe3경로/plugins 폴더에 압축을 푼 상태로 업로드 하거나,
   SSH(터미널)에서 ``unzip external_page.zip`` 을 통해 압축을 풀어주세요.
2. 관리자 대시보드( domain/settings )에 접속합니다.
3. ``플러그인 & 업데이트 > 플러그인 목록`` 에서 ``External Page`` 모듈에 체크를 한후 ``켜기`` 버튼을 눌러주세요.
4. 활성화 완료!



### 외부 페이지를 추가하는 방법
관리자 > 사이트 맵> 사이트 메뉴 편집에서 `아이템 추가` 기능으로 외부페이지를 추가해서 사용합니다.
외부 페이지는 아래 순서로 가능합니다.
1. `아이템 추가` 클릭
2. External Page Module 선택 후 하단에 `다음` 클릭
3. itemURL, Item Title 등 세부사항 입력
4. 등록

### 외부 페이지를 삭제하는 방법
관리자 > 사이트 맵> 사이트 메뉴 편집에서 `아이템 제거` 기능으로 외부페이지를 삭제할 수 있습니다.
외부 페이지 삭제는 아래 순서로 가능합니다.
1. 삭제할 아이템 이름 클릭
2. 상단의 ``아이템 삭제하기`` 클릭
3. 아이템 삭제 항목에서 삭제 클릭
4. 삭제 완료


## Installation specification
* Minimum installation environment
   XE3, PHP 7.0 or later
* Recommended installation environment
   XE3, PHP 7.1 or later



