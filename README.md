# cse308-offline-assignment-1-basics-of-object-oriented-programming-oop-solved
**TO GET THIS SOLUTION VISIT:** [CSE308 Offline Assignment # 1-Basics of Object Oriented Programming (OOP) Solved](https://www.ankitcodinghub.com/product/cse308-offline-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97072&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE308 Offline Assignment # 1-Basics of Object Oriented Programming (OOP) Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this assignment, you will implement a simple banking system using the basic concepts of Object Oriented Programming.

Accounts: In our banking system, there will be three types of accounts: Savings, Student, and Fixed deposit. For the sake of simplicity, assume an user can open one account only. You have to implement the following functionalities:

<ol>
<li>Create Account: After entering the system, users can request to open a new account with their name, account type, and initial deposit. A fixed deposit account must ensure the first deposit is at least 100,000$. After successful opening of the account, the user will be notified accordingly. If an account already exists against that name, an error message will be shown. Assume the names to be primary keys.</li>
<li>Deposit: An user can deposit any sum of money into an account, except for a fixed deposit account. The deposit amount must not be less than 50,000$ for the latter case.</li>
<li>Withdraw: Withdrawing is different across different account types:
<ol>
<li>(a) &nbsp;A student account cannot withdraw more than 10,000$ in one transaction.</li>
<li>(b) &nbsp;A fixed deposit account cannot withdraw if it has not reached a maturity period of one year.</li>
<li>(c) &nbsp;A savings account cannot withdraw if the withdrawal results in a deposit of less than 1,000$.</li>
</ol>
A transaction will be deemed invalid if the amount to withdraw exceeds the deposited sum.
</li>
<li>Request Loan: Any user can request a loan. The maximum allowable loan for savings, student, and fixed deposit accounts are 10,000$, 1,000$, 100,000$, respectively. All loans have a fixed 10% interest rate, which will be deducted after one year. The loans must be approved by an employee of the bank.</li>
<li>Query Deposit: An user can query the amount of deposit at any time.</li>
</ol>
Interest rates on deposit for savings, student, and fixed deposit accounts are 10%, 5%, 15%, re- spectively. All accounts except the student accounts will be deducted an amount of 500$ of service charge after one year.

1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Employees: There will be three types of employees in a banking system: Managing Director, Officer, and Cashier. There are different operations of employees based on their roles:

1. Lookup: Any employee can see the deposit sum of any user account.

2. Approve Loan: The Managing director and officer can approve loan requests of users.

3. Change Interest Rate: The managing director has the discretion to change the interest rates of different types of accounts.

4. See Internal Fund: The managing director can see the internal funds.

Maintain a bank class for handling the accounts and employees, and the internal fund. The initial fund is 1,000,000$. Assume the bank class will not be instantiated more than once, and the following employees will be created at the time of bank instantiation: 1 Managing Director (MD), 2 Officers (O1, O2), 5 Cashiers (C1, · · · , C5). Also maintain a clock variable to increment the year count of operation (assume all accounts are created at the same time).

Some test inputs and corresponding outputs are shown in Table 1.

</div>
</div>
<div class="layoutArea">
<div class="column">
Input

<pre>Create Alice Student 1000
Deposit 20000
Withdraw 12,000
Query
</pre>
<pre>Request 500
Close
Open S1
Approve Loan
Change Student 7.50
Lookup Alice
</pre>
<pre>See
Close
Open Alice
Query
Close
INC
Open Alice
Query
Close
</pre>
</div>
<div class="column">
Output

BankCreated;MD,S1,S2,C1,C2,C3,C4,C5 created Student account for Alice Created; initial balance 1,000$ 20,000$ deposited; current balance 21,000$

Invalid transaction; current balance 21,000$

Current balance 21,000

Loan request successful, sent for approval Transaction Closed for Alice

S1 active, there are loan approvals pending Loan for Alice approved

You don’t have permission for this operation Alice’s current balance 21,500$

You don’t have permission for this operation Operations for S1 closed

Welcome back, Alice

Current Balance 21,500$, loan 500$ Transaction Closed for Alice

1 year passed

Welcome back, Alice

Current balance, 22,525$, loan 500$ Transaction Closed for Alice

</div>
</div>
<div class="layoutArea">
<div class="column">
Table 1: A sample input for job-shop simulation

2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Your implementation must abide by the encapsulation, inheritance, and polymorphism proper- ties of OOP. Make the design choices accordingly.

</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
