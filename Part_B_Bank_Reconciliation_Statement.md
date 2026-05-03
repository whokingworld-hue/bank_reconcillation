 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a/Part_B_Bank_Reconciliation_Statement.md b/Part_B_Bank_Reconciliation_Statement.md
new file mode 100644
index 0000000000000000000000000000000000000000..381301d11e0d69688ac005b90d8b85cccc75c90e
--- /dev/null
+++ b/Part_B_Bank_Reconciliation_Statement.md
@@ -0,0 +1,24 @@
+# Part B — Bank Reconciliation Statement (Provisional)
+
+**Entity:** Arka Tea Traders Pvt Ltd  
+**Period:** 01/01/2026 to 31/03/2026  
+**Prepared on:** 03/05/2026
+
+> **Important limitation:** The required source files (`Arka_Tea_Traders_Zoho_Ledger.csv` and `Arka_Tea_Traders_HDFC_Statement.pdf`) were not available in the repository, so this BRS is a structural template only.
+
+## Standard BRS format (to be populated after source upload)
+
+| Particulars | Amount (₹) |
+|---|---:|
+| Closing balance as per Zoho books (31/03/2026) | TBD |
+| Add: Cheques issued but not yet presented | TBD |
+| Add: Bank credits not yet recorded in Zoho | TBD |
+| Less: Deposits in transit not yet credited by bank | TBD |
+| Less: Bank debits not yet recorded in Zoho | TBD |
+| Add/Less: Errors in Zoho identified and corrected | TBD |
+| Add/Less: Prior-period/opening balance adjustments | TBD |
+| **Closing balance as per HDFC bank statement (31/03/2026)** | **TBD** |
+
+## Notes
+1. Opening balance difference is expected to be the largest reconciling item per assignment hint and should be classified as Type D unless evidence indicates a current-period posting error.
+2. Timing differences (Type C) should not be passed via journal entries.
 
EOF
)
