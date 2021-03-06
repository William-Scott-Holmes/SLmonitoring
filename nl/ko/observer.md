관리자는 해당 디바이스의 현재 및 과거 상태를 한 위치에서 전체적으로 볼 수 있습니다.

사용자 스토리:

    모든 사용자가 기존 보기와 관찰자 베타 간에 "대역폭" 및 "사용량" 탭을 빠르게 전환할 수 있습니다(베타만 해당).

    모든 사용자가 제어 포털을 통해 관찰자 베타의 환경에 대한 피드백을 제공할 수 있습니다(베타만 해당).

    모든 사용자가 블로그 게시물에 액세스하여 베타 환경 내부의 관찰자 작업에 대해 자세히 알아볼 수 있습니다(베타만 해당).

    사용자에게는 가상 서버에 대한 인프라 리소스 지표를 저장하고 볼 수 있는 하나의 지정된 위치가 있습니다.

    1. 가상 코어당 CPU 사용률, %

    2. 네트워크-퍼블릭, 수신/발신, 바이트 수 및 패킷 수

    3. 네트워크-프라이빗, 수신/발신, 바이트 수 및 패킷 수

    4. 메모리 사용률, %

    5. 디스크 읽기, 바이트 수 및 오퍼레이션 수

    6. 디스크 쓰기, 바이트 수 및 오퍼레이션 수

    7. 전송 오류, 수신/발신, 수

    8. 디스크 대기 시간, 밀리초, 읽기 및 쓰기

    9. 로컬 디스크 사용률, % 및 사용된 바이트 수와 사용 가능한 총 바이트 수


    베어메탈 사용자는 다음 지표를 볼 수 있습니다.

    1. 가상 코어당 CPU 사용률, %

    2. 네트워크-퍼블릭, 수신/발신, 바이트 수 및 패킷 수

    3. 네트워크-프라이빗, 수신/발신, 바이트 수 및 패킷 수

    4. 메모리 사용률, %

    5. 디스크 읽기, 바이트 수 및 오퍼레이션 수

    6. 디스크 쓰기, 바이트 수 및 오퍼레이션 수

    7. 전송 오류, 수신/발신, 수

    8. 디스크 대기 시간, 밀리초, 읽기 및 쓰기

    9. 로컬 디스크 사용률, % 및 사용된 바이트 수와 사용 가능한 총 바이트 수

    10. RAID 경보, 0/1

    11. 코어 온도, 화씨 도

    모든 관리자가 로깅 분석을 수행할 필요 없이 단일 보기에서 경보 및 지표의 히스토리를 볼 수 있습니다(#60과 유사함).

    관리자는 관리 팀의 설명 없이 디바이스의 일반 상태를 이해할 수 있습니다.

    모든 사용자가 명령행을 사용하지 않고 디바이스의 최근 syslog 파일을 열 수 있습니다(#35와 유사함).

    모든 사용자가 대화식 차트 세트에서 시계열 지표 데이터를 보고 탐색할 수 있습니다.

    모든 사용자가 경고 히스토리를 보고 기본적으로 이해할 수 있습니다.

    모든 사용자가 이벤트를 "열림" 또는 "닫힘"으로 표시할 수 있습니다.

    경보가 트리거될 때마다 사용자가 수동으로 이벤트를 작성할 필요가 없습니다.

    사용자가 경보 설정 이외에 심각도 레벨 "경고" 또는 "오류"를 수동으로 지정할 필요가 없습니다.

    모든 사용자는 collectD 에이전트를 사용하여 모니터링 프로세스, apache, tomcat, MSSQL, MySQL 및 URL 응답에 대한 시스템 및 애플리케이션 레벨 지표를 수집할 수 있습니다. 

    관리자는 자동화된 방식으로 사용자 정의 지표 데이터를 모니터링 서비스에 전송할 수 있습니다.

    모든 사용자는 그래프, 대시보드, 경보, 알림, 자동 응답, 템플리트 등과 같은 하이퍼바이저 지표와 동일한 방식으로 시스템, 애플리케이션 또는 사용자 정의 지표를 활용할 수 있습니다.



목표 2: 관리자는 90초 이내에 인시던트를 이해하고 문제점 해결을 시작할 수 있습니다.

사용자 스토리:

    모든 관리자는 거짓 긍정(false positive)이 범람하지 않은 상태로 경보를 구독할 수 있습니다.

    모든 관리자는 트리거링 이벤트 발생 후 1분 이내에 처음으로 선택한 통신 채널을 통해 경보를 수신할 수 있습니다.

    신뢰성 엔지니어는 경보 자체의 메시지를 기반으로 인시던트 경보의 원인을 이해할 수 있습니다.

    모든 관리자는 높은 정확도로 디바이스에 대한 최근 사용량 지표를 확인할 수 있습니다.

    모든 관리자는 10초 이내에 필요한 정확한 정보를 검색할 수 있습니다.

    비관리자는 SL 지원에서 세 개 미만의 메시지로 에스컬레이션된 인시던트를 해결할 수 있습니다.

    모든 사용자는 사용 가능한 지표(기본, collectD 또는 사용자 정의)에 대한 경보를 해제하기 위한 조건을 지정할 수 있습니다.

    모든 사용자는 지표의 평균값, 누적(합계) 값, 최소값 또는 최대값을 기반으로 조건을 지정할 수 있습니다.

    모든 사용자는 "초과" 또는 "미만" 한정자를 사용하여 조건을 지정할 수 있습니다.

    모든 사용자는 경보가 트리거되기 전에 조건이 충족되어야 하는 연속 기간 수와 기간의 길이(30초 또는 5분)를 지정할 수 있습니다(예: "X가 2회의 30초 연속 기간 동안 발생하면 경보가 트리거됨").

    모든 사용자는 단일 경보에 대한 여러 조건을 지정할 수 있습니다(예: 이것 그리고 이것 그리고 이것이면 경보가 트리거됨").

    모든 사용자는 경보에 대한 사용자 정의 이름을 지정할 수 있습니다.

    모든 사용자는 경보를 트리거한 시간, 경보 이름 및 충족된 조건을 표시하는 경보의 알림을 받을 수 있습니다.

    경보가 트리거된 후 초기 경보가 "닫힐" 때까지 사용자가 동일한 디바이스에 대한 동일한 규칙에서 추가 경보를 수신하지 않습니다.

    경보 규칙 예: CPU 사용률의 평균이 2회의 5분 연속 기간 동안 80%보다 크고 네트워크 인바운드의 합계가 1회의 5분 연속 기간 동안 50GB보다 크면 경보가 트리거되고 이벤트가 작성됨(이 규칙의 이전 경보가 닫혔다고 가정함)

    관리자는 사용자에게 알리기 위한 하나 이상의 이메일 주소를 지정할 수 있습니다.

    관리자는 사용자에게 알리기 위한 하나 이상의 SMS 전화번호를 지정할 수 있습니다.

    관리자는 웹훅이 전송할 하나 이상의 URL을 지정할 수 있습니다.

    관리자는 사용자에게 알리기 위한 Pagerduty 그룹을 지정할 수 있습니다.

    관리자는 경보가 트리거될 때 서버가 다시 부팅되거나 종료되어야 하는지를 지정할 수 있습니다.

    관리자는 지원되는 프로토콜의 네트워크 모니터링에 대한 간격(30초 또는 5분)을 지정할 수 있습니다.

    관리자는 호스트 ping(ICMP) 검사를 구현할 수 있습니다.

    관리자는 DNS, DNS 사용자 정의, FTP, HTTP, HTTP 사용자 정의, HTTPS, IMAP, LDAP, NNTP, POP, SMTP, SSH, TCP 사용자 정의, TELNET, UDP SIP(이러한 프로토콜에 대한 지원은 현재 SL TCP 오퍼링에 있음) 등의 다양한 프로토콜에 대한 TCP 포트 검사를 구현할 수 있습니다.

    관리자는 SNMP 프로토콜(현재 기존 SL 오퍼링에서 지원되지 않음)에 대한 TCP 포트 검사를 구현할 수 있습니다.

    관리자는 성공 또는 오류로 규정할 응답 시간에 대한 임계값을 지정할 수 있습니다.

    관리자는 경보가 트리거되기 전에 호스트 ping 또는 TCP 포트 검사의 연속 오류 수를 지정할 수 있습니다.

    관리자는 지표를 기반으로하는 경보에서와 같이 네트워크 모니터링 경보에서 동일한 알림 및 자동화된 응답 옵션을 구현할 수 있습니다(이메일, SMS, 웹훅, PagerDuty, 다시 부팅, 시스템 종료).

    관리자는 지표 및 네트워크 모니터링 경보 둘 다에 대한 심각도 레벨 "경고" 또는 "오류"를 지정할 수 있습니다.



목표 3: 모든 사용자가 구성 의사결정에 90초 미만을 들여서 디바이스에 대한 모니터링을 설정할 수 있습니다(#59와 유사함).

사용자 스토리:

    비관리자는 기본적으로 인터페이스와 문서만을 사용하여 모니터링을 구성할 수 있습니다.

    관리자는 수동 구성 프로세스를 거치지 않고 저장되거나 사전 패키지된 구성을 선택하여 특정 요구사항을 충족하는 모니터링을 설정할 수 있습니다(#58과 유사함).

    관리자는 수동으로 구성을 편집 및 저장하여 특정 요구사항을 충족하는 모니터링을 설정하고 임의의 수의 디바이스에 적용할 수 있습니다.

    관리자는 최소한의 반복 작업으로 여러 디바이스에 경보를 설정할 수 있습니다.

    모든 사용자가 시간별 및 지표별 데이터를 CSV 파일로 내보낼 수 있습니다.

    관리자는 유지보수 기간을 설정할 수 있으며, 이 시간 동안에는 경보가 트리거될 때 알림이 전송되지 않습니다.

    설정된 사용자가 저장된 구성을 이해하고 적용할 수 있습니다(#41과 유사함).

    새 사용자가 사전 패키지된 구성을 이해하고 적용할 수 있습니다(#34, #32와 유사함).

    비관리자가 지원 티켓을 제출하지 않고 모니터링 설정에 대한 지원을 받을 수 있습니다.

    모든 고객이 전문 지식 없이도 디바이스에 대한 모니터링을 주문할 수 있습니다(#63, #43과 유사함).

    모든 고객에게는 디바이스에 대한 모니터링을 주문하기 위한 예측 가능한 통합 환경이 있습니다(#40과 유사함).

    모든 사용자가 지원 티켓을 제출하지 않고 해당 디바이스를 써드파티 서비스와 통합할 수 있습니다.

    사용자가 라이프사이클 "경고" 경보(작성, 부팅, 시스템 종료)에 대한 경보를 수동으로 작성할 필요가 없습니다.

    모든 기술 사용자는 나머지 모니터링 서비스와 동일한 API를 통해 모든 관찰자 기능에 액세스할 수 있습니다.

    IBM에서는 무료 대 유료 계층에 대한 관찰자 개요에 정의된 대로 무료 버전에서 특정 기능/성능에 대한 계정 액세스를 제한할 수 있습니다. 

    모든 고객이 모니터링 탭 내부에서 무료 버전에서 유료 버전으로 업그레이드할 수 있습니다.

    모든 고객이 계정 관리 영역에서 유료 또는 무료 버전으로부터 업그레이드하거나 다운그레이드할 수 있습니다.

    무료 버전을 사용하는 모든 고객은 업그레이드한 경우에 사용할 수 있는 옵션을 볼 수 있지만 해당 옵션이 사용 불가능한 이유가 표시됩니다.

    사용자가 업그레이드 수행이 필요한 조치를 수행하려고 시도하는 경우 업그레이드해야 한다고 설명하며 존재하는 경우 대안을 제공하는 메시지가 표시됩니다(예: "이미 무료 버전에 대한 최대 수의 경보가 있습니다. 새 규칙을 작성하려면 경보를 업그레이드하거나 삭제하십시오.").


