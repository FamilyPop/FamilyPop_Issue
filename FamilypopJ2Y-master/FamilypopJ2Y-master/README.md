# FamilypopJ2Y

####################### 12/11 각 issue 별 해결 일정 정리

토크 시작 후, 서버 화면 터치 시 서버 중지 12/14~12/18

Bubble 많아졌을때 속도 저하 현상 12/21~12/24

Bubble 많아졌을때 서버종료 현상   12/28~1/1

서버 가 동적으로 사용자 를 받을수있도록 수정 1/4 ~ 1/11

사용자가 동적으로 서버에 접속 종료를 할수있도록  1/12~1/19

서버에서 동적으로 로케이터를 받을수있도록 수정 1/19 ~1/22

서버와 로케이터의 테이블 상의 위치에 대한 정의를 Localizing 시에는 반영 ~2015-01-29

서버에서 로케이터 서버가 없을 시 접속거부 (실행제한 ) 안내 ~2015-01-29

사용자가 tictactoe 시도시 로케이터가 없으면 접속 거부 ~2015-01-29

로케이터 있는지 체크 ui (접속거부) ~2015-01-29

사용자 서버 접속시 컬러 선택  ~2015-01-29

사용자의 서버 접속시도시 상태  ~2015-01-29

사용자의 서버 접속시도시 상태 ui  ~2015-01-29

서버 의 사용자 허용치가 넘어가지 않게 수정 ~2015-01-29

접속 시도시 접속 버튼을 눌러지지 않게 수정 ~2015-01-29

로케이터 종료시 사용자에게 접근거부 안내 ~2015-01-29

서버 종료시 사용자에게 접근거부 안내 ~2015-01-29

접속자 이름이 이상하게 출력되는 현상 ~2015-01-29




####################### 12/03 
패밀리 팝 중지 문제 
- 토크 시작 후, 서버 화면을 터치 시 서버 중지
- Family bomb 실행 중, bubble이 많아서 느려지고 있는 상황에서 서버 중지 


사용성 관련
- 서버, 클라이언트, 로케이터 중 하나의 폰만 중지되어도 모두 재접속 해야 함, 
Application의 재시작 없이 리셋 기능 요망 혹은 자동 재시작 기능 요망, 동적으로(패밀리팝 진행 도중) 사용자가 서버에 접속하거나 접속을 끊어도 원활하게 패밀리팝이 실행될 수 있도록 개선 요망 


사용자 접속
- 사용자 접속 시 접속 버튼을 눌러도 현재 상황에 대한 피드백이 없어 IP가 잘못되었는지, 현재 징행 중인지 등에 대한 상황파악 불가
- 사용자 접속 시 접속 버튼을 여러 번 눌렀을 때 접속자 이름이 제대로 나타나지 않는 경우가 있음


Localization 제한
- 데모 버전에서 Localization에 관련 된 UI는 있으나 기능 상에 반영되지는 않도록 개발되었음. 즉, 서버와 로케이터의 테이블 상의 위치에 대한 정의에 대한 부분이 Localizing 시에는 반영되지 않았음 



틱택토 관련
-로케이터 추가 문제 : 대화 시작 시 로케이터가 없는 상태로 시작했을 경우, 틱택토로 넘어가면 클라이언트를 로케이터로 변경 불가. 이 상황에서는 앱을 중지시키고 새로 접속해야 함, 동적으로 로케이터를 설정 가능하도록 개선 요망