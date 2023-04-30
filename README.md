Download Link: https://assignmentchef.com/product/solved-mfe409-homework-6-risk-management-and-regulation-after-the-2008-financial-crisis
<br>
<h2>  Risk management and regulation after the 2008 Financial Crisis</h2>

Each study group is assigned to a bank as follows and reponsible for summarizing their risk management policies. Your group number can be found in the attached list.

<table width="173">

 <tbody>

  <tr>

   <td width="53">Group</td>

   <td width="120">Bank</td>

  </tr>

  <tr>

   <td width="53">1</td>

   <td width="120">Goldman Sachs</td>

  </tr>

  <tr>

   <td width="53">2</td>

   <td width="120">UBS</td>

  </tr>

  <tr>

   <td width="53">3</td>

   <td width="120">JP Morgan Chase</td>

  </tr>

  <tr>

   <td width="53">4</td>

   <td width="120">Citigroup</td>

  </tr>

  <tr>

   <td width="53">5</td>

   <td width="120">Barclays Capital</td>

  </tr>

  <tr>

   <td width="53">6</td>

   <td width="120">Morgan Stanley</td>

  </tr>

  <tr>

   <td width="53">7</td>

   <td width="120">Deutsche Bank</td>

  </tr>

  <tr>

   <td width="53">8</td>

   <td width="120">Bank of America</td>

  </tr>

  <tr>

   <td width="53">9</td>

   <td width="120">BNP Paribas</td>

  </tr>

  <tr>

   <td width="53">10</td>

   <td width="120">Credit Suisse</td>

  </tr>

 </tbody>

</table>

Download their 2009 and most recent annual reports (10-K for US firms and

20-F or 6-K for foreign firms) from SEC’s website <a href="https://www.sec.gov/edgar/searchedgar/companysearch.html">(https://www.sec.gov/edgar/searchedgar/companysearch.htm </a>Write a short essay describing the approach of the bank is following for risk management. In particular, describe how it computes the various risk measures to respect the Basel regulations.

1

<h2>2         Bootstrapping a CDS curve</h2>

<ol>

 <li>Recover the hazard rate curve from slide 15 of the notes.</li>

 <li>Use this hazard rate curve to price a 6-year bond on the same companywhich pays 3% coupon every 6 month and has face value $100.</li>

</ol>

<strong>3         Historical vs bond-implied hazard rates</strong>

Explain the patterns you see in the table on slide 16 of the notes.

<h2>4          <em>Optional: </em>Dynamic credit model</h2>

Consider 8 categories: AAA, AA, BBB, BB, B, CCC and default. We are interested in constructing a stochastic dynamic model of rating and default in continuous time. For this we will use the information in slide 7 of the notes.

<ol>

 <li>Let us call <em>P</em>(<em>t</em>) the 8 × 8 matrix of transition probability after time <em>t</em>. This means that <em>P<sub>ij</sub></em>(<em>t</em>) is the probability of being in category <em>j </em>at date <em>t </em>if the firm is in category <em>i </em>at date 0.</li>

</ol>

(a) What is <em>P</em>(0)? (b) What is <em>P</em>(1)?

<ol start="2">

 <li>Just like we defined the hazard rate has the instantaneous probability ofdefault, we can consider instantaneous transition probability <em>λ<sub>ij </sub></em>such that <em>λ<sub>ij</sub>dt </em>is the probability of going from rating <em>i </em>to rating <em>j </em>during an interval <em>dt </em>if <em>i </em>6= <em>j</em>. When <em>i </em>= <em>j</em>, we define <em>λ<sub>ii </sub></em>as the opposite of the intensity of leaving state <em>i</em>: <em>λ<sub>ii </sub></em>= −<sup>P</sup><em><sub>j</sub></em><sub>6=<em>i </em></sub><em>λ<sub>ij</sub></em>. We can put all these in a matrix Λ. Express Λ as a function of <em>P </em>and its first derivative.</li>

 <li>Assuming that Λ is constant over time, derive an expression relating <em>P</em>(1) and Λ.</li>

 <li>Compute Λ for the values of slide 7.</li>

 <li>Use this matrix Λ to compute the probabilities of default at horizon 1, 2,3, 4, 5, 7, and 10 years given each initial rating.</li>

 <li>Compare your results to slide 6 of the notes. What can explain the similarities and differences?</li>

 <li>Use this model to price a 6-year bond on a BBB company which pays 3%coupon every 6 month and has face value $100. Assume that the risk-free interest rate is 0% and recovery is 60%</li>

 <li>Compute the 3, 5, and 10-year CDS spreads for the same company.</li>

</ol>

2