---
title: 메타데이터 관리
description: 에 있는 자산의 메타데이터 관리 [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: cfc105d1-41fc-4418-9905-b2a28a348682
source-git-commit: cd7af0c946a042430e62528fa6aa19bdab139f67
workflow-type: tm+mt
source-wordcount: '962'
ht-degree: 0%

---

# 의 메타데이터 [!DNL Assets Essentials] {#metadata}

메타데이터는 데이터에 대한 데이터 또는 설명을 의미합니다. 예를 들어, 자산으로 이미지에는 클릭한 카메라 정보 또는 저작권 정보가 포함될 수 있습니다. 이 정보는 이미지의 메타데이터입니다. 메타데이터는 효율적인 자산 관리를 위해 매우 중요합니다. 메타데이터는 자산에 사용할 수 있는 모든 데이터의 수집이지만 해당 자산에 포함되어 있을 필요는 없습니다.

메타데이터는 자산을 더 분류하는 데 도움이 되며, 디지털 정보의 양이 늘어나면 유용합니다. 파일 이름, 축소판 및 메모리만 기준으로 수백 개의 파일을 관리할 수 있습니다. 그러나 이 방법은 확장 가능하지 않습니다. 관련된 사람의 수와 관리되는 자산의 수가 증가하면 부족합니다.

메타데이터가 추가되면 자산이 만들어지므로 디지털 자산의 값이 증가합니다.

* 보다 손쉽게 액세스 가능 - 시스템과 사용자가 쉽게 찾을 수 있습니다.
* 관리가 쉬워짐 - 동일한 속성 세트를 더 쉽게 사용하여 자산을 찾고 변경 사항을 적용할 수 있습니다.
* 완료 - 자산은 더 많은 정보와 더 많은 메타데이터를 사용하여 컨텍스트를 전달합니다.

이러한 이유로 Assets는 디지털 자산에 대한 메타데이터를 만들고, 관리하고 교환하는 올바른 방법을 제공합니다.

## 메타데이터 보기 {#view-metadata}

자산의 메타데이터를 보려면, 자산으로 이동하거나 자산을 검색하고, 자산을 선택한 다음 를 클릭합니다 **[!UICONTROL 세부 사항]** 클릭합니다.

![자산의 메타데이터 보기](assets/metadata-view1.png)

*그림: 자산 및 해당 메타데이터를 보려면&#x200B;**[!UICONTROL 세부 사항]**도구 모음에서 자산을 두 번 클릭합니다.*

제목, 설명 및 업로드 날짜와 같은 기본 메타데이터는 [!UICONTROL 기본] 탭. 다음 [!UICONTROL 고급] 탭에는 카메라 모델, 렌즈 세부 사항 및 지오태그와 같은 고급 메타데이터가 포함되어 있습니다. 다음 [!UICONTROL 태그] 탭에는 이미지의 컨텐츠를 기반으로 자동으로 적용된 태그가 포함되어 있습니다.

## 메타데이터 업데이트 {#update-metadata}

몇 개의 메타데이터 필드를 수동으로 업데이트할 수 있습니다. 필드는 다음과 같습니다 [!UICONTROL 제목], [!UICONTROL 설명], [!UICONTROL 작성자], 및 [!UICONTROL 키워드].

## 태그 {#tags}

[!DNL Assets Essentials] 에서 제공하는 인공 지능 사용 [Adobe Sensei](https://www.adobe.com/kr/sensei.html) 업로드한 모든 자산에 관련 태그를 자동으로 적용하려면 적절한 이름의 이러한 태그는 관련 자산을 신속하게 찾을 수 있도록 하여 프로젝트의 컨텐츠 속도를 높입니다. 스마트 태그는 이미지에 포함되지 않은 메타데이터의 예입니다.

스마트 태그는 거의 실시간으로 적용되며 이미지의 내용을 기반으로 생성됩니다. 자산을 업로드하면 사용자 인터페이스가 표시됩니다 [!UICONTROL 처리 중] 자산 축소판에 잠시 있습니다. 처리가 완료되면 다음 작업을 수행할 수 있습니다 [메타데이터 보기](#view-metadata) 그리고 스마트 태그를 사용하여 태그를 만들 수 있습니다.

![자산의 스마트 태그 보기](assets/metadata-view-tags.png)

*그림: 자산의 스마트 태그를 보려면&#x200B;**[!UICONTROL 세부 사항]**도구 모음에서 자산을 두 번 클릭합니다.*

스마트 태그에는 신뢰도 점수가 백분율로 포함되어 있습니다. 적용된 태그와 연관된 신뢰도를 나타냅니다. 자동으로 적용된 스마트 태그를 중재할 수 있습니다.

## 태그 추가 또는 업데이트 {#manually-tag}

를 사용하여 자동으로 추가되는 스마트 태그 외에도 자산에 태그를 더 추가할 수 있습니다 [!DNL Adobe Sensei] 스마트 서비스. 미리 볼 자산을 열고 를 클릭합니다 [!UICONTROL 태그], 및에서 원하는 키워드를 입력합니다. [!UICONTROL 키워드] 필드. 태그를 추가하려면 Return 키를 누릅니다. [!DNL Assets Essentials] 키워드를 거의 실시간으로 인덱싱하며 팀이 곧 새 키워드를 사용하여 업데이트된 자산을 검색할 수 있습니다.

또한 [!UICONTROL 스마트 태그] 섹션에 자동으로 추가됩니다. [!DNL Assets Essentials] 업로드한 모든 자산에 매핑됩니다.

## 메타데이터 양식 {#metadata-forms}

Assets Essentials은 기본적으로 많은 표준 메타데이터 필드를 제공합니다. 조직에는 추가적인 메타데이터 요구 사항이 있으며 비즈니스별 메타데이터를 추가하려면 더 많은 메타데이터 필드가 필요합니다. 메타데이터 양식을 사용하면 기업이 사용자 지정 메타데이터 필드를 자산의 [!UICONTROL 세부 사항] 페이지. 비즈니스별 메타데이터는 자산의 거버넌스 및 검색을 개선합니다.

다양한 유형의 자산(다른 MIME 유형)에 대한 메타데이터 양식을 구성할 수 있습니다. 파일의 MIME 유형과 동일한 양식 이름을 사용하십시오. Essentials는 업로드된 자산을 양식 이름에 자동으로 일치시킵니다. 예를 들어 이름이 `PDF` 또는 `pdf` 가 존재하면 업로드된 PDF 문서에는 양식에 정의된 메타데이터 필드가 포함됩니다. 처음부터 양식을 만들거나 기존 양식을 재사용할 수 있습니다.

>[!IMPORTANT]
>
>특정 파일 형식에 대한 새 메타데이터 양식은 [!DNL Assets Essentials] 을 참조하십시오. 메타데이터 양식을 삭제하거나 이름을 바꾸면 새 자산에 기본 메타데이터 필드를 다시 사용할 수 있습니다.

메타데이터 양식을 만들려면 다음 단계를 수행합니다.

1. 왼쪽 레일에서 를 클릭합니다. **[!UICONTROL 설정]** > **[!UICONTROL 메타데이터 Forms]**.

   ![왼쪽 사이드바의 메타데이터 양식 옵션](assets/metadata-forms-sidebar.png)

1. 클릭 **[!UICONTROL 만들기]**&#x200B;를 입력합니다.
1. 양식 이름을 입력하고 **[!UICONTROL 만들기]**.
1. 에서 탭의 이름을 입력합니다 **[!UICONTROL 설정]** 오른쪽 레일에 있습니다.
1. 에서 **[!UICONTROL 구성 요소]** 왼쪽 레일에서 사용할 수 있는 경우, 양식의 탭에서 필요한 구성 요소를 드래그합니다. 원하는 시퀀스에서 구성 요소를 드래그합니다.

   ![왼쪽 사이드바의 메타데이터 양식 옵션](assets/metadata-form-new.png)

   *그림: 구성 요소를 추가할 수 있는 옵션과 양식을 미리 볼 수 있는 옵션이 포함된 메타데이터 양식 만들기 인터페이스입니다.*

1. 각 구성 요소에 대해 **[!UICONTROL 설정]** 오른쪽 레일에서 지원되는 속성이 있는 매핑을 제공합니다.
1. 구성 요소에 대해 다음을 선택합니다(선택적) **[!UICONTROL 필수 여부]** 메타데이터 필드를 필수로 설정하려면 다음을 선택합니다 **[!UICONTROL 읽기 전용]** 자산에서 필드를 편집할 수 없도록 하려면 [!UICONTROL 세부 사항] 페이지.
1. 원할 경우 **[!UICONTROL 미리 보기]** 만들 양식을 미리 보려면
1. 선택적으로, 각 탭에 탭과 필요한 구성 요소를 더 추가합니다.
1. 클릭 **[!UICONTROL 저장]** 양식이 완료되면

양식이 만들어지면 사용자가 일치하는 MIME 유형의 자산을 업로드할 때 자동으로 적용됩니다.

기존 양식을 다시 사용하여 새 양식을 만들려면 메타데이터 양식을 선택하고 **[!UICONTROL 복사]** 도구 모음에서 이름을 입력하고 **[!UICONTROL 확인]**. 메타데이터 양식을 편집하여 변경할 수 있습니다. 양식을 변경할 때 변경 후 업로드된 자산에 사용됩니다. 기존 자산은 변경되지 않습니다.

<!-- TBD: Cannot create a form using the second option. Documenting only the first option for now.
To reuse an existing form to create a new form, do one of these:

* Select a metadata form and click **[!UICONTROL Copy]** from the toolbar, provide a name, and click **[!UICONTROL Confirm]**.

* Click **[!UICONTROL Create]**, select **[!UICONTROL Use existing form structure as template]** option, and select an existing form. 
-->

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
