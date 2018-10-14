# primitive-anomaly-detection

A primitive anomaly detection system for credit card transactions.
You are provided with a .csv file which mimics a real-time credit card purchase feed. The transactions have the following format:
```AccountId, MerchantId, TransactionAmount```

Notice that sometimes there is data corruption, and a meaningless extra column might appear. 

Your goal is to flag up anomalous transactions in real-time for further inspection by an expert. You decided to approach this problem by quantifying how much an incoming transaction deviates from the typical transaction for the customer in question.
