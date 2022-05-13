---
title: Adobe Workfront과 Assets Essentials 통합
description: Workfront 애플리케이션 내의 Assets Essentials 리포지토리에 액세스할 수 있도록 Assets Essentials을 Adobe Workfront 애플리케이션과 통합합니다.
source-git-commit: 7d49060ba2e02bd9c5caf9753ef56b5feed5b3df
workflow-type: tm+mt
source-wordcount: '616'
ht-degree: 16%

---


# Adobe Workfront과 Assets Essentials 통합 {#integrate-assets-essentials-workfront}

![어두운 테마 및 밝은 테마 전환 환경 설정](assets/cce-workfront.png)

## 지금까지 그 이야기

후 [Experience Manager Assets Essentials 구성](adminster-aem-assets-essentials.md) 및 [Creative Cloud 응용 프로그램과 Assets Essentials 통합](integrate-assets-essentials-creative-cloud.md)를 빌드하여 Adobe Workfront 애플리케이션을 Assets Essentials과 통합할 수 있습니다.

## 목표

* **Audience**: Adobe Workfront 관리자

* **목표**: Workfront 애플리케이션 내의 Assets Essentials 리포지토리에 액세스할 수 있도록 Assets Essentials을 Adobe Workfront 애플리케이션과 통합합니다.

## 개요

[[!DNL Adobe Workfront]](https://www.workfront.com/) 은 한 곳에서 전체 작업 수명 주기를 관리하는 데 도움이 되는 작업 관리 애플리케이션입니다. 간의 기본 통합 [!DNL Adobe Workfront] 및 [!DNL Assets Essentials] 을 사용하면 작업 및 자산 관리를 동적으로 연결하여 컨텐츠 제작 속도 및 시간을 향상시킬 수 있습니다. 작업 관리의 맥락에서 사용자는 동일한 솔루션에서 필요한 문서와 이미지에 액세스할 수 있습니다.

다음 작업을 실행하여 Workfront을 Experience Manager Assets Essentials와 통합합니다.

* [Workfront 제품 프로필에 사용자 추가](#add-users-to-product-profiles)

* [Assets Essentials 제품 프로필에 사용자 추가](#add-workfront-users-assets-essentials-product-profiles)

* [Experience Manager Assets Essentials 통합 구성](#configure-assets-essentials-integration)

## Workfront 제품 프로필에 사용자 추가 {#add-users-to-product-profiles}

Workfront 제품 프로필에 사용자를 추가하려면:

1. 액세스 [Admin Console](https://adminconsole.adobe.com) 조직의 경우 **[!UICONTROL 제품]** 상단 막대에서 **[!UICONTROL Workfront]**&#x200B;를 클릭하고 목록에서 첫 번째 인스턴스를 클릭합니다. 목록에서 두 번째 및 세 번째 인스턴스를 클릭하지 마십시오.

   ![Admin Console 관리자 프로필](assets/workfront-instances.png)

   Admin Console은 사용 가능한 제품 프로필만 표시합니다.

1. 제품 프로필에 사용자를 추가하려면 프로필을 클릭하고 **[!UICONTROL 사용자 추가]**&#x200B;를 클릭하고 사용자 세부 사항을 제공한 다음 를 클릭합니다. **[!UICONTROL 저장]**.

   ![사용자 관리자 프로필 추가](assets/add-users-workfront.png)

   사용자를 추가하면 사용자는 시작하라는 이메일 초대를 수신하게 됩니다. [!DNL Admin Console]의 제품 프로필 설정에서 이메일 초대를 비활성화할 수 있습니다.

1. 그룹에서 사용자를 제거하려면 그룹을 클릭하고 기존 사용자를 선택한 다음 **[!UICONTROL 사용자 제거]**&#x200B;를 선택합니다.

Adobe Admin Console을 사용하여 Workfront에서 사용자 및 시스템 관리자를 만드는 방법에 대한 자세한 내용은 [Adobe Admin Console에서 사용자 관리](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FAdministration_and_Setup%2FAdd_users%2FCreate_and_manage_users%2Fadmin-console.htm&amp;_LANG=enus).

## Assets Essentials 제품 프로필에 사용자 추가 {#add-workfront-users-assets-essentials-product-profiles}

다음 Assets Essentials 제품 프로필 중 하나에 Workfront 사용자를 할당합니다.

* **[!DNL Assets Essentials]사용자** 전체 Assets Essentials 사용자 인터페이스에 액세스할 수 있습니다. 이러한 사용자는 Assets Essentials 애플리케이션에서 디지털 자산을 업로드, 구성, 태그 지정 및 찾을 수 있습니다. 또한 사용자는에서 포함된 자산 선택 경험에 액세스할 수 있습니다 [!DNL Adobe Workfront] 응용 프로그램.
* **[!DNL Assets Essentials]소비자 사용자**: 에서 포함된 자산 선택 경험에 액세스할 수 있습니다. [!DNL Adobe Workfront] 응용 프로그램.

Assets Essentials 제품 프로필에 사용자를 할당하는 방법에 대한 자세한 내용은 [Assets Essentials 제품 프로필에 사용자 할당](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Experience Manager Assets Essentials 통합 구성 {#configure-assets-essentials-integration}

Admin Console을 사용하여 Workfront 및 Assets Essentials 제품 프로필에 사용자를 추가한 후 다음을 수행할 수 있습니다 [Experience Manager Assets Essentials 통합 구성](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2F_workfront-for-aem-asset-essentials.htm).

통합을 설정한 후 다음을 수행할 수 있습니다.

* [Experience Manager Assets Essentials에서 자산 및 폴더를 연결합니다](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Flink-to-aem.htm&amp;_LANG=enus)

* [Experience Manager Assets Essentials로 문서 보내기](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fsend-to-aem.htm&amp;_LANG=enus)

* [Experience Manager Assets Essentials에 연결된 자산 증명](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fproof-linked-asset-aem.htm)

* [Experience Manager Assets Essentials에서 연결된 자산을 보거나 다운로드합니다](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fview-download-asset.htm)
