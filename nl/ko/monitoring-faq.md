---
copyright:
  years: 1994, 2017
lastupdated: "2017-11-01"
---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

<a name="top"></a>
# 모니터링 FAQ

<a name="48"></a>
## 수많은 모니터링 경보 티켓이 표시됩니다. 이는 내 서버가 작동 중지되었음을 의미합니까?

각 디바이스는 무료 모니터링 ping 및 알림 서비스와 함께 제공됩니다. 이 서비스는 설정된 매개변수가 실패하면 자동으로 모니터링 경보 티켓을 작성합니다. 모니터링 서비스에 거짓 긍정(false positive)이 발생할 가능성이 있으며 서버의 소프트웨어 방화벽, 서비스 및 애플리케이션 가용성, 모니터링 인프라 내의 서비스 중단으로 인한 속도 제한이 원인이 될 수 있습니다. 기본 설정을 검토하여 가능한 거짓 모니터링 경보를 완화시키십시오. 

<a name="354"></a>
## 서버가 응답을 중지하는 경우 모니터링 시스템에서 자동 다시 부팅을 실행하도록 하고 지원 기술자에게 경보를 보낼 수 있습니까?

예, **모니터링 중 실패 발생 시 자동 다시 부팅** 서비스를 사용하면 모니터링 경보가 발행되는 경우 자동으로 서버를 다시 부팅하고 지원 기술자를 위한 티켓을 발행하도록 모니터링 시스템을 설정할 수 있습니다. 

<a name="1699"></a>
## "저속 ping"과 "서비스 ping"을 사용한 모니터링의 차이점은 무엇입니까?

서비스 ping과 저속 ping 간의 차이점은 디바이스의 응답이 예상되는 시간입니다. 기본값은 서비스 ping이지만 대신 저속 ping을 사용하도록 변경할 수 있습니다.

* **서비스** ping은 5분 간격으로 하나의 ping을 발행하며 1초 이내에 에코 응답을 예상합니다. 둘 이상의 ping이 응답을 받지 못하면 경보가 발행됩니다.
* **저속** ping은 5초 동안 응답을 대기하며 비네트워크 태스크에 최적화된 서버가 요청을 처리하는 데 더 많은 시간을 허용합니다.


<a name="1000"></a>
## 모니터링 티켓이 열리고 문제에 대한 경보를 전송하면 기술자가 티켓을 보고 응답합니까?

기본 ping 서비스를 사용하는 경우 지원 기술자에게 실패에 대해 알리지 않습니다. 이러한 티켓은 모니터링 시스템이 경보를 발행할 때 열리며 모니터링 화면에서 지정한 사용자에게만 알립니다. 서버가 응답하지 않음을 나타내는 새 티켓을 열 때까지 기술자에게 경보를 보내지 않습니다.

