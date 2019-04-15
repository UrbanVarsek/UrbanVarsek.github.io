---
    title: How to Set Up Future Expenses in a Depreciation Book
    description: To depreciate a future expense, you have to set up future period expenses in a depreciation book.

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
# Set Up Future Expenses in a Depreciation Book
To depreciate a future expense, you have to set up future period expenses in a depreciation book.  

## To set up future expenses in a depreciation book  

1.  Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Depreciation Books**, and then choose the related link.  
2.  On the **General** FastTab, fill in the fields as described in the following table.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**Code**|Specifies the code for the depreciation book.|  
    |**Description**|Specifies the description of the depreciation book.|  
    |**Default Final Rounding Amount**|Specifies the final rounding amount that will be used as the default for the depreciation book.|  
    |**Default Ending Book Value**|Specifies the ending book value that will be used as the default for the depreciation book.|  
    |**Disposal Calculation Method**|Specifies the disposal calculation method that is associated with the depreciation book. Disposal calculation methods include **Net** or **Gross**.|  
    |**Subtract Disc. in Purch. Inv.**|Specifies if discounts will be subtracted from the purchase invoice.|  
    |**Allow Correction of Disposal**|Specifies if disposals can be corrected.|  
    |**Allow Changes in Depr. Fields**|Specifies if changes can be made in the depreciation fields.|  
    |**VAT on Net Disposal Entries**|Specifies if VAT will be calculated on net disposal entries.|  
    |**Posting Book Type**|Specifies the posting book type of the depreciation book. Book types include **Accounting**, **Tax Accounting**, and **Analytical**.|  
    |**Currency Code**|Specifies the currency code that is associated with the depreciation book.|  
    |**Allow Identical Document No.**|Specifies if an identical document number can be used.|  
    |**Allow Depreciation**|Specifies if depreciations are allowed.|  
    |**Allow Indexation**|Specifies if indexation is allowed.|  
    |**Allow Depr. Below Zero**|Specifies if depreciation below zero is allowed.|  
    |**Allow more than 360/365 Days**|Specifies if depreciation is allowed for more than 360/365 days.|  
    |**Use FA Ledger Check**|Specifies if fixed asset ledger checks are used.|  
    |**Use Rounding in Periodic Depr.**|Specifies if rounding is used in periodic depreciation calculations.|  
    |**Use Same FA+G/L Posting Date**|Specifies if the same fixed asset general ledger posting date is used.|  
    |**Fiscal Year 365 Days**|Specifies if the fiscal year equals 365 days.|  
    |**Mark Errors as Corrections**|Specifies if errors are marked as corrections.|  
    |**Control FA Acquis.Cost**|Specifies if fixed asset acquisition costs are controlled.|  

3.  On the **Integration** FastTab, select all options.  
4.  Choose the **FA Journal Setup** action.  
5.  In the **FA Journal Setup window**, fill in the **Gen. Jnl. Template Name** and **Gen. Jnl. Batch Name** fields.  
6.  Choose the **OK** button.  
7.  Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA Setup**, and then choose the related link.  
8.  In the **Fixed Asset Setup** window, on the **General** FastTab, fill in the **Future Depr. Book** field and then choose the **OK** button.  
9. Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Chart of Accounts**, and then choose the related link.  
10. Open the relevant account, and in the **G/L Account Card** window, on the **Posting** FastTab, fill in the **Gen. Prod. Posting Group** and the **VAT Prod. Posting Group** fields, and then choose the **OK** button.  
11. Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA Posting Groups**, and then choose the related link.  
12. In the **FA Posting Groups** window, enter information in the required fields.  
13. Choose the **OK** button.  

## See Also  
 [Fixed Assets](../../fa-manage.md)     
 [Future Expenses (Deferrals)](future-expenses-deferrals-.md)   
 [Create Future Expense Journals](how-to-create-future-expense-journals.md)
