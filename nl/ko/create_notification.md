---
copyright:
  years: 2018
lastupdated: "2018-05-18"
---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# 모니터 알림 작성 및 관리(베타)
알림은 경보가 트리거될 때 알리는 데 사용되는 방법 및 세부사항에 대해 설명합니다. 예를 들어, 지표에 대한 경고 알림 및 오류 알림을 받으려면 경고 임계값을 모니터하는 규칙을 정의하고 오류 임계값을 모니터하는 규칙을 정의하십시오.
{:shortdesc} 

## 알림 작성
 
 1. 베타에 참여한 후 **디바이스 -> 모니터링**을 선택하십시오. 
 2. **알림** 탭을 클릭하십시오.
 3. **알림 작성**을 클릭하십시오.
 4. 새 알림에 대한 정보를 입력하십시오. 

<table>
  <caption>이메일 알림 세부사항</caption>
  <tr>
     <th>필드</th>
     <th>설명</th>
  </tr>
  <tr>
    <td>이름</td>
    <td>알림의 고유 ID입니다. 이 필드는 필수입니다.</td>
  </tr>
  <tr>
    <td>유형</td>
    <td>선택: **이메일**</td>
  </tr>
  <tr>
    <td>이메일 주소</td>
    <td>수신인의 이메일 주소를 입력하십시오.</td>
  </tr>
</table>

<table>
  <caption>웹훅 알림 세부사항</caption>
  <tr>
     <th>필드</th>
     <th>설명</th>
  </tr>
  <tr>
    <td>이름</td>
    <td>알림의 고유 ID입니다. 이 필드는 필수입니다.</td>
  </tr>
  <tr>
    <td>유형</td>
    <td>선택: **웹훅**</td>
  </tr>
  <tr>
    <td>웹훅 URL</td>
    <td>POST가 수행되어야 하는 URL을 입력하십시오.</td>
  </tr>
  <tr>
  <td>인증서 확인</td>
    <td>인증서를 확인하려면 선택하십시오.</td>
  </tr>
  <tr>
    <td>웹훅 헤더</td>
    <td>헤더를 입력하십시오.</td>
  </tr>
  <tr>
    <td>웹훅 조회 매개변수</td>
    <td>조회 매개변수를 입력하십시오.</td>
  </tr>
</table>

<table>
  <caption>PagerDuty 알림 세부사항</caption>
  <tr>
     <th>필드</th>
     <th>설명</th>
  </tr>
  <tr>
    <td>이름</td>
    <td>알림의 고유 ID입니다. 이 필드는 필수입니다.</td>
  </tr>
  <tr>
    <td>유형</td>
    <td>선택: **PagerDuty**</td>
  </tr>
  <tr>
    <td>API 키</td>
    <td>PagerDuty 알림에 대한 API 키를 입력하십시오.</td>
  </tr>
</table>


5. **확인**을 클릭하여 지정한 설정으로 새 알림을 작성하십시오.

## 알림 편집
 1. 베타에 참여한 후 **디바이스 -> 모니터링**을 선택하십시오. 
 2. **알림** 탭을 클릭하십시오.
3. **조치->알림 편집**을 클릭하십시오.
4. 알림 세부사항을 편집하십시오.
5. **확인**을 클릭하여 변경사항을 승인하십시오.

## 알림 삭제
1. 베타에 참여한 후 **디바이스 -> 모니터링**을 선택하십시오. 
2. **알림** 탭을 클릭하십시오.
3. **조치->알림 삭제**를 클릭하십시오.
4. **삭제**를 클릭하여 선택사항을 확인하십시오.

## 디바이스에 복수 알림 추가
1. **인프라->디바이스 목록->*디바이스 이름***을 선택하여 디바이스 세부사항에 액세스하십시오.
2. **조치->알림 관리**를 클릭하십시오.
4. 클릭하여 디바이스에 대한 알림을 지정하거나 제거하십시오.

