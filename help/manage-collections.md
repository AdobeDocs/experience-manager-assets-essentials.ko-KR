---
title: 컬렉션 관리
description: 컬렉션은 Experience Manager Assets Essentials에 포함된 자산 세트입니다. 컬렉션을 사용하여 사용자 간에 자산을 공유합니다.
source-git-commit: 3496f7dea36c47b1fb41d39282ad6028def74499
workflow-type: tm+mt
source-wordcount: '481'
ht-degree: 8%

---

# 컬렉션 관리 {#manage-collections}

컬렉션은 Experience Manager Assets Essentials에 포함된 자산 세트입니다. 컬렉션을 사용하여 사용자 간에 자산을 공유합니다.

폴더와 달리 컬렉션에는 다른 위치의 자산이 포함될 수 있습니다.

<!--
You can share collections with various users that are assigned different levels of privileges, including viewing, editing, and so on.
-->

여러 컬렉션을 사용자와 공유할 수 있습니다. 각 컬렉션에는 자산에 대한 참조가 포함되어 있습니다. 컬렉션 간에 자산의 참조 무결성이 유지됩니다.

다음 작업을 수행하여 컬렉션을 관리하고 사용할 수 있습니다.

* [컬렉션 만들기](#create-collection)

* [컬렉션에 자산 추가](#add-assets-to-collection)

* [컬렉션에 자산 제거](#remove-assets-from-collection)

* [컬렉션에 대한 액세스 관리](#manage-collection-access)

* [컬렉션 검색](#search-collections)

* [컬렉션 메타데이터 보기 및 편집](#view-edit-collection-metadata)

* [컬렉션 다운로드](#download-collection)

* [컬렉션 삭제](#delete-collection)

## 컬렉션 만들기 {#create-collection}

컬렉션을 만들려면:

1. 클릭 **[!UICONTROL 컬렉션]** 왼쪽 레일에서 를 클릭하고 **[!UICONTROL 컬렉션 만들기]**.

1. 컬렉션에 대한 제목과 선택적 설명을 지정합니다.

1. 클릭 **[!UICONTROL 저장]** 컬렉션을 만들려면

## 컬렉션에 자산 추가 {#add-assets-to-collection}

컬렉션에 자산을 추가하려면:

1. 클릭 **[!UICONTROL 자산]** 왼쪽 레일에서 자산을 선택합니다.

1. 클릭 **[!UICONTROL 컬렉션에 추가]**.

1. 설정 [!UICONTROL 컬렉션] 대화 상자에서 선택한 자산을 추가할 컬렉션을 선택합니다.

1. 클릭 **[!UICONTROL 추가]** 자산을 선택한 컬렉션에 추가합니다.

컬렉션에 자산을 추가하려면 **[!UICONTROL 컬렉션]** 왼쪽 레일에서 자산을 추가할 컬렉션을 클릭하고 **[!UICONTROL 컬렉션에 추가]**&#x200B;를 클릭하고 자산을 선택한 다음 를 클릭합니다 **[!UICONTROL 선택]**.

## 컬렉션에서 자산 제거 {#remove-assets-from-collection}

컬렉션에서 자산을 제거하려면 다음을 수행하십시오.

1. 클릭 **[!UICONTROL 컬렉션]** 왼쪽 레일에서 클릭하여 컬렉션 목록을 확인합니다.

1. 컬렉션을 클릭하고 컬렉션에서 제거해야 하는 자산을 선택합니다.

1. **[!UICONTROL 제거]**&#x200B;를 클릭합니다.

<!--

## Manage access to a collection {#manage-collection-access}

The permission management for collections function in the same manner as folders in [!DNL Assets Essentials]. Administrators can manage the access levels for collections available in the repository. As an administrator, you can create user groups and assign permissions to those groups to manage access levels. You can also delegate the permission management privileges to user groups at the collection-level.

For more information, see [Manage permissions for folders and collections](manage-permissions.md).

## Search a collection {#search-collections}

Click **[!UICONTROL Collections]** in the left rail and use the Search box to specify a text as the criteria to search for a collection. [!DNL Assets Essentials] uses the specified text to search collection names, metadata including tags defined for a collection and returns appropriate results.

>[!NOTE]
>
>Assets Essentials performs search in collections available at the root level. It does not perform search in assets and folders available in collections.

-->

## 컬렉션 메타데이터 보기 및 편집 {#view-edit-collection-metadata}

컬렉션 메타데이터는 제목 및 설명과 같은 컬렉션에 대한 데이터를 포함합니다.

컬렉션 메타데이터를 보고 편집하려면:

1. 클릭 **[!UICONTROL 컬렉션]** 왼쪽 레일에서 컬렉션을 선택하고 **[!UICONTROL 세부 사항]**.
1. 를 사용하여 컬렉션 메타데이터 보기 **[!UICONTROL 기본]** 탭.
1. 필요에 따라 메타데이터 필드를 수정합니다. 을 수정할 수 있습니다 [!UICONTROL 제목], [!UICONTROL 설명], 및 [!UICONTROL 작성자] 필드.

## 컬렉션에 대한 링크 공유 {#share-collection-links}

[!DNL Assets Essentials] 링크를 생성하고 외부 이해 관계자와 컬렉션 및 자산을 공유할 수 있습니다 [!DNL Assets Essentials] 응용 프로그램. 해당 링크에 대한 만료일을 정의한 다음 이메일 또는 메시징 서비스와 같이 선호하는 커뮤니케이션 수단을 사용하여 다른 사용자와 공유할 수 있습니다. 링크 수신자는 에셋을 미리 보고 다운로드할 수 있습니다.

외부 이해 관계자와 컬렉션 링크를 공유하는 방법에 대한 자세한 내용은 다음을 참조하십시오 [자산에 대한 링크 공유](share-links-for-assets.md).

## 컬렉션 요소 다운로드 {#download-collection-elements}

컬렉션 요소를 다운로드하려면 다음을 수행하십시오.

1. 클릭 **[!UICONTROL 컬렉션]** 왼쪽 레일에 있습니다.

1. 컬렉션을 클릭하고 다운로드할 요소를 선택합니다.

1. 클릭 **[!UICONTROL 다운로드]**.

1. 설정 [!UICONTROL 자산 다운로드] 대화 상자 **[!UICONTROL 확인]**.

선택한 컬렉션 요소는 로컬 시스템에서 .ZIP 파일로 다운로드됩니다.

## 컬렉션 삭제 {#delete-collection}

컬렉션을 삭제하려면

1. 클릭 **[!UICONTROL 컬렉션]** 왼쪽 레일에 있습니다.

1. 삭제할 컬렉션을 선택합니다.

1. **[!UICONTROL 삭제]**&#x200B;를 클릭합니다. 
