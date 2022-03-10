---
title: 폴더 권한을 효과적으로 관리하는 방법
description: 효과적인 권한 관리를 위한 우수 사례
source-git-commit: fe716385939d18aa23d01dac5fe5f041541d2b31
workflow-type: tm+mt
source-wordcount: '398'
ht-degree: 0%

---

# 효과적인 권한 관리를 위한 우수 사례 {#best-practices-permissions-management}

관리자는 Assets Essentials 리포지토리의 폴더 권한 관리를 시작하기 전에 작업을 관리하면서 나중에 사용자와 관리자가 인프라를 직관적으로 사용하도록 하기 위해 구현할 수 있는 다양한 모범 사례를 제공합니다.

다음과 같은 작업 중에 다음 모범 사례를 통합할 수 있습니다.

* [Admin Console에서 사용자 그룹 만들기](#admin-console-best-practices)

* [Assets Essentials 저장소에서 폴더 구조 만들기](#folder-structure-assets-essentials)

* [Assets Essentials 저장소의 권한 관리](#folder-permissions)

## Admin Console {#admin-console-best-practices}

조직의 사용자 그룹을 기반으로 액세스 요구 사항을 식별합니다. 조직에 대한 사용자 그룹을 계획하고 만들고 만들고 사용자를 해당 사용자 그룹에 추가합니다. 개별 사용자가 아니라 사용자 그룹을 기반으로 폴더 권한을 관리하는 것이 더 쉽습니다.

## Assets Essentials 저장소의 폴더 구조 {#folder-structure-assets-essentials}

Assets Essentials 리포지토리에서 폴더 구조를 생성하려는 계획을 시작할 때 다음 사항을 고려하십시오.

* 향후 거버넌스: 관리자가 관리하는 폴더 및 [다른 사용자에게 소유자로 권한 위임](manage-permissions.md##manage-permissions-folders).

* 확장 가능: 폴더 구조는 조직의 향후 요구 사항을 준수해야 하며 쉽게 확장할 수 있어야 합니다.

* 크기: 폴더에는 너무 많은 자산이 없어야 합니다. 이로 인해 유용성 문제가 발생할 수 있으며 관리가 어려울 수 있습니다.

* 직관적인: 폴더 구조는 최종 사용자가 쉽게 찾아보고 직관적이어야 합니다. 사용자는 폴더 구조에서 새 자산을 업로드할 위치를 쉽게 식별할 수 있어야 합니다.

조직에 사용할 수 있는 폴더 구조 유형은 다양합니다. 다음은 일반적인 폴더 구조의 몇 가지 예입니다.

* 함수 및 분류 기반

   ![함수 및 분류](assets/function-categorization.png)

* 캠페인 기반

   ![캠페인 기반](assets/campaign-based.png)

* 오퍼 위치(또는 채널) 기반

   ![오퍼 위치 기반](assets/offer-location.png)


## 폴더 권한 {#folder-permissions}

조직에 대한 사용자 그룹을 만들고, 해당 사용자 그룹에 사용자를 추가하고, 조직의 요구 사항에 맞는 Assets Essentials 저장소에서 폴더 구조를 선택하고 만들면 조직의 폴더 권한 관리를 시작할 수 있습니다. 폴더 권한 관리를 시작할 때 다음 사항을 고려하십시오.

* 개별 사용자가 아닌 사용자 그룹에 대한 권한을 적용합니다. 따라서 사용 권한 구조가 간단하고 효율적입니다.

* 운영 효율성을 위해 가능한 한 간단한 권한 구조를 유지합니다.

* 거부 액세스 권한을 신중하게 사용하고 폴더 구조에 양의 권한(편집 가능, 보기 가능, 소유자)을 적용하려는 경우 사용합니다.

효율적이고 간단한 폴더 구조를 만드는 방법에 대한 예는 를 참조하십시오 [폴더에 대한 권한 관리](manage-permissions.md##manage-permissions-folders).

