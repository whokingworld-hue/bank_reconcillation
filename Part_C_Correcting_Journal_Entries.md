# Part C — Correcting Journal Entries (Template)

No Type A items could be computed because the underlying ledger and bank statement files were not found in the repository.

Use the following format for each Type A discrepancy after data is available:

Dr [Account Name] ........ ₹X,XXX  
    Cr [Account Name] .... ₹X,XXX  
(Narration: Being correction of [nature of Zoho error] identified during bank reconciliation for Q1 2026.)

## Common correction patterns

1. **Bank charge in statement but missing in Zoho**  
   Dr Bank Charges Expense  
   Cr Bank (HDFC)

2. **Bank interest/credit in statement but missing in Zoho**  
   Dr Bank (HDFC)  
   Cr Interest Income

3. **Duplicate payment posted in Zoho but only one in bank**  
   Dr Bank (HDFC)  
   Cr Relevant Expense / Vendor

4. **Wrong amount posted in Zoho**  
   Pass adjustment entry for difference amount only, with correct debit/credit orientation.
