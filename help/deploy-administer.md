---
title: 사용자 배포 및 관리
description: 의 배포 및 사용자 관리와 같은 관리 사용 사례 [!DNL Assets Essentials].
role: Admin
exl-id: ef91126f-3aee-442b-b242-a6bf4034f3dc
source-git-commit: cbf75aaf05a0f3d798edf4d508325b28d9ca0dcb
workflow-type: tm+mt
source-wordcount: '1030'
ht-degree: 1%

---

# 배포 [!DNL Assets Essentials] 사용자를 추가하고 {#administer}

[!DNL Adobe Experience Manager Assets Essentials] 은 해당 고객에 대해 Adobe이 프로비저닝합니다. 프로비저닝의 일부로서, [!DNL Assets Essentials] 가 의 고객 조직에 추가됩니다. [!DNL Adobe Admin Console]. 또한 고객은 [!DNL Experience Manager Cloud Manager] 을 배포 도구 및 [!DNL Admin Console] 사용자 권한 관리 [!DNL Assets Essentials] 솔루션.

## Assets Essentials 자동 배포 {#automatic-deployment-assets-essentials}

Assets Essentials 솔루션이 프로비저닝되면 관리자는 Adobe에서 이메일을 받습니다. 이메일에 시작할 수 있는 시작 메시지와 링크가 포함되어 있습니다. 또한 Adobe은 Assets Essentials을 자동으로 배포하는 프로세스를 시작합니다. 배포 프로세스를 완료하는 데 1시간이 소요됩니다.

이메일의 링크에서에 액세스하여 로그인합니다. [Admin Console](https://adminconsole.adobe.com). 둘 이상의 조직 계정에 대한 관리자 액세스 권한이 있는 경우 상단 막대에서 적절한 조직을 선택하거나 전환기를 사용하여 해당 조직으로 전환합니다. 자동 배포 프로세스가 완료되면 [!DNL AEM Assets Essentials] 에 표시됩니다. [!DNL Admin Console].

![Assets Essentials 배포](assets/assets-essentials-deployment.png)

관리자는 Assets Essentials 솔루션을 성공적으로 배포한 후 다음 작업을 수행해야 합니다.

* [사용자 액세스 관리](#add-users-to-essentials) 조직 구성원에게 [!DNL Assets Essentials].
* 원할 경우, [서비스 상태 및 로그 보기](#view-logs).

>[!NOTE]
>
>Assets Essentials이 2022년 1월 6일 이전에 프로비저닝된 경우, [Cloud Manager의 배포 단계](#deploy-essentials) 조직 구성원의 사용자 액세스를 관리하기 전에


## 사용자 관리 {#add-users-to-essentials}

관리자는 액세스 권한이 있는 사용자를 관리합니다 [!DNL Assets Essentials]. 관리자는 [!DNL Adobe Admin Console] 사용자 액세스를 추가 또는 제거하려면 [!DNL Assets Essentials] 에는 다음과 같은 두 가지 유형의 사용자 액세스 권한이 있습니다.

* **[!DNL Assets Essentials]사용자** 전체 사용자 인터페이스에 액세스할 수 있습니다. 이러한 사용자는 디지털 자산을 업로드, 구성, 태그 지정 및 찾을 수 있습니다.
* **[!DNL Assets Essentials]소비자 사용자**: 에서 포함된 자산 선택 경험에 액세스할 수 있습니다. [!DNL Adobe Journey Optimizer] 이메일 템플릿 편집기. 자세한 내용은 [사용 [!DNL Assets Essentials] in [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).

in [!DNL Admin Console]과 같은 두 액세스 유형은 [!UICONTROL Product Profiles]. 두 프로필 중 하나에 조직 구성원을 추가하고 제거하려면 다음 단계를 수행합니다.

1. 액세스 [!DNL Admin Console] 조직의 경우 **[!UICONTROL Products]** 상단 막대에서 **[!UICONTROL AEM Assets Essentials]**&#x200B;를 클릭한 다음 [!DNL Assets Essentials] 환경. [!DNL Assets Essentials] 에는 일반 사용자와 소비자 사용자에 대한 액세스를 나타내는 두 개의 제품 프로필이 있습니다.

   ![두 가지 유형의 사용자를 위한 두 개의 프로필](assets/adminconsole-user-types.png)

   *그림: 두 개의 프로필을 사용하여 두 가지 유형의 사용자를 추가할 수 있습니다.*

1. 사용자를 그룹에 추가하려면 그룹을 클릭하고 **[!UICONTROL Add User]**&#x200B;를 클릭하고 사용자 세부 사항을 제공한 다음 를 클릭합니다. **[!UICONTROL Save]**. 사용자를 추가하면 사용자는 시작할 이메일 초대를 받습니다. 의 제품 프로필 설정에서 이메일 초대를 해제할 수 있습니다 [!DNL Admin Console].

   ![사용자를 [!DNL Assets Essentials]](assets/adminconsole-add-user.png)

   *그림: 사용자를 [!DNL Assets Essentials] 변환 전: [!DNL Admin Console].*

1. 그룹에서 사용자를 제거하려면 그룹을 클릭하고 기존 사용자를 선택한 다음 **[!UICONTROL Remove User]**.

>[!TIP]
>
>in [!DNL Admin Console], CSV 파일을 사용하여 사용자를 대량으로 관리할 수 있습니다. 자세한 내용은 [[!DNL Admin Console] 설명서](https://helpx.adobe.com/enterprise/using/accounts.html).

## 서비스 상태 및 액세스 로그 보기 {#view-logs}

프로비저닝 후 관리자 배포 [!DNL Assets Essentials] 한 번만 초기 배포 후 Adobe은 서비스 유지 관리 및 업데이트를 수행합니다. 관리자는 [!DNL Cloud Manager] 사용자 인터페이스를 사용하여 서비스 상태를 확인하고 최근 액세스 로그를 다운로드합니다.

1. 사용자가 문제를 보고할 때 [!DNL Assets Essentials] 에서 **[!UICONTROL Program Overview]** 인터페이스. 일반적인 솔루션 작업 중에 상태는 입니다 `Running`. If [!DNL Cloud Manager] 다른 상태를 표시하고 [!DNL Admin Console] 지원 섹션을 참조하십시오.

   ![상태 [!DNL Assets Essentials] in [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *그림: 의 일반 상태 [!DNL Assets Essentials] in [!DNL Cloud Manager] is `Running`.*

1. 최근 액세스 로그를 다운로드하려면 ![옵션 아이콘](assets/do-not-localize/options-ellipses-icon.png), 선택 **[!UICONTROL Download Logs]**, 그리고 화면의 지시를 따릅니다. 로그를 사용하여 HTTPS 액세스 요청을 감사할 수 있습니다.

   ![ 액세스 로그를 다운로드하는 옵션](assets/cloudmanager-download-logs.png)

   *그림: 액세스 로그를 다운로드하는 옵션입니다.*

## 배포 [!DNL Assets Essentials] {#deploy-essentials}

>[!NOTE]
>
>Assets Essentials이 2022년 1월 6일 이전에 프로비저닝된 경우에만 이러한 단계를 실행합니다.

프로비저닝 후 [!DNL Assets Essentials] 자격 부여 는 [!DNL Admin Console]. 사용자가 솔루션을 사용할 수 있으려면 먼저 조직 관리자가 솔루션을 배포해야 합니다. 관리자는 [!DNL Cloud Manager] 사용자 인터페이스. 초기 배포 후 Adobe은 서비스 유지 관리 및 업데이트를 수행합니다. 솔루션이 프로비저닝되면 관리자는 Adobe에서 이메일을 받습니다. 이메일에 시작할 수 있는 시작 메시지와 링크가 포함되어 있습니다. 배포하려면 다음 단계를 수행합니다.

1. 이메일의 링크에서에 액세스하여 로그인합니다. [Admin Console](https://adminconsole.adobe.com). 둘 이상의 조직 계정에 대한 관리자 액세스 권한이 있는 경우 상단 막대에서 적절한 조직을 선택하거나 전환기를 사용하여 해당 조직으로 전환합니다. 에 대한 제품 카드 [!DNL Assets Essentials] 에 표시됩니다. [!DNL Admin Console].

   ![[!DNL Assets Essentials] 카드 로그인 [!DNL Admin Console]](assets/essentials-in-admin-console.png)

   *그림: [!DNL Assets Essentials] 카드 로그인 [!DNL Admin Console].*

   >[!NOTE]
   >
   >다음을 볼 수 있습니다 **[!UICONTROL AEM Assets Essentials]** 대신 products 섹션의 카드 **[!UICONTROL AEM Assets Essentials - Cloud Manager]** 카드, Assets Essentials 배포이 이미 완료되었습니다. 나머지 단계를 건너뛸 수 있습니다.

1. 자신을 관리자로 `AEM Assets Essentials - Cloud Manager` 의 제품 프로필 [!DNL Admin Console]. 대신 조직의 다른 구성원을 추가하거나 두 명 이상의 관리자를 추가할 수 있습니다.

1. 클릭 ![아이콘 추가](assets/do-not-localize/add-icon.svg) to [!UICONTROL Select product profiles]를 선택한 다음 을 선택합니다. [!UICONTROL Deployment Manager - Assets Essentials] 로서의 **[!UICONTROL product profile]**. 이 단계에 추가된 사용자는에 액세스할 수 있는 Adobe에서 이메일을 받습니다 [!DNL Cloud Manager] 및 은(는) 배포를 수행할 수 있습니다.

   ![관리자를 추가하고 의 제품 프로필을 선택합니다 [!DNL Admin Console]](assets/adminconsole-user1.png)

   *그림: 관리자를 추가하고 의 제품 프로필을 선택합니다 [!DNL Admin Console].*

1. 에 액세스하려면 [!DNL Cloud Manager]에 액세스할 수 있는 이메일의 링크를 클릭합니다. [!DNL Cloud Manager]. 또는, [https://experience.adobe.com/#/cloud-manager/](https://experience.adobe.com/#/cloud-manager/) 브라우저에서

1. Cloud Manager 사용자 인터페이스에서 를 클릭합니다. **[!UICONTROL Add Program]** 오른쪽 위 모서리에서

1. 원하는 이름을 제공하고 이미지를 업로드합니다(이 이름은 [!DNL Cloud Manager])를 클릭한 다음 **[!UICONTROL Create]**. [!DNL Cloud Manager] 프로그램을 설정하는 데 몇 분 정도 걸립니다.

1. 프로그램이 준비되면 타일 위에 포인터를 놓고 ![환경 추가 아이콘](assets/do-not-localize/add-environment-icon.png).

1. 추가하려면 [!DNL Assets Essentials] 조직에 서비스를 제공한 다음 **[!UICONTROL Add Environment]**&#x200B;을 클릭하고 이름 및 배포 영역을 선택한 다음 **[!UICONTROL Save]**. 나중에 배포 영역을 변경할 수 없습니다. 의 배포 영역과 일치시키려고 합니다. [!DNL Assets Essentials] 사용할 다른 솔루션의 배포 영역과 함께 [!DNL Assets Essentials]. 일치하는 것은 디지털 자산에 대해 가능한 가장 빠른 네트워크 액세스 및 가능한 가장 낮은 지연을 보장하는 것입니다.

   ![에서 환경 추가 [!DNL Cloud Manager]](assets/cloudmanager-add-environment-for-essentials.png)

   *그림: 에서 환경 추가 [!DNL Cloud Manager] 사용을 시작하기 [!DNL Assets Essentials].*

1. 몇 분 후에 환경이 성공적으로 만들어지면 [!DNL Admin Console] 조직의 사용자를 [!DNL Assets Essentials] 솔루션. 클릭 ![옵션 아이콘](assets/do-not-localize/options-ellipses-icon.png) 을(를) 선택하고 을(를) 선택합니다. **[!UICONTROL Manage Access]** 선택 사항입니다.

   ![준비 환경 [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *그림: 의 환경 [!DNL Cloud Manager] 사용할 준비가 되었습니다.*

>[!MORELIKETHIS]
>
>* [[!DNL Admin Console] 도움말](https://helpx.adobe.com/kr/enterprise/using/admin-console.html)
>* [[!DNL Cloud Manager] 도움말](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=ko-KR)
>* [Adobe Journey Optimizer 설명서](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html)
>* [릴리스 노트](release-notes.md)
>* [사용 시작 [!DNL Assets Essentials]](get-started.md)

