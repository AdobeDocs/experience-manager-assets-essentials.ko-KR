---
title: 릴리스 정보
description: ' [!DNL Assets Essentials]의 릴리스 정보 및 알려진 문제'
role: User,Leader,Admin,Architect,Developer
contentOwner: AK
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 7c4bc88e2110ff1dd7442af303bdd2c586ba5a6f
workflow-type: tm+mt
source-wordcount: '786'
ht-degree: 69%

---

# [!DNL Assets Essentials]의 릴리스 정보 {#release-notes}

의 현재 릴리스 [!DNL Assets Essentials] 는 2022년 5월 12일에 릴리스됩니다. 이 릴리스는 다음을 제공합니다.

* [!DNL Assets Essentials] 이제에서 지원 [컬렉션 만들기](manage-collections.md). 컬렉션은 Experience Manager Assets Essentials에 포함된 자산 세트입니다. 컬렉션을 사용하여 사용자 간에 자산을 공유합니다. 폴더와 달리 컬렉션에는 다른 위치의 자산이 포함될 수 있습니다.

* 이제 Assets Essentials을 사용하여 다음을 수행할 수도 있습니다 [사용자 지정 필터 추가](search.md#custom-filters) 를 사용자 인터페이스에 추가합니다. 그런 다음 표준 필터 외에 이러한 사용자 지정 필터를 적용하여 검색 결과를 세분화할 수 있습니다.

* 이제 Assets Essentials에서 다음을 수행할 수 있습니다 [상태 설정](manage-organize.md#set-asset-status) 저장소에서 사용할 수 있는 자산입니다. 디지털 자산의 다운스트림 소비를 더 잘 제어하고 관리하려면 자산 상태를 설정하십시오.

* 고객 피드백에 따라 개선 사항이 적용되었으며 버그가 수정되었습니다.

## Chrome의 시크릿 모드 {#incognito-mode}

이번 릴리스를 통해 Adobe는 UI 게재의 성능 및 Assets Essentials의 특정 기능(자산 및 이미지 편집에 주석을 달 수 있는 기능은 브라우저 로컬 저장소 및 사용 중인 타사 쿠키에 따라 다름)을 최적화하고 있습니다. Chrome 웹 브라우저의 시크릿 모드에서는 기본적으로 타사 쿠키를 차단합니다. 사용자에게는 모든 기능에 계속 액세스할 수 있는 다양한 옵션이 있습니다.

* 사용자가 브라우저 세션을 구분해야 하는 경우 Incognito 모드 대신 Chrome 프로필을 사용하십시오

* 설정 해제 `Block third-party cookies` chrome의 Incognito 모드 화면

## 알려진 문제 {#known-issues}

[!DNL Assets Essentials] 서비스의 알려진 문제 목록은 지속적으로 수정 및 업데이트됩니다.

* 를 사용하여 자산을 필터링할 수 없습니다 `No Status` 자산 상태.

* 가 있는 자산을 찾아보거나 검색할 수 없습니다 `Expired` 상태. 딥 링크 또는 URL을 사용해야만 자산에 액세스할 수 있습니다.

* Assets Essentials은 비공개 컬렉션 만들기를 지원하지 않습니다.

문제나 개선 요청이 있는 경우 팀에 [피드백을 제공](#provide-feedback)해 주십시오.

## 이전 릴리스 {#past-release}

### 2022.2.0 {#march-2022}

[!DNL Assets Essentials] 는 2022년 3월 9일에 출시되며 다음 업데이트가 있습니다.

* 이제 [!DNL Assets Essentials]에서는 [링크를 생성하고 [!DNL Assets Essentials] 애플리케이션에 대한 액세스 권한이 없는 외부 관련자와 에셋을 공유](share-links-for-assets.md)할 수 있습니다. 해당 링크에 대한 만료일을 정의한 다음 이메일 또는 메시징 서비스와 같이 선호하는 커뮤니케이션 수단을 사용하여 다른 사용자와 공유할 수 있습니다. 링크 수신자는 에셋을 미리 보고 다운로드할 수 있습니다.

* 이제 [!DNL Assets Essentials]는 기존 기본 및 소비자 사용자 제품 프로필과 더불어 Admin Console의 [관리자 제품 프로필](deploy-administer.md#add-users-to-essentials)로 구성됩니다. 이제 관리자는 관리자 제품 프로필에 다른 사용자를 할당할 수 있습니다.

* 이제 Assets Essentials에서 관리자는 [저장소에서 사용할 수 있는 폴더에 대한 액세스 수준을 관리](manage-permissions.md)할 수 있습니다. 관리자는 사용자 그룹을 만든 다음 해당 그룹에 액세스 수준을 관리하도록 권한을 할당할 수 있습니다. 또한 폴더 수준에서 사용자 그룹에 권한 관리 권한을 위임할 수도 있습니다.

* 고객 피드백에 따라 개선 사항이 적용되었으며 버그가 수정되었습니다.

또한 패널 시작 시간 및 다운로드 속도에 대한 성능이 개선된 Creative Cloud용 [!DNL Adobe Asset Link] 확장 프로그램(Photoshop, Illustrator 및 InDesign)의 [신규 버전 3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)가 릴리스되었습니다.


### 2022.1.0 릴리스 {#january-2022}

[!DNL Assets Essentials]는 다음 업데이트와 함께 2022년 2월 3일에 릴리스됩니다.

* [!UICONTROL 폴더 생성] 작업의 성능이 향상되었습니다. <!-- CQ-4338818 -->

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

* [!DNL Settings] 아래 [!UICONTROL 메타데이터 양식] 옵션의 에셋 세부 정보 화면에서 사용자에게 메타데이터 속성을 표시하는 데 사용할 사용자 지정 메타데이터 양식을 만들고 관리할 수 있습니다. [메타데이터 양식](metadata.md#metadata-forms)을 참조하십시오.
* 여러 하위 폴더가 있는 중첩 폴더를 업로드할 때의 성능 향상되는 등 다양한 버그 수정 및 제품 개선 사항이 있습니다.

### 2021.6.0 릴리스 {#june2021}

2021년 6월 21일에 릴리스된 [!DNL Assets Essentials]의 첫 번째 릴리스는 가벼운 에셋 관리 기능을 제공합니다. 다음과 같은 주요 기능과 CRUD(만들기, 읽기, 업데이트 및 삭제) 작업을 지원합니다.

* 중첩된 폴더를 포함하여 에셋을 업로드하고 추가합니다. 에셋 및 버전을 미리 봅니다.
* 전체 텍스트 검색, 정밀한 검색 필터 및 저장된 검색을 통해 빠른 에셋 검색을 수행할 수 있습니다.
* 메타데이터 업데이트, 삭제, 다운로드 및 관리와 같은 기본 에셋 관리 작업을 지원합니다.
* [!DNL Assets Essentials]는 [!DNL Adobe Journey Optimizer] 사용자가 메시지를 작성할 때 에셋을 관리하는 데 사용할 수 있습니다. 자세한 내용은 [다른 Adobe 솔루션과 통합](/help/integration.md)을 참조하십시오.
