---
    title: How to Define Tax Registers
    description: Tax registers are used to track and manage taxable profits and losses in accordance with Russian tax accounting principles. You can use the **Tax Register Card** window to define how tax registers calculate taxable profits and losses and record the results.

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
# Define Tax Registers
Tax registers are used to track and manage taxable profits and losses in accordance with Russian tax accounting principles. You can use the **Tax Register Card** window to define how tax registers calculate taxable profits and losses and record the results.  

## To define tax registers  

1.  Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Tax Register Card**, and then choose the related link.  
2.  On the **General** FastTab, enter the following information.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**No.**|Specifies the entry number that is assigned to the tax register.|  
    |**Description**|Enter a description for the tax register.|  
    |**Level**|Specifies the parent/child relationship between tax registers. Top-level parent tax registers should be **0**.|  
    |**Costing Method**|Select the inventory valuation costing method that is used for the tax register.|  
    |**G/L Corr. Analysis View Code**|Select the code of the general ledger correspondence analysis view that you want to use for the tax register.|  

3.  On the **Register Lines** FastTab, enter the following information.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**Line Code**|Enter a code to identify the tax register line.|  
    |**Account Type**|Select the account type of the tax register line. Options include **Correspondence** and **G/L Account**.|  
    |**Amount Type**|Select the amount type of the tax register line. Options include **Debit**, **Credit**, and **Net Change**.|  
    |**Account No.**|Enter the general ledger account number for the tax register line.|  
    |**Bal. Account No.**|Enter the general ledger balance account number for the tax register line. The calculated tax register line balance amount will be stored in this account.|  
    |**Dimensions Filters**|Specifies if a dimension filter has been entered for the tax register line. If a dimension filter has been entered, the value will be **Present**.|  
    |**G/L Corr. Dimensions Filters**|Specifies if a general ledger correspondence dimension filter has been entered for the tax register line. If a dimension filter has been entered, the value will be **Present**.|  

4.  On the **Template Line** FastTab, enter the following information.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**Line Code**|Enter a code to identify the tax register template line.|  
    |**Expression**|Enter a formula for the tax register template line.|  
    |**Term Line Code**|Enter the tax register line code that is used for the template line.|  
    |**Dimensions Filters**|Specifies if a dimension filter has been entered for the tax register template line. If a dimension filter has been entered, the value will be **Present**.|  
    |**G/L Corr. Dimensions Filters**|Specifies if a general ledger correspondence dimension filter has been entered for the tax register template line. If a dimension filter has been entered, the value will be **Present**.|  

5.  Choose the **Close** button to close the window and save your entries.  

## See Also  
 [Tax Accounting](tax-accounting.md)   
  [Tax Registers](tax-registers.md)   
 [Create Tax Registers](how-to-create-tax-registers.md)   
 [Tax Differences](tax-differences.md)
