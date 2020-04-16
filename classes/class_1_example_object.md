**Instance of CashRegister:**
mainRegisteratCoffeeShop

**Attributes**
* registerName: "Main Register"
* billsInRegister: { 1: 10, 5: 10, 10: 5, 20: 5, 50: 0, 100: 1}
* hasReceiptPaper: true
* coinsInRegister { 1: 5, 5: 5, 10: 5, 25: 10}

**Methods**
* calculateDenominationValue ("Main Register" has 10 $1 = bills so that denomination is worth $10.)
* countTotalCash (Adds up ($1*10)+($5*10)+($10*5)+($20*5)+($50*0)+($100*1)= $310)
* acceptPayment (receive one $10 from customer, changing key-value pair of 10: 5 in billsInRegister to 10: 6)
* returnChange (return $5 to customer, changing key-value pair of 5: 10 in billsInRegister to 5: 9 )
* printReceipt ($10 - $5 = $5 can be printed out because it is true the register hasReceiptPaper)
