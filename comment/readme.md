<p align="center"> 
  <img src="https://raw.githubusercontent.com/xpressengine/plugin-comment/master/icon.png">
 </p>

# 댓글 플러그인
이 플러그인은 Xpressengine3(이하 XE3)의 플러그인입니다.
이 플러그인을 사용하여, 댓글 기능을 사용할 수 있습니다.


## 어떤 기능을 제공하나요?

본 플러그인을 사용하여 댓글 기능을 사용할 수 있습니다.
아래의 강력한 기능을 사용해보세요!

* 최대 7Depth까지 지원하는 기본 스킨
* 자유로운 소통을 위한 파일첨부 기능


# 사용방법

## 설치
본 플러그인은 XE3에 기본 포함된 플러그인입니다.
따로 설정을 통해 활성화 하지 않아도 되지만, 다른 이유로 인해 재설치 또는 재활성화 해야하는 경우에 따라주세요.

#### FTP로 설치하는 경우
1.  xe3경로/plugins 폴더에 압축을 푼 상태로 업로드 하거나, SSH(터미널)에서  `unzip comment.zip`  을 통해 압축을 풀어주세요.
2.  관리자 대시보드( domain/settings )에 접속합니다.
3.  `플러그인 & 업데이트 > 플러그인 목록`  에서  `댓글`  모듈에 체크를 한후  `켜기`  버튼을 눌러주세요.
4.  활성화 완료!


### 권한을 설정하는 방법
각 게시판의 댓글 모듈에 권한을 설정하거나, 확장 필드를 설정 하는 등의 설정이 가능합니다.

1. 권한을 설정할 게시판의 설정을 클릭 합니다.
2. ``게시판 상세 설정``에 존재하는 ``댓글`` 설정 란의 설정을 눌러주세요.
3. 관리탭의 ``관리``탭을 눌러주세요.
4. 권한을 설정한 다음, 저장을 눌러주세요.
5. 권한 설정 완료!

### 스킨을 설정하는 방법
각 게시판의 스킨을 바꾸어서 적용할 수 있습니다.
1. 댓글 스킨을 변경할 게시판의 설정을 클릭 합니다.
2. ``게시판 상세 설정`` 에 존재하는 ``댓글``설정 란의 설정을 눌러주세요.
3. 관리탭의 ``스킨`` 탭을 눌러주세요.
4. 원하는 스킨을 클릭해 활성화 해주세요.
5. 스킨 지정 완료!


### 확장 필드 추가 및 삭제 방법
각 댓글에도 이제, 확장 필드를 추가하여 작성하거나, 원하는 정보를 받을 수 있습니다.

1. 확장 필드를 추가할 게시판의 설정을 클릭합니다.
2. ``게시판 상세 설정`` 에 존재하는 ``댓글`` 설정 란의 설정을 눌러주세요.
3. 관리 탭의 ``확장 필드`` 탭을 눌러주세요.
4.  오른쪽 추가버튼을 누릅니다.
5.  입력할 확장필드의 종류를 선택합니다. (확장 필드의 정보는 하단에 있습니다.)
6.  확장 필드의 고유 ID(본 게시판에서만 쓰이는 ID)를 입력 후, 라벨(확장필드의 이름)을 입력 합니다.
7.  사용할 것인지의 사용 여부와, 필수 여부를 체크한 후, 스킨을 선택하여 등록합니다.
8.  댓글을 쓸때에 확장 필드가 적용 되었는지 확인합니다.
9.  완성!

#### 확장 필드 종류

-   Category - (분류/게시글의 종류)
-   Number - (숫자 유형의 데이터)
-   Text - (글자 유형의 데이터_
-   boolean - (불리언 / 참거짓)
-   Address - (주소/ 동호수)
-   Cell phone number - (휴대폰 번호)
-   Textarea - (텍스트 입력 탭)
-   Email - (이메일 주소)
-   Url - (링크형태의 주소/자동링크됨)

### 토글메뉴 관리

댓글에 존재하는 휴지통 기능 또는 신고 토글 메뉴를 관리할 수 있습니다.

1.  토글메뉴를 관리할 게시판 상단의 톱니바퀴 또는 설정을 클릭 합니다.
2. ``게시판 상세 설정`` 에 존재하는 ``댓글`` 설정 란의 설정을 눌러주세요.
3.  관리 탭에 있는  `토글 메뉴`  탭을 클릭 합니다.
4.  사용하지 않을 토글을  `Off`로 탭을 클릭한 후 저장을 클릭해주세요.
5.  설정 완료!


## 요구/최소 사양
* Minimum installation environment : XE3, PHP 7.0 or later, Require core version

* Recommended installation environment : XE3, PHP 7.1 or later, Require core version
