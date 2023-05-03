Download Link: https://assignmentchef.com/product/solved-cs3810-assignment3-queries
<br>
Run the given <a href="https://drive.google.com/file/d/1XkUWj4dSauPrufThBf6HWJ4Fja0x3AET/view?usp=sharing">ipps.sql</a> file to build the IPPS database from Database Assignment 02.  For this second part of the IPPS assignment you are asked to use the provided database schema.  Use the LOAD DATA commands (embedded in the SQL file) to populate your tables from the following CSV files that you will have to download:

<ul>

 <li><a href="https://drive.google.com/file/d/1-jaUL308hPiCGdAHwlosyrTtNIq-5oY-/view?usp=sharing">csv</a></li>

 <li><a href="https://drive.google.com/file/d/1U1CQkV5lWvIR4LvLWw_Q6gf5EPcx4H87/view?usp=sharing">csv</a></li>

 <li><a href="https://drive.google.com/file/d/1Sy9wNvXMNL705EiKJIIqRG9T5BAChHi9/view?usp=sharing">csv</a></li>

 <li><a href="https://drive.google.com/file/d/17z2W_M5yD65I5oNGe8MgopeWHb3pgII7/view?usp=sharing">csv</a></li>

</ul>

Your task in this assignment is to answer the following queries using SQL.  Write your answers to all queries updating the ipps.sql file.  That’s the file you are expected to submit through Blackboard.

How you should interpret the following fields in ChargesAndPayments:

<ul>

 <li>totalDischarges refers to “the <u>number of discharges</u> billed by the provider for inpatient hospital services,”</li>

 <li>avgCoveredCharges refers to “the provider’s <u>average</u> charge for services covered by Medicare for <u>all</u> discharges in the DRG,”</li>

 <li>avgTotalPayments refers to “the <u>average</u> charge for services by the provider for the correspondent DRG,”</li>

 <li>avgMedicarePayments refers to “the <u>average</u> of Medicare payments to the provider for the DRG.”</li>

</ul>

<ol>

 <li>a) List all diagnostic names in alphabetical order.</li>

 <li>b) List the names and correspondent states (including Washington D.C.) of all of the providers in alphabetical order (state first, provider name next, no repetition).</li>

 <li>c) List the total number of providers.</li>

 <li>d) List the total number of providers per state (including Washington D.C.) in alphabetical order (also printing out the state).</li>

 <li>e) List the total number of hospital referral regions (HRR).</li>

 <li>f) List the total number of HRRs per state (also printing out the state).</li>

 <li>g) List all of the providers in the state of Pennsylvania in alphabetical order.</li>

 <li>h) List the top 10 providers (with their correspondent state) that charged (as described in avgTotalPayments) the most for the diagnose with code 308. Output should display the provider, their state, and the average charged amount in descending order.</li>

 <li>i) List the average charges (as described in avgTotalPayments) of all providers per state for the clinical condition with code 308. Output should display the state and the average charged amount per state in descending order (of the charged amount) using only two decimals.</li>

 <li>j) Which provider and clinical condition pair had the highest difference between the amount charged (as described in avgTotalPayments) and the amount covered by Medicare (as described in avgMedicarePayments)?</li>

</ol>

<h1></h1>

<strong> </strong>