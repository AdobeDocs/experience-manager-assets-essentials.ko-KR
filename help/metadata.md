---
title: 메타데이터 관리
description: ' [!DNL Assets Essentials]에 있는 자산의 메타데이터 관리'
role: User,Leader,Administrator,Architect,Developer
contentOwner: AG
source-git-commit: 5bae37e18ac587aaacaa004e5ec02775888d7f9a
workflow-type: tm+mt
source-wordcount: '544'
ht-degree: 0%

---


# [!DNL Assets Essentials]의 메타데이터 {#metadata}

메타데이터는 데이터에 대한 데이터 또는 설명을 의미합니다. 예를 들어, 자산으로 이미지에는 클릭한 카메라 정보 또는 저작권 정보가 포함될 수 있습니다. 이 정보는 이미지의 메타데이터입니다. 메타데이터는 효율적인 자산 관리를 위해 매우 중요합니다. 메타데이터는 자산에 사용할 수 있는 모든 데이터의 수집이지만 해당 자산에 포함되어 있을 필요는 없습니다.

메타데이터는 자산을 더 분류하는 데 도움이 되며, 디지털 정보의 양이 늘어나면 유용합니다. 파일 이름, 축소판 및 메모리만 기준으로 수백 개의 파일을 관리할 수 있습니다. 그러나 이 방법은 확장 가능하지 않습니다. 관련된 사람의 수와 관리되는 자산의 수가 증가하면 부족합니다.

메타데이터가 추가되면 자산이 만들어지므로 디지털 자산의 값이 증가합니다.

* 보다 손쉽게 액세스 가능 - 시스템과 사용자가 쉽게 찾을 수 있습니다.
* 관리가 쉬워짐 - 동일한 속성 세트를 더 쉽게 사용하여 자산을 찾고 변경 사항을 적용할 수 있습니다.
* 완료 - 자산은 더 많은 정보와 더 많은 메타데이터를 사용하여 컨텍스트를 전달합니다.

이러한 이유로 Assets는 디지털 자산에 대한 메타데이터를 만들고, 관리하고 교환하는 올바른 방법을 제공합니다.

## 메타데이터 보기 {#view-metadata}

자산의 메타데이터를 보려면, 자산으로 이동하거나 자산을 검색하고, 자산을 선택한 다음 도구 모음에서 **[!UICONTROL Details]** 를 클릭합니다.

![자산의 메타데이터 보기](assets/metadata-view1.png)

*그림:자산 및 해당 메타데이터를 보려면 도구 모음&#x200B;**[!UICONTROL Details]**에서 를 클릭하거나 자산을 두 번 클릭합니다.*

제목, 설명 및 업로드 날짜와 같은 기본 메타데이터는 [!UICONTROL Basic] 탭에서 사용할 수 있습니다. [!UICONTROL Advanced] 탭에는 카메라 모델, 렌즈 세부 사항 및 지오태그와 같은 고급 메타데이터가 더 포함되어 있습니다. [!UICONTROL Tags] 탭에는 이미지의 내용을 기반으로 자동으로 적용된 태그가 포함되어 있습니다.

## 메타데이터 업데이트 {#update-metadata}

몇 개의 메타데이터 필드를 수동으로 업데이트할 수 있습니다. 이 필드에는 [!UICONTROL Title], [!UICONTROL Description], [!UICONTROL Author] 및 [!UICONTROL Keywords]가 포함됩니다.

## 태그 {#tags}

[!DNL Assets Essentials] 에서는  [Adobe 센서에서 제공한 인공 ](https://www.adobe.com/kr/sensei.html) 인텔리전스를 사용하여 업로드된 모든 자산에 관련 태그를 자동으로 적용합니다. 적절한 이름의 이러한 태그는 관련 자산을 신속하게 찾을 수 있도록 하여 프로젝트의 컨텐츠 속도를 높입니다. 스마트 태그는 이미지에 포함되지 않은 메타데이터의 예입니다.

스마트 태그는 거의 실시간으로 적용되며 이미지의 내용을 기반으로 생성됩니다. 자산을 업로드하면 사용자 인터페이스에 한동안 자산 축소판에 [!UICONTROL Processing]이 표시됩니다. 처리가 완료되면 [메타데이터](#view-metadata) 및 스마트 태그를 볼 수 있습니다.

![자산의 스마트 태그 보기](assets/metadata-view-tags.png)

*그림:자산의 스마트 태그를 보려면 도구 모음&#x200B;**[!UICONTROL Details]**에서 를 클릭하거나 자산을 두 번 클릭합니다.*

스마트 태그에는 신뢰도 점수가 백분율로 포함되어 있습니다. 적용된 태그와 연관된 신뢰도를 나타냅니다. 자동으로 적용된 스마트 태그를 중재할 수 있습니다.

## 태그 추가 또는 업데이트 {#manually-tag}

[!DNL Adobe Sensei] 스마트 서비스를 사용하여 자동으로 추가되는 스마트 태그 외에도 자산에 태그를 더 추가할 수 있습니다. 미리 볼 자산을 열고 [!UICONTROL Tags] 을 클릭한 다음 [!UICONTROL Keywords] 필드에 원하는 키워드를 입력합니다. 태그를 추가하려면 Return 키를 누릅니다. [!DNL Assets Essentials] 키워드를 거의 실시간으로 인덱싱하며 팀이 곧 새 키워드를 사용하여 업데이트된 자산을 검색할 수 있습니다.

[!DNL Assets Essentials]에 의해 자동으로 추가된 [!UICONTROL Smart Tags] 섹션에서 업로드된 모든 자산에 태그를 제거할 수도 있습니다.

<!-- TBD: Queries for PM and engg.

Can we edit the existing metadata in any form?

How to moderate smart tags?

Allow or deny list for smart tags?

What about Tags displayed just above Smart Tags in the UI?

Is there a detailed metadata tab. Where do the other details of an asset go?

How can one search based strictly on the metadata. Similar to AEM Assets GQL queries.
-->

<!-- TBD: Link to related articles if any.

>[!MORELIKETHIS]
>
>* [Search assets](search.md).
-->
