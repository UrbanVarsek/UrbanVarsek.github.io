---
    title: How to Calculate Assessed Tax
    description: The assessed tax feature enables you to calculate the assessed tax for fixed assets. The assessed tax is based on the information provided in the **Fixed Asset Setup** window.

    services: project-madeira 
    documentationcenter: ''
    author: SorenGP

    ms.service: dynamics365-financials
    ms.topic: article
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 07/01/2017
    ms.author: sgroespe

---
# Calculate Assessed Tax
The assessed tax feature enables you to calculate the assessed tax for fixed assets. The assessed tax is based on the information provided in the **Fixed Asset Setup** window. You can also export the results of the calculated tax as a Microsoft Office Excel template.  

## To calculate assessed tax  

1.  Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Assessed Tax Allowances**, and then choose the related link.  
2.  In the **Assessed Tax Allowances** window, fill in the fields as described in the following table.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**Code**|Specifies the code for the assessed tax that is associated with the fixed asset.|  
    |**Name**|Specifies the name of the assessed tax code.|  

3.  Choose the **OK** button.  
4.  Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Assessed Tax Codes**, and then choose the related link.  
5.  In the **Assessed Tax Codes** window, fill in the fields as described in the following table.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**Code**|Specifies a code for an assessed tax allowance.|  
    |**Description**|Specifies a description for the assessed tax code.|  
    |**Region Code**|Specifies a two-character region code that is used together with the Tax Authority No. field to determine the OKATO code.|  
    |**Rate %**|Specifies the tax rate for the assessed tax. If there are any tax allowances that reduce the tax rate, they must be included in the rate percentage.|  
    |**Dec. Rate Tax Allowance Code**|Specifies a code for the assessed tax allowance code that reduces the calculated assessed tax amount according to the tax allowances directory. This code is defined in the **Assessed Tax Allowance** table.|  
    |**Dec. Amount Tax Allowance Code**|Specifies the amount of an assessed tax allowance.|  
    |**Decreasing Amount**|Specifies the value to be used in the assessed tax calculation if there is a tax allowance that reduces assessed taxes.|  
    |**Exemption Tax Allowance**|Specifies a code for an assessed tax allowance exemption. This code is defined in the **Assessed Tax Allowance** table.|  
    |**Decreasing Amount Type**|Specifies whether the decreasing amount value is a percentage or an amount.|  

6.  Choose the **Close** button.  
7.  Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **OKATO Codes**, and then choose the related link.  
8.  In the **OKATO Codes** window, fill in the **Region Code** and the **Tax Authority No.** fields, and then choose the **OK** button.  
9. Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Fixed Assets**, and then choose the related link.  
10. On the **Assessed Tax** FastTab, fill in the fields as described in the following table.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**Assessed Tax Code**|Specifies the assessed tax code that is associated with the fixed asset.|  
    |**Property Type**|Specifies the property type of the fixed the fixed asset. Property types include: **Immovable UGSS Property**, **Immovable Distributed Property**, **Other Property**, and **Special Economic Zone Property**.|  
    |**Book Value per Share**|Specifies the book value of the fixed asset, per share.|  
    |**OKATO Code**|Specifies the region where the current fixed asset is situated.|  
    |**Tax Amount Paid Abroad**|Specifies the amount of tax that was paid abroad for the fixed asset.|  

11. Choose the **OK** button.  
12. To print the assessed tax declaration, you have to first import the declaration template. In the **Fixed Asset Setup** window, select the template name from the **Templates** FastTab.  
13. Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Calculate Assessed Tax**, and then choose the related link.  
14. In the **Calculate Assessed Tax** window, fill in the **Tax Authority No.**, **Year**, and the **Reporting Period** fields.  
15. Choose the **OK** button.  

## See Also  
 [Fixed Assets](../../fa-manage.md)  
 [Setting Up Fixed Assets](../../fa-setup.md)
