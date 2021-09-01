---
title: 릴리스 노트
description: 릴리스 노트 및 [!DNL Assets Essentials]의 알려진 문제
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: 574ac781fc5c5dfdba0640b1032a50268947875d
workflow-type: tm+mt
source-wordcount: '301'
ht-degree: 1%

---


# [!DNL Assets Essentials] 릴리스 노트 {#release-notes}

[!DNL Assets Essentials] 의 현재 릴리스는 2021년 8월 30일에 릴리스됩니다. [!DNL Workfront] 사용자가 작업 관리 컨텍스트에서 디지털 자산을 관리할 수 있도록 해주는 [!DNL Adobe Workfront] 과의 통합을 제공합니다. 자세한 내용은 [다른 Adobe 솔루션과의 통합](/help/integration.md)을 참조하십시오.

솔루션에 대해 자세히 알아보려면 [소개 [!DNL Assets Essentials]](introduction.md)를 참조하십시오. 기능 사용을 시작하려면 [시작하기](/help/get-started.md)를 참조하십시오.

## 알려진 문제 {#known-issues}

알려진 [!DNL Assets Essentials] 제공 문제 목록이 계속 수정 및 업데이트됩니다.

* 폴더 또는 자산을 업로드하려면 항목을 리포지토리의 하위 폴더가 있는 폴더로 드래그하면 업로드가 자동으로 하위 폴더 중 하나로 이동합니다. 해결 방법은 [!DNL Upload assets] 옵션을 클릭하고 대화 상자로 드래그하는 것입니다. <!-- CQ-4327753 -->
* 폴더를 업로드하면 트리 보기에 표시되지 않고 왼쪽 레일에 새 폴더가 잘못 표시될 수 있습니다. 해결 방법은 브라우저를 새로 고치는 것입니다. <!-- CQ-4323534 -->

<!--
* Use assets that do not have whitespace in the file names. The replies to comments do not work for such assets.
-->

문제가 발생하거나 심지어 개선 요청이 발생하면 [팀에 피드백](#provide-feedback)을 제공합니다.

## 이전 릴리스 {#past-release}

### 2021.7.0 릴리스 {#july2021}

[!DNL Assets Essentials] 2021.7.0은 2021년 7월 29일에 출시되며 다음 업데이트가 있습니다.

* [!DNL Settings] 아래의 [!UICONTROL Metadata Forms] 옵션의 자산 세부 사항 화면에서 사용자에게 메타데이터 속성을 표시하는 데 사용할 사용자 지정된 메타데이터 양식을 만들고 관리할 수 있습니다. [메타데이터 양식](metadata.md#metadata-forms)을 참조하십시오.
* 많은 하위 폴더가 있는 중첩된 폴더를 업로드할 때 향상된 성능을 비롯한 다양한 버그 수정 및 제품 개선 사항이 있습니다.

### 2021.6.0 릴리스 {#june2021}

[!DNL Assets Essentials] 의 첫 번째 릴리스는 2021년 6월 21일에 사용할 수 있으며, 간단한 자산 관리 기능을 제공합니다. 다음과 같은 주요 기능과 CRUD(만들기, 읽기, 업데이트 및 삭제) 작업을 지원합니다.

* 중첩된 폴더를 포함한 자산을 업로드하고 추가합니다. 자산 및 버전을 미리 봅니다.
* 신속한 자산 검색을 위해 전체 텍스트 검색, 고급 검색 필터 및 저장된 검색을 수행할 수 있습니다.
* 업데이트, 삭제, 다운로드 및 메타데이터와 같은 기본 자산 관리 작업입니다.
* [!DNL Assets Essentials] 메시지를 만들  [!DNL Adobe Journey Optimizer] 때 자산을 관리할 사용자가 사용할 수 있습니다. 자세한 내용은 [다른 Adobe 솔루션과의 통합](/help/integration.md)을 참조하십시오.
