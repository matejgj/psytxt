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


```python
p.info()
```

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



```python
