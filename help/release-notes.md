---
title: 릴리스 정보
description: ' [!DNL Assets Essentials]의 릴리스 정보 및 알려진 문제'
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 4cced7aba92fd0f041842e5ef78d02f0a4f7ffe0
workflow-type: tm+mt
source-wordcount: '549'
ht-degree: 59%

---

# [!DNL Assets Essentials]의 릴리스 정보 {#release-notes}

의 현재 릴리스 [!DNL Assets Essentials] 는 2022년 3월 9일에 릴리스됩니다. 이 릴리스는 다음을 제공합니다.

* [!DNL Assets Essentials] 이제 를 사용하여 다음을 수행할 수 있습니다. [링크 생성 및 외부 이해 관계자와 자산 공유](share-links-for-assets.md)에 대한 액세스 권한이 없는 [!DNL Assets Essentials] 응용 프로그램. 링크에 대한 만료 날짜를 정의한 다음, 전자 메일 또는 메시징 서비스와 같은 기본 통신 방법을 사용하여 다른 사용자와 링크를 공유할 수 있습니다. 링크를 받은 사람은 자산을 미리 보고 다운로드할 수 있습니다.

* 다음 [!DNL Assets Essentials] now includs [관리자 제품 프로필](deploy-administer.md#add-users-to-essentials) 기존 일반 및 소비자 사용자 제품 프로필 외에 추가 Admin Console. 이제 관리자는 관리자 제품 프로필에 다른 사용자를 할당할 수 있습니다.

* 이제 관리자가 Assets Essentials을 사용하여 [저장소에서 사용할 수 있는 폴더에 대한 액세스 수준 관리](manage-permissions.md). 관리자는 사용자 그룹을 만들고 액세스 수준을 관리하기 위해 해당 그룹에 권한을 할당할 수 있습니다. 폴더 수준의 사용자 그룹에 권한 관리 권한을 위임할 수도 있습니다.

* 고객 피드백을 기반으로 개선 사항 및 버그 수정.

게다가, [!DNL Adobe Asset Link] Creative Cloud 확장(Photoshop, Illustrator 및 InDesign)은 [새 버전 3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)로 설정되며, 패널 시작 시간 및 다운로드 속도가 개선되었습니다.


## 알려진 문제 {#known-issues}

[!DNL Assets Essentials] 서비스의 알려진 문제 목록은 지속적으로 수정 및 업데이트됩니다.

* 없음

문제나 개선 요청이 있는 경우 팀에 [피드백을 제공](#provide-feedback)해 주십시오.

## 이전 릴리스 {#past-release}

### 2022.1.0 릴리스 {#january-2022}

[!DNL Assets Essentials] 는 2022년 2월 3일에 출시되며 다음 업데이트가 있습니다.

* 을 위한 성능 개선 [!UICONTROL 폴더 만들기] 작업. <!-- CQ-4338818 -->

### 2021.11.0 릴리스 {#november-2021}

[!DNL Assets Essentials]는 다음 업데이트와 함께 2021년 12월 16일에 출시됩니다.

* Adobe는 프로비저닝 프로세스를 완료한 후 Assets Essentials를 자동으로 배포합니다. 관리자는 [!DNL Cloud Manager] 사용자 인터페이스를 사용하여 Assets Essentials를 배포하기 위해 추가 단계를 수행할 필요가 없습니다. 이 자동 배포는 2022년 1월 6일 이후에 프로비저닝된 환경에서 사용할 수 있습니다.
* Assets Essentials와 함께 작동하는 Creative Cloud 플러그인의 새 버전은 Adobe Exchange(Adobe XD용 [Adobe Asset Link v 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) 및 [Adobe Asset Link for Photoshop/InDesign/Illustrator v 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html))에서 사용할 수 있습니다.
* 이전에 알려진 문제를 포함한 다양한 버그 수정 및 제품 개선 사항(업로드<!-- CQ-4337638 --> 후 폴더가 이제 왼쪽 탐색 트리에 올바르게 표시되며, 드래그 앤 드롭 업로드를 통해 사용자가 업로드<!-- CQ-4327753 -->를 위해 드롭할 때 현재 폴더 또는 하위 폴더를 선택할 수 있음)

### 2021.8.0 릴리스 {#august2021}

[!DNL Assets Essentials] 2021.8.0은 다음 업데이트와 함께 2021년 8월 30일에 출시됩니다.

* [!DNL Adobe Workfront]와의 통합을 통해 [!DNL Workfront] 사용자가 작업 관리의 맥락에서 디지털 에셋을 관리할 수 있습니다. 자세한 내용은 [다른 Adobe 솔루션과 통합](/help/integration.md)을 참조하십시오.

### 2021.7.0 릴리스 {#july2021}

[!DNL Assets Essentials] 2021.7.0은 다음 업데이트와 함께 2021년 7월 29일에 출시됩니다.

* 의 자산 세부 사항 화면에서 사용자에게 메타데이터 속성을 표시하는 데 사용할 사용자 지정된 메타데이터 양식을 만들고 관리할 수 있습니다 [!UICONTROL 메타데이터 Forms] 옵션 아래의 [!DNL Settings]. [메타데이터 양식](metadata.md#metadata-forms)을 참조하십시오.
* 여러 하위 폴더가 있는 중첩 폴더를 업로드할 때의 성능 향상되는 등 다양한 버그 수정 및 제품 개선 사항이 있습니다.

### 2021.6.0 릴리스 {#june2021}

2021년 6월 21일에 릴리스된 [!DNL Assets Essentials]의 첫 번째 릴리스는 가벼운 에셋 관리 기능을 제공합니다. 다음과 같은 주요 기능과 CRUD(만들기, 읽기, 업데이트 및 삭제) 작업을 지원합니다.

* 중첩된 폴더를 포함하여 에셋을 업로드하고 추가합니다. 에셋 및 버전을 미리 봅니다.
* 전체 텍스트 검색, 정밀한 검색 필터 및 저장된 검색을 통해 빠른 에셋 검색을 수행할 수 있습니다.
* 메타데이터 업데이트, 삭제, 다운로드 및 관리와 같은 기본 에셋 관리 작업을 지원합니다.
* [!DNL Assets Essentials]는 [!DNL Adobe Journey Optimizer] 사용자가 메시지를 작성할 때 에셋을 관리하는 데 사용할 수 있습니다. 자세한 내용은 [다른 Adobe 솔루션과 통합](/help/integration.md)을 참조하십시오.
