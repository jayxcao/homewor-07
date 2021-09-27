# homework-07


<br>

> **How can you isolate (or group) the transactions of each cardholder?**
    
<br>
Using 3 tables, transaction, card_holder and credit_card I am able to find the person behind each credit card he/she owns and the transaction pertaining to them. Please refer to the SQL file for actual queries.



<br>

> **Count the transactions that are less than $2.00 per cardholder.**
    
<br>

Using 3 tables, transaction, card_holder and credit_card I am able to find the person behind each credit card he/she owns and the transaction pertaining to them. By putting a where clause in the transaction table I am able to limit the amount values to less than $2. Please refer to the SQL file for actual queries.


<br>

> **Is there any evidence to suggest that a credit card has been hacked? Explain your rationale.**
    
<br>

Negative, there is not enough information to lead to plausible conclusion that a credit card has been hacked. 1. After doing a check across the hours that hacking has occurred across all the credit cards and found that there are such evidence where the cards are debited less than $2 at a certain time of the day. 

check the merchant themselves for the value.

<br>

> **What are the top 100 highest transactions made between 7:00 am and 9:00 am?**

<br>

> **Do you see any anomalous transactions that could be fraudulent?**

<br>

<br>

> **Is there a higher number of fraudulent transactions made during this time frame versus the rest of the day?**

<br>

<br>

> **If you answered yes to the previous question, explain why you think there might be fraudulent transactions during this time frame.**

<br>