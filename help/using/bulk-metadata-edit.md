---
title: Assets Essentials의 벌크 메타데이터 편집
description: Assets Essentials에서 동시에 사용할 수 있는 여러 에셋에 대해 사전 정의된 표준 메타데이터 필드 세트를 업데이트하는 방법에 대해 알아봅니다.
exl-id: 17185160-6c51-4581-a716-77b365ef3dd9
source-git-commit: 461773235cb2d27d334b5ceb23f959dc9a848716
workflow-type: tm+mt
source-wordcount: '508'
ht-degree: 4%

---


<table>
    <tr>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="새 항목">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-prime-ultimate"><b>Dynamic Media Prime 및 Ultimate</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="새 항목">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/assets-ultimate-overview"><b>AEM Assets Ultimate</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="새 항목">
            <a href="http://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/integrate-aem-assets-edge-delivery-services"><b>Edge Delivery Services과 AEM Assets 통합</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="새 항목">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/assets-view/aem-assets-view-ui-extensibility"><b>UI 확장성</b></a>
        </td>
          <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="새 항목">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-assets-essentials/help/custom-search-filters"><b>사용자 지정 검색 필터</b></a>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/best-practices/search-best-practices"><b>모범 사례 검색</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/best-practices/metadata-best-practices"><b>메타데이터 모범 사례</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/product-overview"><b>Content Hub</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/dynamic-media-open-apis-overview"><b>OpenAPI 기능이 포함된 Dynamic Media</b></a>
        </td>
        <td>
            <a href="https://developer.adobe.com/experience-cloud/experience-manager-apis/"><b>AEM Assets 개발자 설명서</b></a>
        </td>
    </tr>
</table>

# Assets Essentials의 벌크 메타데이터 편집{#how-to-edit-the-metadata-of-multiple-assets-simultaneously}

Assets Essentials 내의 **일괄 메타데이터 편집** 기능을 사용하면 여러 에셋 파일에 대한 사전 정의된 표준 메타데이터 필드 집합을 동시에 편집할 수 있습니다. 각 에셋에 대한 표준 메타데이터를 개별적으로 업데이트하는 대신, 여러 에셋을 선택하고 사전 정의된 표준 메타데이터 세트를 한 번에 일괄 업데이트합니다. 이 기능은 대규모 에셋 세트에서 표준 메타데이터 속성의 효율성, 일관성 및 정확성을 향상시켜 에셋 검색 및 구성을 향상시킵니다.

## 자산 메타데이터 벌크 편집 {#how-to-bulk-edit-the-metadata-of-multiple-assets-on-assets-essentials}

다음 단계를 실행하여 여러 에셋의 메타데이터를 한 번에 일괄 편집합니다.

1. Assets Essentials에서 **Assets**&#x200B;을(를) 클릭합니다.
1. 특정 에셋을 찾아보거나 검색 막대에서 키워드를 사용하여 검색합니다.
1. 자산을 선택하고 상단 메뉴에서 **일괄 메타데이터 편집**을 클릭합니다.
   ![일괄 메타데이터 편집](/help/using/assets/bulk-metadata-edit1.png)
1. 메타데이터 편집 페이지에서 **속성** 패널에서 다음 필드를 편집합니다.
   * **상태:** 선택한 자산의 상태를 선택합니다.
   * **만료 날짜:** 자산이 더 이상 유효하지 않거나 필요하지 않은 날짜를 설정합니다.
   * **작성자:** 작성자 이름을 지정합니다.
   * **키워드:** 검색 기능을 향상시키기 위해 자산에 대한 높은 수준의 정보를 제공하는 특정 용어나 텍스트 문자열을 추가합니다. 키워드를 추가하고 Enter 키를 누르거나 Return 키를 눌러 목록에 다른 키워드를 추가합니다.
   * **태그:** 사용 가능한 옵션에서 태그를 선택하려면 ![태그 아이콘](/help/using/assets/tags-icon.svg)을 클릭하십시오. 태그는 에셋에 대한 보다 구체적인 정보를 제공하고 검색 기능을 향상시킵니다. 선택한 자산에 이미 적용된 태그가 **속성** 패널에 표시됩니다. 관련 태그를 찾을 수 없는 경우 해당 태그를 만들어 선택한 에셋에 할당합니다. 에셋에 태그를 만들고 할당하는 방법에 대한 자세한 내용은 [Assets Essentials의 태그 관리](/help/using/tagging-management.md)를 참조하십시오.
   * 위의 메타데이터 업데이트를 선택한 자산에 적용하려면 **저장**을 클릭하십시오. 저장하면 키워드 및 태그가 추가되고 상태, 만료 날짜 및 작성자에 대한 업데이트된 세부 정보가 기존 세부 정보를 덮어씁니다.
     ![save-bulk-metadata-edit-properties](/help/using/assets/save-bulk-metadata-edit-properties2.png)

     >[!NOTE]
     >
     >한 번에 100개의 에셋의 메타데이터를 편집할 수 있습니다.

에셋에 적용된 메타데이터 업데이트를 보려면 에셋 세부 정보 페이지로 이동하고(에셋을 선택하고 **세부 정보**&#x200B;을 클릭) ![](/help/using/assets/info-icon-solid-black.svg)을(를) 클릭하여 **정보** 패널에서 에셋의 메타데이터를 확인합니다.

>[!NOTE]
>
>**상태**, **만료 날짜**, **작성자**, **키워드** 및 **태그**&#x200B;는 폴더별 메타데이터와 관계없이 일괄 메타데이터 편집에 사용할 수 있는 표준 메타데이터 속성입니다. 이러한 메타데이터 속성은 에셋의 폴더에 적용된 메타데이터 양식에 포함된 경우에만 에셋 세부 정보 페이지에 표시됩니다. 자산 세부 사항 페이지에서 이러한 표준 메타데이터 속성을 찾을 수 없는 경우 포함할 자산 폴더의 메타데이터 양식을 편집하십시오. 메타데이터 양식을 만들거나 편집하고 폴더에 적용하는 방법에 대해 알아보려면 [Assets Essentials의 메타데이터](/help/using/metadata.md)를 참조하십시오.
