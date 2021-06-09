<h2>Specifications of the DataSet :-</h2>

<h2>Continuous variables:-</h2>
    group_size: number of people covered by the policy<br>
    car_age: age of customer's car<br>
    risk_factor: 1 through 4 assessment of customer risk<br>
    age_oldest: age of oldest person covered by the policy<br>
    age_youngest: age of youngest person covered by the policy<br>
    duration_previous: years covered by previous issuer<br>
    cost: cost of quoted options<br>
<h2>Categorical variables:</h2>
    state: customer location<br>
    location: ID of customer location (more specific than state)<br>
    homeowner: yes or no<br>
    car_value: value of customer's car when new, expressed only as letters 'a' through 'i'<br>
    married_couple: yes or no<br>
    C_previous: what customer previous had for option C<br>
    A/B/C/D/E/F/G: coverage options<br>

<h2> Understanding Labels</h2>
<img src="https://storage.googleapis.com/kaggle-competitions/kaggle/3788/media/product_options.png">
A product is simply a vector with length 7 whose values are chosen from each of the options listed above. The cost of a product is a function of both the product options and customer characteristics.
