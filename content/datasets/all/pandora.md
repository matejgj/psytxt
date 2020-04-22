---
title: PANDORA
linktitle: PANDORA
toc: true
type: docs
# date: "2019-05-05T00:00:00+01:00"
draft: false
menu:
  all:
    parent: Datasets
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
---

## Description

[Paper]({{< ref "/publication/gjurkovic-2020-pandora/index.md" >}})

## Basic Stats


### General 
    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 10295 entries, 0 to 10294
    Data columns (total 38 columns):
     #   Column                     Non-Null Count  Dtype  
    ---  ------                     --------------  -----  
     0   author                     10295 non-null  object 
     1   mbti                       9084 non-null   object 
     2   introverted                9078 non-null   float64
     3   intuitive                  9083 non-null   float64
     4   thinking                   9080 non-null   float64
     5   perceiving                 9074 non-null   float64
     6   gender                     3227 non-null   object 
     7   age                        2324 non-null   float64
     8   enneagram                  794 non-null    object 
     9   country                    2146 non-null   object 
     10  state                      857 non-null    object 
     11  type                       1611 non-null   object 
     12  agreeableness              1606 non-null   float64
     13  openness                   1588 non-null   float64
     14  conscientiousness          1605 non-null   float64
     15  extraversion               1608 non-null   float64
     16  neuroticism                1603 non-null   float64
     17  is_description             151 non-null    float64
     18  is_percentile              368 non-null    object 
     19  is_score                   1098 non-null   float64
     20  contains_details           1386 non-null   float64
     21  num_comments               10295 non-null  int64  
     22  en_comments                10295 non-null  int64  
     23  en_comments_percentage     10295 non-null  float64
     24  region                     852 non-null    object 
     25  continent                  2146 non-null   object 
     26  country_code               2146 non-null   object 
     27  enneagram_type             794 non-null    float64
     28  enneagram_wing             790 non-null    float64
     29  is_native_english_country  2146 non-null   float64
     30  predicted_test             1677 non-null   float64
     31  test_name                  1677 non-null   object 
     32  test_scale                 1677 non-null   object 
     33  16pers_ta                  9 non-null      object 
     34  test_result_type           1677 non-null   object 
     35  is_female                  3084 non-null   float64
     36  is_female_pred             10295 non-null  int64  
     37  is_female_proba            10295 non-null  float64
    dtypes: float64(20), int64(3), object(15)
    memory usage: 3.0+ MB

### Gender

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
<table border="0" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>m</th>
      <th>f</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>gender</th>
      <td>1753</td>
      <td>1331</td>
    </tr>
  </tbody>
</table>
</div>

### Continuous variables (OCEAN, age, number of comments)
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
        font-size: small;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="0" class="dataframe">
  <thead>
    <tr style="text-align: right">
      <th></th>
      <th>age</th>
      <th>agreeableness</th>
      <th>openness</th>
      <th>conscientiousness</th>
      <th>extraversion</th>
      <th>neuroticism</th>
      <th>comments</th>
      <th>in english</th>
    </tr>
  </thead>
  <tbody>
     <tr>
      <th>count</th>
      <td>2324</td>
      <td>1606</td>
      <td>1588</td>
      <td>1605</td>
      <td>1608</td>
      <td>1603</td>
      <td>10295</td>
      <td>10295</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>25.68</td>
      <td>42.40</td>
      <td>62.45</td>
      <td>40.16</td>
      <td>37.38</td>
      <td>49.78</td>
      <td>1819</td>
      <td>1714</td>
    </tr>
    <tr>
      <th>std</th>
      <td>7.07</td>
      <td>31.04</td>
      <td>27.78</td>
      <td>30.39</td>
      <td>30.47</td>
      <td>32.37</td>
      <td>4104</td>
      <td>3866</td>
    </tr>
    <tr>
      <th>min</th>
      <td>14</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>21</td>
      <td>14</td>
      <td>44</td>
      <td>13</td>
      <td>10</td>
      <td>19</td>
      <td>219</td>
      <td>206</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>24</td>
      <td>40</td>
      <td>69</td>
      <td>35</td>
      <td>30</td>
      <td>50</td>
      <td>604</td>
      <td>569</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>29</td>
      <td>70</td>
      <td>85</td>
      <td>65</td>
      <td>61</td>
      <td>82</td>
      <td>1729</td>
      <td>1616</td>
    </tr>
    <tr>
      <th>max</th>
      <td>67</td>
      <td>100</td>
      <td>100</td>
      <td>99</td>
      <td>99</td>
      <td>100</td>
      <td>101789</td>
      <td>99568</td>
    </tr>
  </tbody>
</table>
</div>

### MBTI dimensions
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
<table border="0" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>introverted</th>
      <th>intuitive</th>
      <th>thinking</th>
      <th>perceiving</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1.0</th>
      <td>7152</td>
      <td>8054</td>
      <td>5857</td>
      <td>5315</td>
    </tr>
    <tr>
      <th>0.0</th>
      <td>1926</td>
      <td>1029</td>
      <td>3223</td>
      <td>3759</td>
    </tr>
  </tbody>
</table>
</div>

### MBTI types
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
<table border="0" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>intp</th>
      <th>intj</th>
      <th>infp</th>
      <th>infj</th>
      <th>entp</th>
      <th>enfp</th>
      <th>istp</th>
      <th>entj</th>
      <th>istj</th>
      <th>enfj</th>
      <th>isfp</th>
      <th>isfj</th>
      <th>estp</th>
      <th>esfp</th>
      <th>estj</th>
      <th>esfj</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>mbti</th>
      <td>2336</td>
      <td>1847</td>
      <td>1074</td>
      <td>1051</td>
      <td>631</td>
      <td>617</td>
      <td>407</td>
      <td>320</td>
      <td>195</td>
      <td>163</td>
      <td>123</td>
      <td>109</td>
      <td>72</td>
      <td>50</td>
      <td>43</td>
      <td>29</td>
    </tr>
  </tbody>
</table>
</div>

### Enneagram types

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
<table border="0" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>5.0</th>
      <th>4.0</th>
      <th>9.0</th>
      <th>7.0</th>
      <th>6.0</th>
      <th>2.0</th>
      <th>8.0</th>
      <th>1.0</th>
      <th>3.0</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>enneagram_type</th>
      <td>239</td>
      <td>164</td>
      <td>100</td>
      <td>79</td>
      <td>56</td>
      <td>44</td>
      <td>41</td>
      <td>41</td>
      <td>30</td>
    </tr>
  </tbody>
</table>
</div>

### Continents

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
<table border="0" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>north america</th>
      <th>europe</th>
      <th>asia</th>
      <th>oceania</th>
      <th>south america</th>
      <th>africa</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>continent</th>
      <td>1325</td>
      <td>598</td>
      <td>106</td>
      <td>87</td>
      <td>26</td>
      <td>4</td>
    </tr>
  </tbody>
</table>
</div>


### Top 10 countries
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
<table border="0" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>us</th>
      <th>canada</th>
      <th>uk</th>
      <th>australia</th>
      <th>germany</th>
      <th>netherlands</th>
      <th>sweden</th>
      <th>eu</th>
      <th>france</th>
      <th>finland</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>country</th>
      <td>1125</td>
      <td>188</td>
      <td>177</td>
      <td>73</td>
      <td>54</td>
      <td>38</td>
      <td>33</td>
      <td>27</td>
      <td>27</td>
      <td>24</td>
    </tr>
  </tbody>
</table>
</div>

### Regions (without prefix US, Canada with prefix c)

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
<table border="0" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>w</th>
      <th>mw</th>
      <th>se</th>
      <th>ne</th>
      <th>sw</th>
      <th>cw</th>
      <th>ce</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>region</th>
      <td>214</td>
      <td>155</td>
      <td>145</td>
      <td>140</td>
      <td>101</td>
      <td>53</td>
      <td>44</td>
    </tr>
  </tbody>
</table>
</div>