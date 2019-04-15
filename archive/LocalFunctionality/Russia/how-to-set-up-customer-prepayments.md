---
    title: How to Set Up Customer Prepayments
    description: Prepayments are advance payments on sales orders that are received, invoiced, and posted before the final invoice is issued. For example, you may require a deposit before you manufacture and ship an item to a customer.

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
# Set Up Customer Prepayments
Prepayments are advance payments on sales orders that are received, invoiced, and posted before the final invoice is issued. For example, you may require a deposit before you manufacture and ship an item to a customer. Prepayments let you invoice and collect advance payments from customers and post the payments against the correct invoices and accounts.  

## To set up customer prepayments  

1.  Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales & Receivables Setup**, and then choose the related link.  
2.  On the **Numbering** FastTab, verify that the number series for the **Posted Prepmt. Inv. Nos.** is the same as the **Posted Invoice Nos.**. Also verify that the number series for the **Posted Prepmt. Cr. Memo Nos.** is the same as the **Posted Credit Memo Nos.**.  
3.  On the **Prepayment** FastTab, enter the following information.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**Use Prepayment Account**|Select to post prepayments using the subaccount specified in the **Prepayment Account** field in the **Customer Posting Groups** window.|  
    |**Create Prepayment Invoice**|Select to create an invoice for the prepayment. If this field is not selected, an invoice for the prepayment will not be created.|  
    |**Posted Prepayment Nos.**|Enter the code of the number series that you want to use for prepayment invoices.|  
    |**Posted PD Doc. Nos.**|Enter the code of the number series that you want to use for prepayment documents.|  
    |**PD Doc. Nos. Type**|Select if you want to use a number series or symbol to identify prepayment documents.|  
    |**Symbol for PD Doc.**|Enter a symbol to be printed on prepayment documents.|  
    |**PD Gains Condition Dim Value**|Enter the code for the dimension that is used to generate conditional prepayment gains.|  
    |**PD Losses Condition Dim Value**|Enter the code for the dimension that is used to generate conditional prepayment losses.|  
    |**PD Gains Kind Dim Value**|Enter the code for the dimension that is used to generate payment in kind prepayment gains.|  
    |**PD Losses Kind Dim Value**|Enter the code for the dimension that is used to generate payment in kind prepayment gains.|  

4.  Open the **Customer Posting Groups** window.  
5.  In the **Prepayment Account** field, specify the general ledger accounts that you want to use for posting customer prepayments.  
6.  Choose the **Close** button to close the window and save your entries.  

You can now invoice and collect advance payments from customers and post the payments to the correct invoices and accounts.  

## See Also  
[Invoicing Prepayments](../../finance-invoice-prepayments.md)  
[Walkthrough: Setting Up and Invoicing Sales Prepayments](../../walkthrough-setting-up-and-invoicing-sales-prepayments.md)
