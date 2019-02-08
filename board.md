이미지

# 게시판 플러그인
이 플러그인은 XpressEngine3(이하 XE3)의 플러그인 입니다.

사이트 이용자가 컨텐츠를 생산할 수 있는 모듈을 제공합니다.
사이트 관리자는 한 페이지에 표시될 글 수를 설정하거나, 댓글의 사용 유무 등을 설정할 수 있습니다.


## 제공되는 기능
* 분류를 만들어 게시글 별 분류가 가능합니다.
* 게시판을 익명 게시판으로도 사용할 수 있습니다.
* 추천과 비추천을 사용할 수 있습니다.
* 관리자는 새 글을 이메일로 볼 수 있습니다.

## Installation
이 플러그인을 사용하려면 먼저 XE3가 설치 되어 있어야 하며, 플러그인을 XE3에 설치 해야 합니다.

### SSH(터미널)를 사용하여 설치
```
$ php artisan plugin:install board
```

### 웹 페이지를 사용하여 설치

-   관리자 > 플러그인 & 업데이트 > 플러그인 목록 내에 새 플러그인 설치 버튼 클릭
-   `board`  검색 후 설치하기

### FTP를 사용하여 설치

-   다음의 페이지에서 다운로드
    -   [https://store.xpressengine.io/plugins/board](https://store.xpressengine.io/plugins/board)
    -   [https://github.com/xpressengine/plugin-board/releases](https://github.com/xpressengine/plugin-board/releases)
-   프로젝트의  `plugins`  디렉토리 아래  `board`  디렉토리명으로 압축해제
-   `board`  디렉토리 이동 후  `composer dump`  명령 실행

	``사이트 관리 페이지 > 플러그인 > 플러그인 목록 `` 페이지에서 `Board`` 플러그인을 활성화 합니다.

## Usage

관리자 > 사이트 맵> 사이트 메뉴 편집에서  `아이템 추가`  기능으로 게시판을 추가해서 사용합니다. 게시판 추가는 아래 순서로 가능합니다.

1.  `아이템 추가`  클릭
2.  Board 선택 후 하단에  `다음`  클릭
3.  itemURL, Item Title 등 세부사항 입력
4.  등록


## License

이 플러그인은 LGPL라이선스 하에 있습니다.  [https://opensource.org/licenses/LGPL-2.1](https://opensource.org/licenses/LGPL-2.1)
