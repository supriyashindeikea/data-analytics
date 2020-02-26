# Data Analysis - Livecode

Let's explore the **Titanic disaster** data set.

Here are some interesting points to explore:

0. Let’s get familiar with the dataset (import, head, describe, read column name description…)
1. Let’s remove the cabin from the dataset because we don’t have enough data about the cabin number (Cleaning a dataset)
2. Find-out if first class tickets increased your chances of survival.
   Here it’s a simple comparaison between the rate of survival of the passenger by ticket type
3. Find-out if children and women were saved
   Here compare the survival rate of [‘Men’, ‘Children’, ‘Women’]

**Optional**

4. Find-out if it was harder for bigger families to survive?
   Here you create a new column in your dataframe for the family size of the passenger
5. Passengers with distingused title may be preferred during the evacuation ?
   With some string manipulation create a new column for each user with their title

-----


You can import the data set from this URL:

[https://github.com/lewagon/python-beginners/blob/livecode-data-analysis/03-Data-Analysis/data/titanic.csv](https://github.com/lewagon/python-beginners/blob/livecode-data-analysis/03-Data-Analysis/data/titanic.csv)

<table>
<tbody>
<tr><th><b>Variable</b></th><th><b>Definition</b></th><th><b>Key</b></th></tr>
<tr>
<td>survival</td>
<td>Survival</td>
<td>0 = No, 1 = Yes</td>
</tr>
<tr>
<td>pclass</td>
<td>Ticket class</td>
<td>1 = 1st, 2 = 2nd, 3 = 3rd</td>
</tr>
<tr>
<td>sex</td>
<td>Sex</td>
<td></td>
</tr>
<tr>
<td>Age</td>
<td>Age in years</td>
<td></td>
</tr>
<tr>
<td>sibsp</td>
<td># of siblings / spouses aboard the Titanic</td>
<td></td>
</tr>
<tr>
<td>parch</td>
<td># of parents / children aboard the Titanic</td>
<td></td>
</tr>
<tr>
<td>ticket</td>
<td>Ticket number</td>
<td></td>
</tr>
<tr>
<td>fare</td>
<td>Passenger fare</td>
<td></td>
</tr>
<tr>
<td>cabin</td>
<td>Cabin number</td>
<td></td>
</tr>
<tr>
<td>embarked</td>
<td>Port of Embarkation</td>
<td>C = Cherbourg, Q = Queenstown, S = Southampton</td>
</tr>
</tbody>
</table>

## Solution

Please do not peek _before_ the livecode session!

<details><summary markdown='span'>View solution
</summary>

  <a href="https://github.com/lewagon/python-beginners-solutions/blob/master/03-Data-Analysis/livecode_solution.ipynb">Titanic disaster: Solution notebook<a>
</details>
