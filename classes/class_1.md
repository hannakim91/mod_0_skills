**Class:**
CashRegister

**Attributes**
* registerName (string)
* billsInRegister (hash of keys (bill type) and values (how many of each bill))
* hasReceiptPaper (boolean)
* coinsInRegister (hash of keys (coin type) and values (how many of each coin))

**Methods**
* calculateDenominationValue (multiply each key by its value in billsInRegister to return value of that denomination)
* countTotalCash (multiplies each key by its value in billsInRegister and adds each total)
* acceptPayment (modifies billsInRegister and consequently modifies totalCash)
* returnChange (modifies billsInRegister and consequently modifies totalCash)
* printReceipt (if hasReceiptPaper is true, register can print out a receipt using values of acceptPayment and returnChange)
