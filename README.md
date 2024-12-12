<h1 align="center">Loan Eligibility Prediction </h1>
<p align="center">using <b>SAS Studio</b></p><br>
<div align="center">

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)  [![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)  [![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

</div>

# METADATA
<table style="width:100%">
  <thead>
    <tr>
      <th style="text-align:center; font-weight: bold; font-size:14px">Variable Name</th>
      <th style="text-align:center; font-weight: bold; font-size:14px">Description</th>
      <th style="text-align:center; font-weight: bold; font-size:14px">Sample Data</th>
      <th style="text-align:center; font-weight: bold; font-size:14px">Available in Data Set</th>
      <th style="text-align:center; font-weight: bold; font-size:14px">Variabel Type</th>
      <th style="text-align:center; font-weight: bold; font-size:14px">Data Type</th>
      <th style="text-align:center; font-weight: bold; font-size:14px">Length</th>
    </tr>
  </thead>
  <tbody>
  <tr>
    <td>SME_LOAN_ID_NO</td>
    <td>Loan reference number <br> (unique ID)</td>
    <td>TRAINING_DS, TESTING_DS</td>
    <td>Categorical</td>
    <td>Char</td>
    <td>8</td>
    <td>LP001002; LP001003; …</td>
  </tr>
  <tr>
    <td>GENDER</td>
    <td>Applicant gender <br> (Male or Female)</td>
    <td>TRAINING_DS, TESTING_DS</td>
    <td>Categorical</td>
    <td>Char</td>
    <td>6</td>
    <td>Male; Female</td>
  </tr>
  <tr>
    <td>MARITAL_STATUS</td>
    <td>Applicant marital status <br> (Married or not married)</td>
    <td>TRAINING_DS, TESTING_DS</td>
    <td>Categorical</td>
    <td>Char</td>
    <td>11</td>
    <td>Married; Not Married</td>
  </tr>
  <tr>
    <td>FAMILY_MEMBERS</td>
    <td>Numberof family members owned by applicant</td>
    <td>TRAINING_DS, TESTING_DS</td>
    <td>Categorical</td>
    <td>Char</td>
    <td>2</td>
    <td>0;1; 2; 3+</td>
  </tr>
  <tr>
    <td>QUALIFICATION</td>
    <td>Applicant qualification <br> (graduate or under graduate)</td>
    <td>TRAINING_DS, TESTING_DS</td>
    <td>Categorical</td>
    <td>Char</td>
    <td>14</td>
    <td>Graduate; Under Graduate</td>
  </tr>
  <tr>
    <td>EMPLOYMENT</td>
    <td>Applicant employment status <br> (yes or no)</td>
    <td>TRAINING_DS, TESTING_DS</td>
    <td>Categorical</td>
    <td>Char</td>
    <td>3</td>
    <td>Yes; No</td>
  </tr>
  <tr>
    <td>CANDIDATE_INCOME</td>
    <td>Applicant’s monthly salary/income</td>
    <td>TRAINING_DS, TESTING_DS</td>
    <td>Continuous</td>
    <td>Numeric</td>
    <td>8</td>
    <td>5849; 4583; …</td>
  </tr>
  <tr>
    <td>GUARANTEE_INCOME</td>
    <td>Earnings of both applicants</td>
    <td>TRAINING_DS, TESTING_DS</td>
    <td>Continuous</td>
    <td>Numeric</td>
    <td>8</td>
    <td>1508; 2358; …</td>
  </tr>
  <tr>
    <td>LOAN_AMOUNT</td>
    <td>Loan amount <br> (in thousands)</td>
    <td>TRAINING_DS, TESTING_DS</td>
    <td>Continuous</td>
    <td>Numeric</td>
    <td>8</td>
    <td>128; 66; …</td>
  </tr>
  <tr>
    <td>LOAN_DURATION</td>
    <td>The loan’s repayment period</td>
    <td>TRAINING_DS, TESTING_DS</td>
    <td>Categorical</td>
    <td>Numeric</td>
    <td>8</td>
    <td>360; 120; …</td>
  </tr>
  <tr>
    <td>LOAN_HISTORY</td>
    <td>Records of previous loans</td>
    <td>TRAINING_DS, TESTING_DS</td>
    <td>Categorical</td>
    <td>Numeric</td>
    <td>8</td>
    <td>0; 1</td>
  </tr>
  <tr>
    <td>LOAN_LOCATION</td>
    <td>The location of loan (city/village/town)</td>
    <td>TRAINING_DS, TESTING_DS</td>
    <td>Categorical</td>
    <td>Char</td>
    <td>7</td>
    <td>City; Village; Town</td>
  </tr>
  <tr>
    <td>LOAN_APPROVAL_STATUS</td>
    <td>Approval status of loan</td>
    <td>TESTING_DS</td>
    <td>Categorical</td>
    <td>Char</td>
    <td>1</td>
    <td>Y; N</td>
  </tr>
</tbody>
</table>
