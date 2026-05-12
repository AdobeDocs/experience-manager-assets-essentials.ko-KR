---
title: Assets Essentials에서 메타데이터 일괄 편집
description: Assets Essentials에서 동시에 사용할 수 있는 여러 에셋에 대해 사전 정의된 표준 메타데이터 필드 세트를 업데이트하는 방법에 대해 알아봅니다.
exl-id: 17185160-6c51-4581-a716-77b365ef3dd9
TQID: https://experienceleague.adobe.com/zfRAzwQWEhdCwSVuWKDz-ndudFtv-mIhmjzyNkg8sOQ
product_v2: id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
feature_v2: id: a01bfd36-4ab8-4bf8-9dc0-5b45b890552e
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554id: f8a45b24-4be7-4f1b-909b-60d06b483a20
topic_v2: id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
source-git-commit: f026b389ce582ece5d2ca8745d291b1ae50d657e
workflow-type: tm+mt
source-wordcount: 649
ht-degree: 100%

---

<table>
    <tr>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="신규">
            <a href="https://experienceleague.adobe.com/ko/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-prime-ultimate"><b>Dynamic Media Prime 및 Ultimate</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="신규">
            <a href="https://experienceleague.adobe.com/ko/docs/experience-manager-cloud-service/content/assets/assets-ultimate-overview"><b>AEM Assets Ultimate</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="신규">
            <a href="http://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/integrate-aem-assets-edge-delivery-services"><b>Edge Delivery Services와 AEM Assets 통합</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="신규">
            <a href="https://experienceleague.adobe.com/ko/docs/experience-manager-cloud-service/content/assets/assets-view/aem-assets-view-ui-extensibility"><b>UI 확장성</b></a>
        </td>
          <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="신규">
            <a href="https://experienceleague.adobe.com/ko/docs/experience-manager-assets-essentials/help/custom-search-filters"><b>사용자 정의 검색 필터</b></a>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://experienceleague.adobe.com/ko/docs/experience-manager-cloud-service/content/assets/best-practices/search-best-practices"><b>모범 사례 검색</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/ko/docs/experience-manager-cloud-service/content/assets/best-practices/metadata-best-practices"><b>메타데이터 모범 사례</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/ko/docs/experience-manager-cloud-service/content/assets/content-hub/product-overview"><b>Content Hub</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/ko/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/dynamic-media-open-apis-overview"><b>OpenAPI 기능이 포함된 Dynamic Media</b></a>
        </td>
        <td>
            <a href="https://developer.adobe.com/experience-cloud/experience-manager-apis/"><b>AEM Assets 개발자 설명서</b></a>
        </td>
    </tr>
</table>

# Assets Essentials에서 메타데이터 일괄 편집{#how-to-edit-the-metadata-of-multiple-assets-simultaneously}

Assets Essentials에서 **일괄 메타데이터 편집** 기능을 사용하면 여러 에셋 파일에 대한 사전 정의된 표준 메타데이터 필드 세트를 동시에 편집할 수 있습니다. 각 에셋에 대한 표준 메타데이터를 개별적으로 업데이트하는 대신, 여러 에셋을 선택하고 사전 정의된 표준 메타데이터 세트를 한 번에 일괄 업데이트합니다. 이 기능은 대규모 에셋 세트에서 표준 메타데이터 속성의 효율성, 일관성 및 정확성을 개선하여 에셋 검색 및 구성을 향상합니다.

## 에셋 메타데이터 일괄 편집 {#how-to-bulk-edit-the-metadata-of-multiple-assets-on-assets-essentials}

다음 단계를 실행하여 여러 에셋의 메타데이터를 한 번에 일괄 편집합니다.

1. Assets Essentials에서 **에셋**&#x200B;을 클릭합니다.
1. 특정 에셋을 찾아보거나 검색 창에서 키워드를 사용하여 검색합니다.
1. 에셋을 선택하고 상단 메뉴에서 **일괄 메타데이터 편집**을 클릭합니다.
   ![일괄 메타데이터 편집](/help/using/assets/bulk-metadata-edit1.png)
1. 메타데이터 편집 페이지의 **속성** 패널에서 다음 필드를 편집합니다.
   * **상태:** 선택한 에셋의 상태를 선택합니다.
   * **만료 날짜:** 에셋이 더 이상 유효하지 않거나 필요하지 않은 날짜를 설정합니다.
   * **작성자:** 작성자 이름을 지정합니다.
   * **키워드:** 검색 기능을 향상하기 위해 에셋에 대한 높은 수준의 정보를 제공하는 특정 용어나 텍스트 문자열을 추가합니다. 키워드를 추가하고 Enter 키를 누르거나 Return 키를 눌러 목록에 다른 키워드를 추가합니다.
   * **태그:** 사용 가능한 옵션에서 태그를 선택하려면 ![태그 아이콘](/help/using/assets/tags-icon.svg)을 클릭합니다. 태그는 에셋에 대한 보다 구체적인 정보를 제공하고 검색 기능을 향상합니다. 선택한 에셋에 이미 적용된 태그는 **속성** 패널에 표시됩니다. 관련 태그를 찾을 수 없는 경우 해당 태그를 만들어 선택한 에셋에 할당합니다. 에셋에 태그를 만들고 할당하는 방법에 대한 자세한 내용은 [Assets Essentials의 태그 관리](/help/using/tagging-management.md)를 참조하십시오.
   * 위의 메타데이터 업데이트를 선택한 에셋에 적용하려면 **저장**을 클릭합니다. 저장 시 키워드 및 태그가 추가되고 상태, 만료 날짜 및 작성자에 대한 업데이트된 세부 정보가 기존 세부 정보를 덮어씁니다.
     ![메타데이터 일괄 저장-속성 편집](/help/using/assets/save-bulk-metadata-edit-properties2.png)

     >[!NOTE]
     >
     >한 번에 100개의 에셋의 메타데이터를 편집할 수 있습니다.

에셋에 적용된 메타데이터 업데이트를 보려면 에셋 세부 정보 페이지로 이동(에셋을 선택하고 **세부 정보**&#x200B;를 클릭)한 다음 ![](/help/using/assets/info-icon-solid-black.svg)를 클릭하여 **정보** 패널에서 에셋의 메타데이터를 확인합니다.

>[!NOTE]
>
>**상태**, **만료 날짜**, **작성자**, **키워드** 및 **태그**&#x200B;는 폴더별 메타데이터와 관계없이 일괄 메타데이터 편집에 사용할 수 있는 표준 메타데이터 속성입니다. 이러한 메타데이터 속성은 에셋의 폴더에 적용된 메타데이터 양식에 포함된 경우에만 에셋 세부 정보 페이지에 표시됩니다. 에셋 세부 정보 페이지에서 이러한 표준 메타데이터 속성을 찾을 수 없는 경우 포함할 에셋 폴더의 메타데이터 양식을 편집합니다. 메타데이터 양식을 만들거나 편집하고 폴더에 적용하는 방법에 대해 알아보려면 [Assets Essentials의 메타데이터](/help/using/metadata.md)를 참조하십시오.
