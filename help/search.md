---
title: ' [!DNL Assets Essentials]에서 자산 검색 및 검색'
description: ' [!DNL Assets Essentials]에서 자산을 검색하고 검색합니다.'
role: Business Practitioner
source-git-commit: 3389908e3ba085362b48a18cd3c106e658484a96
workflow-type: tm+mt
source-wordcount: '386'
ht-degree: 1%

---


# [!DNL Assets Essentials] {#search-assets}에서 자산 검색

[!DNL Assets Essentials] 은 기본적으로 작동하는 효과적인 검색을 제공합니다. 전체 텍스트 검색이므로 검색은 포괄적입니다. 강력한 검색 기능을 사용하면 적절한 자산을 빠르게 찾고 컨텐츠 속도를 향상시킬 수 있습니다. [!DNL Assets Essentials] 은 전체 텍스트 검색을 제공하고 스마트 태그, 제목, 만든 날짜 및 저작권 등의 메타데이터를 통해 검색할 수 있습니다.

자산을 검색하려면,

* 페이지 상단에 있는 검색 상자에서 를 클릭합니다. 기본적으로 현재 탐색 중인 폴더 내에서 검색합니다. 다음 중 하나를 수행하십시오.

   ![검색 상자](assets/search-box.png)

   * 키워드를 사용하여 검색하고 선택적으로 폴더를 변경합니다. Return 키를 누릅니다.

   * 직접 검색하여 최근에 본 자산으로 작업을 시작합니다. 검색 상자에서 를 클릭하고 제안에서 최근에 본 자산을 선택합니다.

## 검색 결과 필터링 {#refine-search-results}

다음 매개 변수를 기반으로 검색 결과를 필터링할 수 있습니다.

![검색 필터](assets/filters1.png)

*그림:다양한 매개 변수를 기반으로 검색된 자산을 필터링합니다.*

* 파일 형식:지원되는 파일 형식, `Images`, `Documents` 및 `Videos`별로 검색 결과를 필터링합니다.
* MIME 유형:지원되는 파일 형식 중 하나 이상을 필터링합니다.<!-- TBD:  [supported file formats](/help/supported-file-formats.md). -->
* 이미지 크기:이미지를 필터링할 최소 및 최대 차원 중 하나 이상을 제공합니다. 크기는 픽셀 단위로 제공되며 이미지의 파일 크기가 아닙니다.
* 날짜 만들기:메타데이터에 제공된 자산의 생성 날짜입니다. 사용되는 표준 날짜 형식은 `yyyy-mm-dd`입니다.
* 수정한 날짜:자산의 마지막 수정 날짜입니다. 사용되는 표준 날짜 형식은 `yyyy-mm-dd`입니다.

`Name`, `Relevancy`, `Size`, `Modified` 및 `Created`의 순서를 늘이거나 줄이면 검색된 자산을 정렬할 수 있습니다.

## 저장된 검색 {#saved-search}

검색 기능은 [!DNL Assets Essentials]에서 매우 쉽게 사용할 수 있습니다. 검색 상자 내에서 키워드를 입력하고 Return 키를 눌러 결과를 볼 수 있을 뿐만 아니라 한 번의 클릭으로 최근에 검색한 키워드를 다시 빠르게 검색할 수도 있습니다.

메타데이터 및 자산 유형에 대한 특정 기준에 따라 검색 결과를 필터링할 수도 있습니다. 자주 사용하는 필터의 경우 검색 경험을 향상시키기 위해 [!DNL Assets Essentials]을(를) 사용하여 검색 매개 변수를 저장할 수 있습니다. 그런 다음 저장된 검색을 선택하여 검색하고 한 번의 클릭으로 필터를 적용할 수도 있습니다.

저장된 검색을 만들려면 일부 자산을 검색하고, 하나 이상의 필터를 적용하고 [!UICONTROL Filters] 패널에서 [!UICONTROL Save Search] 를 클릭합니다.

![필터 패널에서 저장된 검색](assets/saved-search.png)

<!-- TBD: Search behavior. Full-text search. Ranking and rank boosts. Hidden assets.
Report poor UX that users can only save a filtered search and not a simple search.
.
Are other supported files fully indexed and support full-text search? Eg. audio/videos files can at best have metadata indexed.
Anything about ranking of assets displayed in search results?

What about temporarily hiding an asset (suspending search on it) from the search results? If an asset is undergoing review collaboration, should it be used by others? Should it be hidden in search?

When userA is searching and userB add an asset that matches search results, will the asset display in search as soon as userA refreshes the page? Assuming indexing is near real-time. May not be so for bulk uploads.
-->
