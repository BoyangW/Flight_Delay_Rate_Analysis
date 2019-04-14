### Flight Delay Rate Association Rule Mining
<p>Website: https://boywei.georgetown.domains/Flight_Delay_Analysis/association.html</p>

<H4>Dataset</H4>
<ul>
  <li>cleaned_data.csv
    <ul>
      <li>Input file for associate rule.py and anotherpackage.py/li>
    </ul>
  </li>
</ul>

<H4>Python Code</H4>
<ul>
  <li>associate rule.py
    <ul>
      <li>Input cleaned_data.csv</li>
      <li>Python code using Apyori 1.1.1 for association rule mining</li>
    </ul>
  </li>
  <li>anotherpackage.py
    <ul>
      <li>Input cleaned_data.csv</li>
      <li>Python code using mlxtend for association rule mining</li>
    </ul>
  </li>
</ul>

<H4>Output</H4>
<ul>
  <li>arr_0.01.txt, arr_0.05.txt, arr_0.005.txt, dep_0.01.txt, dep_0.05.txt, dep_0.005.txt
    <ul>
      <li>Outcomes of association rules considering arrival delay and departure delay with min_support=0.01,0.05,0.005 using the Apyori 1.1.1 Python package</li>
    </ul>
  </li>
  <li>mlxtend_arr_5.csv, mlxtend_arr_6.csv, mlxtend_dep_5.csv, mlxtend_dep_6.csv
    <ul>
      <li>Outcomes of association rules and frequent itemsets by using mlxtend Python package. the 5 and 6 mean the length of the itemsets, arr/dep means the type of delay</li>
    </ul>
  </li>
</ul>
