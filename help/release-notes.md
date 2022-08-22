---
title: 릴리스 정보
description: ' [!DNL Assets Essentials]의 릴리스 정보 및 알려진 문제'
role: User,Leader,Admin,Architect,Developer
contentOwner: AK
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: b44ded8b1678e9b7c1c5eda3f350072e51b52f32
workflow-type: tm+mt
source-wordcount: '1269'
ht-degree: 87%

---

# [!DNL Assets Essentials]의 릴리스 정보 {#release-notes}

현재 Assets Essentials 릴리스는 2022년 8월 16일에 릴리스됩니다.

이 릴리스는 다음을 제공합니다.

**컬렉션에 대한 알림**

이제 Assets Essentials 알림을 사용하여 저장소에서 사용할 수 있는 컬렉션에서 수행되는 작업을 모니터링할 수 있습니다. 알림이 전송될 컬렉션을 선택하고 구독해야 합니다. 컬렉션에 대해 수행되는 삭제, 공유 링크, 이동, 이름 변경 및 업데이트 작업과 같이 알림이 전송되는 작업을 구성할 수도 있습니다.

**스마트 컬렉션 편집**

또한 Assets Essentials은 스마트 컬렉션을 만드는 동안 사용되는 검색 기준을 편집하는 기능을 제공합니다.  새 검색 기준을 저장하여 컬렉션 콘텐츠를 동적으로 업데이트합니다.

<!--

**View live statistics for storage account**

Assets Essentials now also enables you to view real-time storage account data for your Assets Essentials environment with the Live Statistics dashboard. You can view real-time event metrics for the last 30 days or for the last 12 months.

-->

**업로드 보고서 보기**

이제 자산 보고는 관리자가 Adobe Experience Manager Assets Essentials 배포에 업로드된 자산에 대한 가시성을 제공합니다. 관리자는 이미 Assets Essentials 배포에서 다운로드한 자산에 대한 보고서를 생성할 수 있습니다. 이 데이터는 사용자가 콘텐츠 및 제품과 상호 작용하는 방법에 대한 유용한 정보를 제공합니다.

**고객 피드백을 기반으로 한 개선 사항**

고객 피드백에 따라 개선 사항이 적용되었으며 버그가 수정되었습니다.


## 알려진 문제 {#known-issues}

[!DNL Assets Essentials] 서비스의 알려진 문제 목록은 지속적으로 수정 및 업데이트됩니다.

<!--

* Assets Essentials does not support creating Private collections.

-->


* 개인 컬렉션은 생성자 및 관리자 권한이 있는 사용자가 사용할 수 있습니다. 관리자는 다른 사용자에게 컬렉션에 액세스할 수 있는 권한을 위임할 수 없습니다.

문제나 개선 요청이 있는 경우 팀에 [피드백을 제공](#provide-feedback)해 주십시오.

## 이전 릴리스 {#past-release}

### 2022.6.0 {#june-2022}

6월 릴리스 [!DNL Assets Essentials] 는 2022년 7월 14일에 릴리스됩니다.

이 릴리스는 다음을 제공합니다.

**Smart Collection**

검색 결과를 Smart Collection으로 저장하여 컬렉션 콘텐츠를 동적으로 업데이트합니다. [Smart Collection을 생성](manage-collections.md#create-smart-collection)하는 동안 정의된 검색 기준에 맞는 Assets Essentials 저장소에 추가된 에셋이 있는 경우 해당 Smart Collection의 콘텐츠가 자동으로 업데이트됩니다.

**알림**

Assets Essentials 알림을 사용하면 [저장소에서 사용할 수 있는 에셋 또는 폴더에서 수행된 작업을 모니터링](manage-notifications.md)할 수 있습니다. 알림을 받을 콘텐츠를 선택하고 구독해야 합니다. 알림을 받을 범주를 구성할 수도 있습니다.

**보고**

에셋 보고를 사용하여 관리자는 Adobe Experience Manager Assets Essentials 내의 사용자 활동을 평가할 수 있습니다. 보고서 및 라이브 통계 대시보드는 사용자가 배포에서 사용할 수 있는 에셋과 상호 작용하는 방법에 대한 유용한 정보를 제공합니다. [보고서의 정보를 사용](manage-reports.md)하여 기업 내 또는 고객에 의한 Assets의 채택률을 측정하기 위한 주요 성공 지표를 도출할 수 있습니다.

에셋 다운로드 보고서 및 라이브 통계 대시보드 모듈을 보고 다운로드 중인 에셋 및 다운로드 빈도를 확인할 수 있습니다.

### 2022.5.0 {#may-2022}

의 5월 릴리스 [!DNL Assets Essentials] 는 2022년 6월 16일에 릴리스됩니다.

이 릴리스는 다음을 제공합니다.

**에셋 상태 개선 사항**

* 이제 Assets Essentials를 사용하여 [에셋의 만료 날짜를 설정](manage-organize.md#set-asset-status)할 수 있습니다. 또한 `Expired` 에셋 상태 및 만료 날짜 범위를 기반으로 [에셋을 필터링](search.md#refine-search-results)할 수 있습니다.

* 이제 Trash에서 사용 가능한 모든 에셋에 대한 에셋 상태 표시기를 볼 수 있습니다. 결과적으로 에셋 상태에 따라 에셋의 복원 여부를 결정할 수 있습니다.

**검색 필터 개선 사항**

* Assets Essentials에서는 이제 `No Status` 에셋 상태를 사용하여 [에셋을 필터링](search.md#refine-search-results)할 수 있습니다.

<!--

* Assets Essentials now supports [using a wildcard operator (*) while using custom filters](search.md#custom-filters) to enable Assets Essentials to display assets in the results that partially match the search criteria.

-->

**컬렉션 개선 사항**

<!--

* Assets Essentials now enables you to [create Private collections](manage-collections.md#create-collection).

-->

* Assets Essentials는 이제 [컬렉션 다운로드](manage-collections.md)를 지원합니다.

* 이제 컬렉션에 대한 설명 메타데이터 필드를 편집할 수 있습니다.

**설명서 개선 사항**

* 이제 [Assets Essentials 개요 설명서](introduction.md)의 새 버전을 사용할 수 있습니다.

**고객 피드백을 기반으로 한 개선 사항**

* 고객 피드백에 따라 개선 사항이 적용되었으며 버그가 수정되었습니다.

### 2022.4.0 {#april-2022}

[!DNL Assets Essentials]의 최신 릴리스는 2022년 5월 12일에 출시되었습니다. 이 릴리스는 다음을 제공합니다.

* [!DNL Assets Essentials]는 이제 [컬렉션 생성](manage-collections.md)을 지원합니다. 컬렉션은 Experience Manager Assets Essentials 내의 에셋 세트입니다. 컬렉션을 사용하여 사용자 간에 에셋을 공유합니다. 폴더와 달리 컬렉션에는 서로 다른 위치의 에셋이 포함될 수 있습니다.

* 이제 Assets Essentials를 사용하여 사용자 인터페이스에 [맞춤형 필터를 추가](search.md#custom-filters)할 수도 있습니다. 그런 다음 표준 필터 외에 이러한 맞춤형 필터를 적용하여 검색 결과를 구체화할 수 있습니다.

* 이제 Assets Essentials를 사용하여 저장소에서 사용 가능한 에셋의 [상태를 설정](manage-organize.md#set-asset-status)할 수 있습니다. 에셋 상태를 설정하여 디지털 에셋의 다운스트림 소비를 보다 효과적으로 관리합니다.

* 고객 피드백에 따라 개선 사항이 적용되었으며 버그가 수정되었습니다.

#### Chrome의 시크릿 모드 {#incognito-mode}

이 릴리스에서는 브라우저의 로컬 저장소 및 사용 가능한 서드파티 쿠키에 따라 Assets Essentials의 UI 전달 성능 및 특정 기능(에셋 댓글 달기 및 이미지 편집)을 최적화하고 있습니다. Chrome 웹 브라우저의 시크릿 모드는 기본적으로 서드파티 쿠키를 차단합니다. 사용자는 모든 기능에 계속 액세스할 수 있는 여러 가지 옵션을 사용할 수 있습니다.

* 사용자가 브라우저 세션을 분리해야 하는 경우 시크릿 모드 대신 Chrome 프로필 사용

* Chrome의 시크릿 모드 화면에서 `Block third-party cookies` 끄기

### 2022.2.0 {#march-2022}

[!DNL Assets Essentials]는 다음 업데이트와 함께 2022년 3월 9일에 출시됩니다.

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
