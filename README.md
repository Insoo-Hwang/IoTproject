# IoTproject


-프로젝트 개요

최근 사물인터넷이 많이 보급되면서 점점 스마트 홈과 같은 사물인터넷 기술이 우리의 삶에 자리 잡기 시작하였다. 그로 인하여 사물의 상태를 확인하는 일(가스밸브 확인, 집 안 온도 확인 등), 제어하는 일 등을 휴대폰이라는 매체 하나로 할 수 있는 시대가 도래하였다. 그러나 아직 학교 강의실에는 위와 같은 시스템이 정착되지 않았고 IoT 클라우드 플랫폼을 이용한다면 좀 더 간편하고 편리한 수업환경이 조성되지 않을까? 라는 생각에 스마트 강의실을 기획하게 되었다. 스마트 강의실은 명시적인 출석 체크, 온도 체크를 통한 에어컨 on/off 여부 결정, 수업 중 질문 유무를 교수의 이메일로 전송 및 LED를 통한 알림의 기능을 갖추어 기존보다 간편하고 편리한 환경에서 수업을 듣고 수업을 진행하는 환경이 구축될 것으로 예상한다.

-구조도

![슬라이드1](https://user-images.githubusercontent.com/70841847/144699576-f37e23f7-34c5-44c0-9599-e9caec0bd22f.JPG)

-주요 기능

1. Firebase를 이용하여 사용자 관리(교수만 사용할 수 있는 영역과 학생도 사용할 수 있는 영역 구분, 게시글 작성시 사용자 구분, 로그인 시스템)
2. 자유게시판을 통해 수업과 관련된 글 게시 가능
3. 출석확인 시스템을 통해 학생이 직접 출석체크를 할 수 있고 교수는 이를 안드로이드 앱으로 실시간 조회 및 바람직하지 않은 출석에 관하여 제어 가능
4. 강의실 온도 확인을 통해 에어컨 ON/OFF 여부를 객관적으로 판단 가능
5. 수업 중 질문 여부를 LED를 통해 파악 가능하고 수업 중 파악하지 못하였다면 교수는 앱과 이메일을 통해 수업 중에 질문이 발생하였는지 확인 가능

-실행 화면

