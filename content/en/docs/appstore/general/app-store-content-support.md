---
title: "Marketplace Content Support"
url: /appstore/general/app-store-content-support/
category: "General Info"
weight: 4
tags: ["marketplace", "support", "platform support", "community support", "deprecated"]
description: "Describes the various levels of support available for using Marketplace content in your Mendix apps."
aliases:
    - /community/app-store-content-support/
    - /developerportal/app-store/app-store-content-support/
    - /community/app-store-content-support.html
    - /developerportal/app-store/app-store-content-support.html
#If moving or renaming this doc file, implement a temporary redirect and let the respective team know they should update the URL in the product. See Mapping to Products for more details.
---

## 1 Content Support Categories {#category}

Support for Marketplace content is determined by the content support category and the service level agreement (SLA) the user possesses. We distinguish the following content support categories:

| Category | Description |
| --- | --- |
| **Platform** | Mendix supports all the content in this category as-is when you are equipped with an SLA (**Platform**, **Standard**, or **Premium**) with Mendix. Content in this category is proactively incorporated into Mendix R&D test cycles as part of our platform release management. Please note that this category replaces the former **Extended** category, which has been deprecated. |
| **Deprecated** | The content in this category is considered end-of-life and will be dropped to the **Community support** status in the next major release of Mendix. Content is provided as-is by Mendix R&D, and support depends on the severity of the reported issue and the effort required to resolve it. |
| **Community** | Content is provided as-is by members of the Mendix community, and support depends on the availability and effort of the owner. | 
| **Partner** | The content in this category is provided and supported by a partner. The partner supports this content as-is when you are equipped with an SLA with the partner. For more information, see [Mendix Component Partner Program](/appstore/creating-content/partner-program/). | 
| **Siemens** | The content in this category is provided and supported by the Siemens team. Siemens supports this content as-is when you are equipped with an SLA with Siemens. | 

## 2 Feedback Process Details

We are always curious about and grateful for your feedback. The way you communicate your feedback to us depends on the support category of the content.

### 2.1 Platform Category

The applicable level of service for Mendix-supported Marketplace content is equal to the Mendix SLA you have acquired. In other words, the same SLA conditions apply to support on Marketplace content.

This means that equal response and resolve times are applicable, and the standard support process using the [Mendix Support Portal](https://support.mendix.com) has to be followed.

{{% alert color="warning" %}}
Content in this support category is supported as-is. When changing the content, the module will no longer be Platform-supported.
{{% /alert %}}

### 2.2 Deprecated Category {#deprecated}

We will move Platform-supported content into this category when we consider the content end-of-life. We factor in popularity, the availability of improved alternative(s), and industry standards when deciding on this.

Support for content in this category is limited and is decided by Mendix on a case-by-case basis. You can still follow the standard support process using the [Mendix Support Portal](https://support.mendix.com). However, the Mendix SLA no longer applies. 

### 2.3 Community Category {#community-category}

Support on content in this category is up to the user or organization providing the content. We recommend contacting the owner of the content in case of questions or issues via the following methods:

* Open an issue on the GitHub repository associated with the content (for details on GitHub issues, see [Mastering Issues](https://guides.github.com/features/issues/))
* Contact the owner of the content via the contact details available on the Marketplace component's detail pages
* Ask a question on the [Mendix Forum](https://mxforum.mendix.com/)
* Contribute 

The level of support depends on the availability and effort of the developer and/or the Mendix community.

### 2.4 Partner Category

Partner-supported content is created and maintained by partners as part of the [Mendix Component Partner program](/appstore/creating-content/partner-program/). Partners in the program commit to providing support to paying customers under an SLA (meaning, under terms specified by the partner). Customers can rely on this SLA for support from the partner if something goes wrong. A partner-supported Marketplace [component details page](/appstore/general/app-store-overview/#details) contains a reference to the partner's support portal or the partner's support contact email.

## 3 Feedback Process Summary

### 3.1 Mendix-Supplied Content

| Support Category  | Standard/Premium SLA | Platform SLA | No SLA | Notes |
| --- | --- | --- | --- | --- |
| **Platform** | [Mendix Support](https://support.mendix.com/)   | [Mendix Support](https://support.mendix.com/) | Mendix community supports | Mendix supports all the content in this category as-is when you are equipped with a Mendix SLA (Platform, Standard, or Premium). Content in this category is proactively incorporated into Mendix R&D test cycles as part of our platform release management. This category replaces the former Extended category, which has been deprecated. |
| **Deprecated** | [Mendix Support (limited)](https://support.mendix.com/) (for more information, see the [Deprecated Support Category](#deprecated) section above) | [Mendix Support (limited)](https://support.mendix.com/) (for more information, see the [Deprecated Support Category](#deprecated) section above) | Mendix community supports | Content in this category is considered end-of-life and will be dropped to the Community support category in the next major Mendix release. Content is provided as-is by Mendix R&D, and support depends on the severity of the reported issue and the effort required to resolve it. |
| **Community** | Mendix community supports | Mendix community supports | Mendix community supports | Content is provided as-is by members of the Mendix community, and support depends on the availability and effort of the owner. |

### 3.2 Community-Supplied Content

| Support Category | Supplied by Individual Developer | Supplied by Partner Organization | Notes |
| --- | --- | --- | --- |
| **Community** | Mendix community supports | Options: No support from partner, or Mendix community supports | Content is provided as-is by members of the Mendix community, and support depends on the availability and effort of the owner. |
| **Partner**  | N/A | Partner supports premium customers (allowed after Mendix Component Partner agreement is signed) | Content in this category is provided and supported by a Mendix partner. The partner supports this content as-is when you are equipped with an SLA with the partner. For more information, see [Mendix Component Partner Program](/appstore/creating-content/partner-program/). |

### 3.3 Siemens-Supplied Content

| Support Category | Supplied by Individual Developer | Supplied by Segment Team or Other Org Level | Notes |
| --- | --- | --- | --- |
| **Siemens** | N/A  | Siemens supports. | Content in this category is provided and supported by the Siemens team. Siemens supports this content as-is when you are equipped with an SLA with Siemens. |
| **Community** | Mendix community supports | Options: No support from partner, or Mendix community supports | Content is provided as-is by members of the Mendix community, and support depends on the availability and effort of the owner. |

## 4 Read More

* [Marketplace Overview](/appstore/general/app-store-overview/)
* [How to Share Marketplace Content](/appstore/general/share-app-store-content/)
* [How to Use Marketplace Content in Studio Pro](/appstore/general/app-store-content/)
