

```python
#Dependencies
import pandas as pd
```


```python
#import csv
data = pd.read_csv("/Users/apetek/Desktop/Github/pandas-challenge/Resources/purchase_data.csv")
data
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Purchase ID</th>
      <th>SN</th>
      <th>Age</th>
      <th>Gender</th>
      <th>Item ID</th>
      <th>Item Name</th>
      <th>Price</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>0</td>
      <td>Lisim78</td>
      <td>20</td>
      <td>Male</td>
      <td>108</td>
      <td>Extraction, Quickblade Of Trembling Hands</td>
      <td>3.53</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1</td>
      <td>Lisovynya38</td>
      <td>40</td>
      <td>Male</td>
      <td>143</td>
      <td>Frenzied Scimitar</td>
      <td>1.56</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2</td>
      <td>Ithergue48</td>
      <td>24</td>
      <td>Male</td>
      <td>92</td>
      <td>Final Critic</td>
      <td>4.88</td>
    </tr>
    <tr>
      <th>3</th>
      <td>3</td>
      <td>Chamassasya86</td>
      <td>24</td>
      <td>Male</td>
      <td>100</td>
      <td>Blindscythe</td>
      <td>3.27</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4</td>
      <td>Iskosia90</td>
      <td>23</td>
      <td>Male</td>
      <td>131</td>
      <td>Fury</td>
      <td>1.44</td>
    </tr>
    <tr>
      <th>5</th>
      <td>5</td>
      <td>Yalae81</td>
      <td>22</td>
      <td>Male</td>
      <td>81</td>
      <td>Dreamkiss</td>
      <td>3.61</td>
    </tr>
    <tr>
      <th>6</th>
      <td>6</td>
      <td>Itheria73</td>
      <td>36</td>
      <td>Male</td>
      <td>169</td>
      <td>Interrogator, Blood Blade of the Queen</td>
      <td>2.18</td>
    </tr>
    <tr>
      <th>7</th>
      <td>7</td>
      <td>Iskjaskst81</td>
      <td>20</td>
      <td>Male</td>
      <td>162</td>
      <td>Abyssal Shard</td>
      <td>2.67</td>
    </tr>
    <tr>
      <th>8</th>
      <td>8</td>
      <td>Undjask33</td>
      <td>22</td>
      <td>Male</td>
      <td>21</td>
      <td>Souleater</td>
      <td>1.10</td>
    </tr>
    <tr>
      <th>9</th>
      <td>9</td>
      <td>Chanosian48</td>
      <td>35</td>
      <td>Other / Non-Disclosed</td>
      <td>136</td>
      <td>Ghastly Adamantite Protector</td>
      <td>3.58</td>
    </tr>
    <tr>
      <th>10</th>
      <td>10</td>
      <td>Inguron55</td>
      <td>23</td>
      <td>Male</td>
      <td>95</td>
      <td>Singed Onyx Warscythe</td>
      <td>4.74</td>
    </tr>
    <tr>
      <th>11</th>
      <td>11</td>
      <td>Haisrisuir60</td>
      <td>23</td>
      <td>Male</td>
      <td>162</td>
      <td>Abyssal Shard</td>
      <td>2.67</td>
    </tr>
    <tr>
      <th>12</th>
      <td>12</td>
      <td>Saelaephos52</td>
      <td>21</td>
      <td>Male</td>
      <td>116</td>
      <td>Renewed Skeletal Katana</td>
      <td>4.18</td>
    </tr>
    <tr>
      <th>13</th>
      <td>13</td>
      <td>Assjaskan73</td>
      <td>22</td>
      <td>Male</td>
      <td>4</td>
      <td>Bloodlord's Fetish</td>
      <td>1.70</td>
    </tr>
    <tr>
      <th>14</th>
      <td>14</td>
      <td>Saesrideu94</td>
      <td>35</td>
      <td>Male</td>
      <td>165</td>
      <td>Bone Crushing Silver Skewer</td>
      <td>4.86</td>
    </tr>
    <tr>
      <th>15</th>
      <td>15</td>
      <td>Lisassa64</td>
      <td>21</td>
      <td>Female</td>
      <td>98</td>
      <td>Deadline, Voice Of Subtlety</td>
      <td>2.89</td>
    </tr>
    <tr>
      <th>16</th>
      <td>16</td>
      <td>Lisirra25</td>
      <td>20</td>
      <td>Male</td>
      <td>40</td>
      <td>Second Chance</td>
      <td>2.52</td>
    </tr>
    <tr>
      <th>17</th>
      <td>17</td>
      <td>Zontibe81</td>
      <td>21</td>
      <td>Male</td>
      <td>161</td>
      <td>Devine</td>
      <td>1.76</td>
    </tr>
    <tr>
      <th>18</th>
      <td>18</td>
      <td>Reunasu60</td>
      <td>22</td>
      <td>Female</td>
      <td>82</td>
      <td>Nirvana</td>
      <td>4.90</td>
    </tr>
    <tr>
      <th>19</th>
      <td>19</td>
      <td>Chamalo71</td>
      <td>30</td>
      <td>Male</td>
      <td>89</td>
      <td>Blazefury, Protector of Delusions</td>
      <td>4.64</td>
    </tr>
    <tr>
      <th>20</th>
      <td>20</td>
      <td>Iathenudil29</td>
      <td>20</td>
      <td>Male</td>
      <td>57</td>
      <td>Despair, Favor of Due Diligence</td>
      <td>4.60</td>
    </tr>
    <tr>
      <th>21</th>
      <td>21</td>
      <td>Phiarithdeu40</td>
      <td>20</td>
      <td>Male</td>
      <td>168</td>
      <td>Sun Strike, Jaws of Twisted Visions</td>
      <td>1.48</td>
    </tr>
    <tr>
      <th>22</th>
      <td>22</td>
      <td>Siarithria38</td>
      <td>38</td>
      <td>Other / Non-Disclosed</td>
      <td>24</td>
      <td>Warped Fetish</td>
      <td>3.81</td>
    </tr>
    <tr>
      <th>23</th>
      <td>23</td>
      <td>Eyrian71</td>
      <td>40</td>
      <td>Male</td>
      <td>151</td>
      <td>Severance</td>
      <td>3.40</td>
    </tr>
    <tr>
      <th>24</th>
      <td>24</td>
      <td>Siala43</td>
      <td>30</td>
      <td>Male</td>
      <td>132</td>
      <td>Persuasion</td>
      <td>3.19</td>
    </tr>
    <tr>
      <th>25</th>
      <td>25</td>
      <td>Lisirra87</td>
      <td>29</td>
      <td>Male</td>
      <td>178</td>
      <td>Oathbreaker, Last Hope of the Breaking Storm</td>
      <td>4.23</td>
    </tr>
    <tr>
      <th>26</th>
      <td>26</td>
      <td>Lirtossa84</td>
      <td>11</td>
      <td>Male</td>
      <td>71</td>
      <td>Demise</td>
      <td>1.61</td>
    </tr>
    <tr>
      <th>27</th>
      <td>27</td>
      <td>Eusri44</td>
      <td>7</td>
      <td>Male</td>
      <td>96</td>
      <td>Blood-Forged Skeletal Spine</td>
      <td>3.09</td>
    </tr>
    <tr>
      <th>28</th>
      <td>28</td>
      <td>Aela59</td>
      <td>21</td>
      <td>Male</td>
      <td>119</td>
      <td>Stormbringer, Dark Blade of Ending Misery</td>
      <td>4.32</td>
    </tr>
    <tr>
      <th>29</th>
      <td>29</td>
      <td>Tyida79</td>
      <td>24</td>
      <td>Male</td>
      <td>37</td>
      <td>Shadow Strike, Glory of Ending Hope</td>
      <td>3.16</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>750</th>
      <td>750</td>
      <td>Iljask75</td>
      <td>22</td>
      <td>Male</td>
      <td>167</td>
      <td>Malice, Legacy of the Queen</td>
      <td>3.61</td>
    </tr>
    <tr>
      <th>751</th>
      <td>751</td>
      <td>Lisjaskan36</td>
      <td>11</td>
      <td>Male</td>
      <td>30</td>
      <td>Stormcaller</td>
      <td>3.36</td>
    </tr>
    <tr>
      <th>752</th>
      <td>752</td>
      <td>Mindjasksya61</td>
      <td>17</td>
      <td>Male</td>
      <td>112</td>
      <td>Worldbreaker</td>
      <td>2.60</td>
    </tr>
    <tr>
      <th>753</th>
      <td>753</td>
      <td>Frichirranya75</td>
      <td>36</td>
      <td>Male</td>
      <td>178</td>
      <td>Oathbreaker, Last Hope of the Breaking Storm</td>
      <td>4.23</td>
    </tr>
    <tr>
      <th>754</th>
      <td>754</td>
      <td>Pheosurllorin41</td>
      <td>23</td>
      <td>Female</td>
      <td>79</td>
      <td>Alpha, Oath of Zeal</td>
      <td>4.05</td>
    </tr>
    <tr>
      <th>755</th>
      <td>755</td>
      <td>Raesty92</td>
      <td>12</td>
      <td>Male</td>
      <td>76</td>
      <td>Haunted Bronzed Bludgeon</td>
      <td>3.15</td>
    </tr>
    <tr>
      <th>756</th>
      <td>756</td>
      <td>Ilast79</td>
      <td>20</td>
      <td>Male</td>
      <td>73</td>
      <td>Ritual Mace</td>
      <td>2.05</td>
    </tr>
    <tr>
      <th>757</th>
      <td>757</td>
      <td>Eratiel90</td>
      <td>18</td>
      <td>Male</td>
      <td>57</td>
      <td>Despair, Favor of Due Diligence</td>
      <td>4.60</td>
    </tr>
    <tr>
      <th>758</th>
      <td>758</td>
      <td>Iral74</td>
      <td>21</td>
      <td>Male</td>
      <td>182</td>
      <td>Toothpick</td>
      <td>4.03</td>
    </tr>
    <tr>
      <th>759</th>
      <td>759</td>
      <td>Tyaelorap29</td>
      <td>25</td>
      <td>Male</td>
      <td>72</td>
      <td>Winter's Bite</td>
      <td>3.77</td>
    </tr>
    <tr>
      <th>760</th>
      <td>760</td>
      <td>Aithelis62</td>
      <td>21</td>
      <td>Male</td>
      <td>44</td>
      <td>Bonecarvin Battle Axe</td>
      <td>2.38</td>
    </tr>
    <tr>
      <th>761</th>
      <td>761</td>
      <td>Assim27</td>
      <td>45</td>
      <td>Male</td>
      <td>17</td>
      <td>Lazarus, Terror of the Earth</td>
      <td>1.70</td>
    </tr>
    <tr>
      <th>762</th>
      <td>762</td>
      <td>Asur53</td>
      <td>26</td>
      <td>Male</td>
      <td>110</td>
      <td>Suspension</td>
      <td>1.44</td>
    </tr>
    <tr>
      <th>763</th>
      <td>763</td>
      <td>Lassilsala30</td>
      <td>21</td>
      <td>Male</td>
      <td>85</td>
      <td>Malificent Bag</td>
      <td>1.75</td>
    </tr>
    <tr>
      <th>764</th>
      <td>764</td>
      <td>Saedaiphos46</td>
      <td>18</td>
      <td>Male</td>
      <td>113</td>
      <td>Solitude's Reaver</td>
      <td>4.07</td>
    </tr>
    <tr>
      <th>765</th>
      <td>765</td>
      <td>Irith83</td>
      <td>18</td>
      <td>Male</td>
      <td>130</td>
      <td>Alpha</td>
      <td>2.07</td>
    </tr>
    <tr>
      <th>766</th>
      <td>766</td>
      <td>Aelastirin39</td>
      <td>23</td>
      <td>Male</td>
      <td>58</td>
      <td>Freak's Bite, Favor of Holy Might</td>
      <td>4.14</td>
    </tr>
    <tr>
      <th>767</th>
      <td>767</td>
      <td>Ilmol66</td>
      <td>8</td>
      <td>Female</td>
      <td>92</td>
      <td>Final Critic</td>
      <td>4.88</td>
    </tr>
    <tr>
      <th>768</th>
      <td>768</td>
      <td>Assassasta79</td>
      <td>38</td>
      <td>Male</td>
      <td>92</td>
      <td>Final Critic</td>
      <td>4.88</td>
    </tr>
    <tr>
      <th>769</th>
      <td>769</td>
      <td>Ilosian36</td>
      <td>15</td>
      <td>Male</td>
      <td>145</td>
      <td>Fiery Glass Crusader</td>
      <td>4.58</td>
    </tr>
    <tr>
      <th>770</th>
      <td>770</td>
      <td>Lirtosia63</td>
      <td>34</td>
      <td>Male</td>
      <td>12</td>
      <td>Dawne</td>
      <td>1.02</td>
    </tr>
    <tr>
      <th>771</th>
      <td>771</td>
      <td>Iskossasda43</td>
      <td>16</td>
      <td>Male</td>
      <td>25</td>
      <td>Hero Cane</td>
      <td>4.35</td>
    </tr>
    <tr>
      <th>772</th>
      <td>772</td>
      <td>Asur53</td>
      <td>26</td>
      <td>Male</td>
      <td>136</td>
      <td>Ghastly Adamantite Protector</td>
      <td>3.58</td>
    </tr>
    <tr>
      <th>773</th>
      <td>773</td>
      <td>Hala31</td>
      <td>21</td>
      <td>Male</td>
      <td>19</td>
      <td>Pursuit, Cudgel of Necromancy</td>
      <td>1.02</td>
    </tr>
    <tr>
      <th>774</th>
      <td>774</td>
      <td>Jiskjask80</td>
      <td>11</td>
      <td>Male</td>
      <td>92</td>
      <td>Final Critic</td>
      <td>4.19</td>
    </tr>
    <tr>
      <th>775</th>
      <td>775</td>
      <td>Aethedru70</td>
      <td>21</td>
      <td>Female</td>
      <td>60</td>
      <td>Wolf</td>
      <td>3.54</td>
    </tr>
    <tr>
      <th>776</th>
      <td>776</td>
      <td>Iral74</td>
      <td>21</td>
      <td>Male</td>
      <td>164</td>
      <td>Exiled Doomblade</td>
      <td>1.63</td>
    </tr>
    <tr>
      <th>777</th>
      <td>777</td>
      <td>Yathecal72</td>
      <td>20</td>
      <td>Male</td>
      <td>67</td>
      <td>Celeste, Incarnation of the Corrupted</td>
      <td>3.46</td>
    </tr>
    <tr>
      <th>778</th>
      <td>778</td>
      <td>Sisur91</td>
      <td>7</td>
      <td>Male</td>
      <td>92</td>
      <td>Final Critic</td>
      <td>4.19</td>
    </tr>
    <tr>
      <th>779</th>
      <td>779</td>
      <td>Ennrian78</td>
      <td>24</td>
      <td>Male</td>
      <td>50</td>
      <td>Dawn</td>
      <td>4.60</td>
    </tr>
  </tbody>
</table>
<p>780 rows × 7 columns</p>
</div>




```python
total_players = len(data["SN"].value_counts())
pd.DataFrame({"Total Players":[total_players]})
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Total Players</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>576</td>
    </tr>
  </tbody>
</table>
</div>




```python
#Total Number of players
purchases = data["Purchase ID"].count()

#Number of unique items
unique = data["Item Name"].nunique()

#Calculate the average purchase price
average = data["Price"].mean()

#Total Revenue
revenue = data["Price"].sum()

data_df = pd.DataFrame ({
    "Number of unique items":[unique],
    "Average Price":[average],
    "Number of purchases":[purchases],
    "Total Revenue":[revenue]
})
data_df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Number of unique items</th>
      <th>Average Price</th>
      <th>Number of purchases</th>
      <th>Total Revenue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>179</td>
      <td>3.050987</td>
      <td>780</td>
      <td>2379.77</td>
    </tr>
  </tbody>
</table>
</div>




```python
#Gender Demographics
#percentage and count of male players
#percentage and count of female players
#Percentage and Count of Other / Non-Disclosed

Gcount = data.groupby("Gender")
fm = Gcount.nunique()["SN"]
percent = fm / total_players * 100
pd.DataFrame({'Counts': fm,
             'Percent': percent})
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Counts</th>
      <th>Percent</th>
    </tr>
    <tr>
      <th>Gender</th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Female</th>
      <td>81</td>
      <td>14.062500</td>
    </tr>
    <tr>
      <th>Male</th>
      <td>484</td>
      <td>84.027778</td>
    </tr>
    <tr>
      <th>Other / Non-Disclosed</th>
      <td>11</td>
      <td>1.909722</td>
    </tr>
  </tbody>
</table>
</div>




```python
#Purchasing Analysis(Gender)
#Purchase count per Gender
purchase_c = data.groupby(["Gender"]).count()["Purchase ID"]

#average price per gender
average_p = data.groupby(["Gender"]).mean()["Price"]

#Total purchase value per Gender 
total_p = data.groupby(["Gender"]).sum()["Price"]

##Average total purchase per person
average_t = total_p/fm

pd.DataFrame({
    "Purchase Count": purchase_c,
    "Average Purchase Price": average_p,
    "Total Purchase Value": total_p,
    "Average Total Purchase per Person": average_t
})
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Purchase Count</th>
      <th>Average Purchase Price</th>
      <th>Total Purchase Value</th>
      <th>Average Total Purchase per Person</th>
    </tr>
    <tr>
      <th>Gender</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Female</th>
      <td>113</td>
      <td>3.203009</td>
      <td>361.94</td>
      <td>4.468395</td>
    </tr>
    <tr>
      <th>Male</th>
      <td>652</td>
      <td>3.017853</td>
      <td>1967.64</td>
      <td>4.065372</td>
    </tr>
    <tr>
      <th>Other / Non-Disclosed</th>
      <td>15</td>
      <td>3.346000</td>
      <td>50.19</td>
      <td>4.562727</td>
    </tr>
  </tbody>
</table>
</div>




```python
#Age Demographics
#Establish bins for ages
bins = [0, 9, 14, 19, 24, 29, 34, 39, 40]
group_name = ["<10", "10-14", "15-19", "20-24", "25-29", "30-34", "35-39", "40+"]
data["Age data"] = pd.cut(data["Age"], bins, labels=group_name)
data

#Calculate the numberd and percntages by age group
age_group = data.groupby("Age data")

count_age = age_group["SN"].nunique()

age_percentage = (count_age/total_players) * 100

#dataframe to hold results
age_d = pd.DataFrame({"Total_count": count_age,
                     "Percentage of Players": age_percentage,
                     })
age_d.index.name = None
age_d
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Total_count</th>
      <th>Percentage of Players</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>&lt;10</th>
      <td>17</td>
      <td>2.951389</td>
    </tr>
    <tr>
      <th>10-14</th>
      <td>22</td>
      <td>3.819444</td>
    </tr>
    <tr>
      <th>15-19</th>
      <td>107</td>
      <td>18.576389</td>
    </tr>
    <tr>
      <th>20-24</th>
      <td>258</td>
      <td>44.791667</td>
    </tr>
    <tr>
      <th>25-29</th>
      <td>77</td>
      <td>13.368056</td>
    </tr>
    <tr>
      <th>30-34</th>
      <td>52</td>
      <td>9.027778</td>
    </tr>
    <tr>
      <th>35-39</th>
      <td>31</td>
      <td>5.381944</td>
    </tr>
    <tr>
      <th>40+</th>
      <td>5</td>
      <td>0.868056</td>
    </tr>
  </tbody>
</table>
</div>




```python
#Purchasing Analysis
#Run basic calculations to obtain purchase count, avg. purchase price, avg. purchase total per person etc.
purchase_age = age_group["Purchase ID"].count()

avg_purchase_age = age_group["Price"].mean()

total_purchase = age_group["Price"].sum()

avg_purchase_per_age = total_purchase/count_age

age_d = pd.DataFrame({"Purchase Count": purchase_age,
                     "Average Purchase Price": avg_purchase_age,
                     "Total Purchase Value": total_purchase,
                     "Average Purchase Total per Person": avg_purchase_per_age})

age_d.index.name = None
age_d
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Purchase Count</th>
      <th>Average Purchase Price</th>
      <th>Total Purchase Value</th>
      <th>Average Purchase Total per Person</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>&lt;10</th>
      <td>23</td>
      <td>3.353478</td>
      <td>77.13</td>
      <td>4.537059</td>
    </tr>
    <tr>
      <th>10-14</th>
      <td>28</td>
      <td>2.956429</td>
      <td>82.78</td>
      <td>3.762727</td>
    </tr>
    <tr>
      <th>15-19</th>
      <td>136</td>
      <td>3.035956</td>
      <td>412.89</td>
      <td>3.858785</td>
    </tr>
    <tr>
      <th>20-24</th>
      <td>365</td>
      <td>3.052219</td>
      <td>1114.06</td>
      <td>4.318062</td>
    </tr>
    <tr>
      <th>25-29</th>
      <td>101</td>
      <td>2.900990</td>
      <td>293.00</td>
      <td>3.805195</td>
    </tr>
    <tr>
      <th>30-34</th>
      <td>73</td>
      <td>2.931507</td>
      <td>214.00</td>
      <td>4.115385</td>
    </tr>
    <tr>
      <th>35-39</th>
      <td>41</td>
      <td>3.601707</td>
      <td>147.67</td>
      <td>4.763548</td>
    </tr>
    <tr>
      <th>40+</th>
      <td>6</td>
      <td>2.785000</td>
      <td>16.71</td>
      <td>3.342000</td>
    </tr>
  </tbody>
</table>
</div>




```python
#Top Spenders 
#Identify the the top 5 spenders in the game by total purchase value, then list (in a table)
spender = data.groupby("SN")

purchase_spender = spender["Purchase ID"].count()

avg_purchase_spender = spender["Price"].mean()

purchase_per_spender = spender["Price"].sum()

top_spender = pd.DataFrame({"Purchase Count": purchase_spender,
                           "Average Purchase Price": avg_purchase_spender,
                           "Total Purchase Value":purchase_per_spender})
format_spenders = top_spender.sort_values(["Total Purchase Value"], ascending=False).head()
format_spenders
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Purchase Count</th>
      <th>Average Purchase Price</th>
      <th>Total Purchase Value</th>
    </tr>
    <tr>
      <th>SN</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Lisosia93</th>
      <td>5</td>
      <td>3.792000</td>
      <td>18.96</td>
    </tr>
    <tr>
      <th>Idastidru52</th>
      <td>4</td>
      <td>3.862500</td>
      <td>15.45</td>
    </tr>
    <tr>
      <th>Chamjask73</th>
      <td>3</td>
      <td>4.610000</td>
      <td>13.83</td>
    </tr>
    <tr>
      <th>Iral74</th>
      <td>4</td>
      <td>3.405000</td>
      <td>13.62</td>
    </tr>
    <tr>
      <th>Iskadarya95</th>
      <td>3</td>
      <td>4.366667</td>
      <td>13.10</td>
    </tr>
  </tbody>
</table>
</div>




```python
#Most Popular items
#Retrieve the Item ID, Item Name, and Item Price columns
#Group by Item ID and Item Name. Perform calculations to obtain purchase count, average item price, and total purchase value
item = data[["Item ID", "Item Name", "Price"]]

items = item.groupby(["Item ID", "Item Name"])

count_items = items["Price"].count()

purchase_value = (items["Price"].sum())

item_price = purchase_value/count_items

popular_items = pd.DataFrame({"Purchase Count": count_items,
                             "Item Price": item_price,
                             "Total Purchase Value": purchase_value})
format_popular = popular_items.sort_values(["Purchase Count"], ascending=False).head()
format_popular
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th></th>
      <th>Purchase Count</th>
      <th>Item Price</th>
      <th>Total Purchase Value</th>
    </tr>
    <tr>
      <th>Item ID</th>
      <th>Item Name</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>92</th>
      <th>Final Critic</th>
      <td>13</td>
      <td>4.614615</td>
      <td>59.99</td>
    </tr>
    <tr>
      <th>178</th>
      <th>Oathbreaker, Last Hope of the Breaking Storm</th>
      <td>12</td>
      <td>4.230000</td>
      <td>50.76</td>
    </tr>
    <tr>
      <th>145</th>
      <th>Fiery Glass Crusader</th>
      <td>9</td>
      <td>4.580000</td>
      <td>41.22</td>
    </tr>
    <tr>
      <th>132</th>
      <th>Persuasion</th>
      <td>9</td>
      <td>3.221111</td>
      <td>28.99</td>
    </tr>
    <tr>
      <th>108</th>
      <th>Extraction, Quickblade Of Trembling Hands</th>
      <td>9</td>
      <td>3.530000</td>
      <td>31.77</td>
    </tr>
  </tbody>
</table>
</div>




```python
#Most Profitable Items
format_popular = popular_items.sort_values(["Total Purchase Value"], ascending=False).head()
format_popular
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th></th>
      <th>Purchase Count</th>
      <th>Item Price</th>
      <th>Total Purchase Value</th>
    </tr>
    <tr>
      <th>Item ID</th>
      <th>Item Name</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>92</th>
      <th>Final Critic</th>
      <td>13</td>
      <td>4.614615</td>
      <td>59.99</td>
    </tr>
    <tr>
      <th>178</th>
      <th>Oathbreaker, Last Hope of the Breaking Storm</th>
      <td>12</td>
      <td>4.230000</td>
      <td>50.76</td>
    </tr>
    <tr>
      <th>82</th>
      <th>Nirvana</th>
      <td>9</td>
      <td>4.900000</td>
      <td>44.10</td>
    </tr>
    <tr>
      <th>145</th>
      <th>Fiery Glass Crusader</th>
      <td>9</td>
      <td>4.580000</td>
      <td>41.22</td>
    </tr>
    <tr>
      <th>103</th>
      <th>Singed Scalpel</th>
      <td>8</td>
      <td>4.350000</td>
      <td>34.80</td>
    </tr>
  </tbody>
</table>
</div>


