---
title: ' [!DNL Assets Essentials]에서 에셋 검색 및 탐색'
description: ' [!DNL Assets Essentials]에서 에셋을 검색하고 탐색합니다.'
role: User
exl-id: be9597a3-056c-436c-a09e-15a03567c85a
source-git-commit: cd7af0c946a042430e62528fa6aa19bdab139f67
workflow-type: ht
source-wordcount: '389'
ht-degree: 100%

---

# [!DNL Assets Essentials]에서 에셋 검색 {#search-assets}

[!DNL Assets Essentials]는 기본적으로 작동하는 효과적인 검색 기능을 제공합니다. 검색 기능은 전체 텍스트 검색이므로 포괄적입니다. 강력한 검색 기능을 통해 적절한 에셋을 빠르게 찾고 콘텐츠 속도를 높일 수 있습니다. [!DNL Assets Essentials]는 스마트 태그, 제목, 생성 날짜 및 저작권과 같은 메타데이터를 통해 전체 텍스트 검색 및 다중 검색 기능을 제공합니다.

에셋을 검색하려면

* 페이지 상단의 검색 상자를 클릭합니다. 기본적으로 현재 탐색 중인 폴더 내에서 검색됩니다. 다음 중 하나를 수행하십시오.

   ![검색 상자](assets/search-box.png)

   * 키워드를 사용하여 검색하고 필요한 경우 폴더를 변경합니다. Return 키를 누릅니다.

   * 직접 검색하여 최근에 본 에셋으로 작업을 시작하십시오. 검색 상자를 클릭하고 제안에서 최근에 본 에셋을 선택합니다.

## 검색 결과 필터링 {#refine-search-results}

다음 매개 변수를 기반으로 검색 결과를 필터링할 수 있습니다.

![검색 필터](assets/filters1.png)

*그림: 다양한 매개 변수를 기반으로 검색된 에셋을 필터링합니다.*

* 파일 형식: 지원되는 파일 형식(`Images`, `Documents` 및 `Videos`)으로 검색 결과를 필터링합니다.
* MIME 유형: 지원되는 파일 형식 중 하나 이상을 필터링합니다. <!-- TBD:  [supported file formats](/help/supported-file-formats.md). -->
* 이미지 크기: 이미지를 필터링할 최소 및 최대 크기 중 하나 이상을 제공합니다. 크기는 픽셀 단위의 치수로 제공되며 이는 이미지의 파일 크기가 아닙니다.
* 생성 날짜: 메타데이터에 입력된 에셋 생성 날짜입니다. 사용되는 표준 날짜 형식은 `yyyy-mm-dd`입니다.
* 수정 날짜: 에셋이 마지막으로 수정된 날짜입니다. 사용되는 표준 날짜 형식은 `yyyy-mm-dd`입니다.

검색된 에셋을 `Name`, `Relevancy`, `Size`, `Modified` 및 `Created`의 오름차순 또는 내림차순으로 정렬할 수 있습니다.

## 저장된 검색 {#saved-search}

검색 기능은 [!DNL Assets Essentials]에서 사용하기 매우 간단합니다. 검색 상자 내에서 키워드를 입력하고 Return 키를 눌러 결과를 볼 수 있을 뿐만 아니라 한 번의 클릭으로 최근 검색한 키워드를 빠르게 다시 검색할 수 있습니다.

메타데이터 및 에셋 유형에 대한 특정 기준에 따라 검색 결과를 필터링할 수도 있습니다. 자주 사용하는 필터의 경우 검색 경험을 개선하기 위해 [!DNL Assets Essentials]을 사용하여 검색 매개 변수를 저장할 수 있습니다. 그런 다음 저장된 검색을 선택하여 한 번의 클릭으로 필터를 검색하고 적용할 수 있습니다.

저장된 검색을 생성하려면 일부 에셋을 검색하고 하나 이상의 필터를 적용한 다음 [!UICONTROL 필터] 패널에서 [!UICONTROL 검색 저장]을 클릭하십시오.

![필터 패널에서 저장된 검색](assets/saved-search.png)

<!-- TBD: Search behavior. Full-text search. Ranking and rank boosts. Hidden assets.
Report poor UX that users can only save a filtered search and not a simple search.
.
Are other supported files fully indexed and support full-text search? Eg. audio/videos files can at best have metadata indexed.
Anything about ranking of assets displayed in search results?

What about temporarily hiding an asset (suspending search on it) from the search results? If an asset is undergoing review collaboration, should it be used by others? Should it be hidden in search?

When userA is searching and userB add an asset that matches search results, will the asset display in search as soon as userA refreshes the page? Assuming indexing is near real-time. May not be so for bulk uploads.
-->
