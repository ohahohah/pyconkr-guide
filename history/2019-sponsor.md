## 목적

본 문서는 2019년에 두레이를 통해 스폰서를 관리하였던 방법에 대한 기록입니다. 여기 있는 내용대로 꼭 해야 하는 것은 아닙니다. 더 좋은 방법이 있으면 공유하고 수정해주세요.

스폰서 관리자를 위한 가이드이지만 메일링 관리자도 참고하시면 좋습니다.

* 본 문서에서는 **후원사**를 모두 **스폰서**라 표기하였습니다.

## 스폰서 신청 절차

1. 파이콘 한국 홈페이지를 통해 스폰서 신청 (아래 장고 어드민 페이지는 2019년 기준입니다.)
2. 신청 내용 확인 및 검토
   - 신청이 접수되었음을 알림 ([신청 확인 메일](<https://docs.google.com/document/d/1GmEgnfPCAyjm1lAIRh_JjYiOE2IhiTjFj-0Zb6uv1NY/edit#>))
   - 필수적으로 입력해야 하는 정보를 입력하였는지 확인
   - 스폰서 담당자를 포함한 준비위 내에서 이의가 없는지 확인
3. 이상 없다면 입금 안내 ([입금 요청 메일](<https://docs.google.com/document/d/1ZgnaEhKJYsz9RqYTRWLMoWTXnJRps4JCssq4caBBlfo/edit#>))
   - 추가 정보 중 어떤 것이 누락되었는지 안내
   - 입금 계좌 안내
4. 계좌 조회를 통해 입금 확인
   - [계좌 조회 방법](<https://docs.google.com/document/d/13GRI2bHSz2AqLCYK9S2-Uuhp7r_3chuqGxb0-DPm9zU/edit>)
5. 입금 확인되었다면 스폰서 확정 메일 발송 ([확정 안내 메일](<https://docs.google.com/document/d/1CiJFbXmsHA0ygKJLdMFlFLFWjZzFEWb3vZ9O8nKO4TQ/edit#>))

### 스폰서 신청 확인

![](./images/홈페이지 sponsors.png)

`Sponsors`를 누르면 홈페이지를 통해 신청한 스폰서 목록이 나옵니다. ID를 누르면 상세 정보가 표시됩니다. 

![](./images/홈페이지 submitted.png)

`SUBMITTED`가 체크되어 있다면 후원사가 신청을 제출한 것입니다.

### 입금 안내

신청 내용에 이상이 없다면 메일 초안에 쓰인 대로 입금 계좌를 안내합니다. 약관상 명시된 입금 기한을 한 번 더 고지해주는 것도 좋습니다.

![](./images/홈페이지 accepted.png)

이후 홈페이지 관리 페이지에서 해당 기업의 `ACCEPTED`를 체크해줍니다.

### 입금 확인

빠른 계좌 조회를 통해 해당 기업의 입금이 확인합니다. 이 때, 해당 등급에 맞는 후원금을 입금하였는지 꼭 확인해야 하고, 부가세 10%가 포함되었는지도 확인합니다.

![](./images/홈페이지 paid at.png)

확인이 완료되면 확정 안내 메일을 보내고, 홈페이지 관리 페이지에서 `PAID AT`에 입금 날짜, 일시를 적어줍니다.

## 두레이에서의 메일링 관리

대부분의 경우 스폰서와의 소통은 메일(sponsor@pycon.kr)을 통해 이뤄집니다. 두레이에서는 `메일링-sponsor` 프로젝트에 자동으로 이 메일링이 연결되어 있습니다.

![](./images/두레이 댓글로 메일 보내기.png)

메일링이 연결된 두레이 프로젝트에서는 댓글을 통해 바로 메일을 회신할 수 있습니다. 스폰서에서 문의 메일이 왔을 경우 이를 통해 회신하는 것이 가장 간편합니다.

### 태깅

![](./images/두레이 태그.png)

수많은 스폰서들과 한 메일링을 통해 소통하며 모두를 구별하기는 쉽지 않습니다. 두레이에 있는 프로젝트별 태그 기능을 통해 필터링해보면 편합니다.

#### 세금계산서

기본적으로 후원금 입금을 위해서는 스폰서에서 전자 세금계산서 발행을 원하시는 경우가 많습니다. 세금계산서 발행은 `스폰서` 프로젝트에서 업무를 생성하고 진행하시면 됩니다. 세금계산서 발행이 완료되면 메일로 알려드려야 하기에 메일링 프로젝트에서도 이 태그가 쓰입니다.

세금계산서 발행을 원하실 경우 업무 상태를 `진행 중`으로 바꾸고 `세금계산서` 태그를 달아둡니다. 세금계산서 발행이 되면, 댓글을 통해 완료되었다고 알려드리고 업무 상태를 `완료`로 바꿉니다.

#### 공문

세금계산서보다는 드물지만 사단법인 "파이썬 사용자모임" 이름으로 된 공문이 필요하다 하시는 경우가 있습니다. `세금계산서`와 마찬가지로 `공문` 태그를 달아주고 업무 상태를 `진행 중`으로 바꿉니다. 스폰서 프로젝트에서 업무를 만들어 공문 발행을 진행합니다. 보통의 경우 PDF 형식으로 출력해 메일로 회신드려도 되지만, 날인이 찍혀야 하거나 서면으로 보내달라고 하시는 경우엔 가능하신 분을 담당자로 지정하시고 알려주세요.

PDF 파일을 회신드렸거나 담당자분이 발송을 완료하셨으면 업무 상태를 `완료`로 바꿉니다.

#### 스폰서별 태그

각 스폰서별로 어떤 메일을 주고 받았는지 필터링하기가 쉽지 않습니다. 그래서 각 후원사마다 `스폰서 - xxx`라는 태그를 만들고 이 태그를 주고 받은 메일에 모두 달아줍니다. 업무 필터링 조건에 해당 태그를 지정하면 이 스폰서와 주고 받은 메일을 한 눈에 볼 수 있습니다.

### 먼저 메일 보내기

스폰서에게 먼저 메일을 보내고자 할 때는 `메일링-sponsor` 프로젝트에서 `새 업무`를 누릅니다. 제목과 본문 내용을 입력하고 아래와 같이 채워줍니다.

- 담당자 : 받는 사람 (`To`)
- 참조 : 참조 (`sponsor@pycon.kr`, `메일링-sponsor/all`)

그리고 `저장`을 누르면 `From`을 누구로 보낼지 물어보는데, 개인 두레이 계정이 아닌 팀 계정(`PyCon Korea Sponsor`)으로 선택해주시면 됩니다.

회신을 기다리지 않는 메일인 경우 생성된 업무를 `완료`, 그렇지 않은 경우 `진행 중`으로 표시하고 그에 맞는 태그를 걸어줍니다.

회신이 오는 경우 보통 댓글로 들어오고 쓰레드로 묶입니다. 또한 새로운 업무로도 등록됩니다. 이 업무는 삭제하셔도 되고 거기서 새로운 쓰레드로 활용하셔도 됩니다. 메일의 오고 감이 많아 쓰레드가 너무 길거나 내용이 다른 메일의 경우 새로운 쓰레드로 활용하시는 걸 추천 드립니다.

기존의 방법대로 지메일에서 메일을 보낼 수도 있습니다. ([지메일에서 메일 보내기](./03-mailing-rule.md))

### 메일이 왔을 때

외부에서 문의 메일이 온 경우 바로 두레이 업무로 등록됩니다. 기존에 스폰서 태그가 존재하는 경우 바로 태깅하고 회신하시면 됩니다. 그렇지 않은 경우 그냥 놔두셔도 됩니다. 추후에 스폰서로 신청하시면 그 때 태그를 만들고 걸어도 됩니다.

보낼 때와는 다르게 간단하게 댓글로 바로 회신하시면 됩니다. 메일 초안을 썼는데 다른 분들의 검토가 필요한 경우 업무 상태를 `검토 필요`로 바꾸고 슬랙에 공유해주세요.

### 메일링 업무 상태

메일링의 경우 준비위원회 전체가 한 그룹으로 묶여있습니다. (e.g., `메일링-sponsor/all`) 이런 경우 내 담당 업무에서 해당 업무를 `완료`로 바꾸면 그 업무는 `완료`로 바뀌지 않는 것을 볼 수 있습니다. 왜냐면 그룹 내 구성원 중 나 혼자만 완료를 눌렀기 때문에 아직 그 업무가 `완료`로 바뀌지 않은 것입니다.

메일링의 담당자를 바꾸셔도 상관없지만, 업무 목록 보기에서 보낸 사람을 빠르게 보려면 담당자를 변경하지 않는 것이 편하기 때문에 되도록이면 그대로 두고 있습니다. 이 경우 해당 업무를 완료할 때 일괄적으로 한 번에 모든 구성원을 `완료`로 바꾸는 방법을 사용하고 있습니다.

![](./images/두레이 업무 상태 일괄 변경.png)

다른 사람의 업무 상태를 편집할 수 있는 이유는 해당 프로젝트에 대해 모두가 관리자 권한을 갖고 있기 때문입니다.

## 스폰서 관리

### 스폰서 관리 카드

앞서 봤던 스폰서 신청 과정들이 메일을 통해 이뤄집니다. 하지만 각 스폰서마다 얼마나 일이 진행되고 있는지를 보려면 메일을 하나하나 뒤져봐야 하죠. ~~귀찮습니다~~ 그래서 스폰서마다 **스폰서 관리 카드**를 만들어 활용하고 있습니다.

![](./images/두레이 스폰서 관리 카드.png)

스폰서 카드 전용 업무 상태가 5가지 있습니다.

- 신청
- 검토 필요
- 입금 요청
- 입금 완료 : 세금계산서 미발행 / 미완료 + 입금 완료
- 세금계산서 완료 : 세금계산서 완료 + 입금 완료

각각의 상태에 따라 카드를 옮기시면 됩니다.

![](./images/두레이 업무 보드.png)

`보드`를 클릭하시면 위와 같이 화면이 바뀝니다. 여기서 스폰서 관리 카드를 드래그 앤 드랍하면 쉽게 옮길 수 있습니다.

### 기타 업무

세금계산서 발행을 포함한 스폰서 업무에 포함되는 부가 업무들이 있습니다. (e.g., 공문 발행) 이런 일감들도 업무로 생성하시고 관련된 스폰서에 **상위/하위 업무**로 연결해주세요. 위 스폰서 관리 카드 사진에 나와 있듯이, 스폰서 관리 카드에서 간단하게 연결된 일감들을 확인하고 완료되었는지 볼 수 있습니다.
