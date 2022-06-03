# hcde-410-final

**Project Overview**

This project analyzes abortion rates and contraceptives used nationwide in 2017. The goal is to see how abortion rates vary in America and if access to contraceptives impacts abortion rates. The current research questions are "Does the rate of use of contraceptives affect rates of abortion in specific states?" and "Does the rate of abortion vary based on the region of the U.S. a state is in?". There is background information regarding the rates of abortion across the United States, access to contraceptives by state, individual state laws concerning abortion, and many articles about the correlation between access to women's healthcare and the impacts on abortion rates.  

**Goal of the Project**

To understand if there is a connection between the using contraceptives to prevent pregnancy and abortions and the number/rates of abortions across individual states and regions of the United States. 

**Research Questions & Hypotheses to be Addressed** 
* *Research Q1: Does the rate of use of contraceptives affect rates of abortion in specific states?*

* Hypothesis 1: Higher use levels of contraceptives lead to lower abortion rates in a specific state.

* *Research Q2: Does the rate of abortion vary based on the region of the US a state is in?*

* Hypothesis 2: Rates of abortions are higher in states where abortion is more accepted (specifically the West Coast and Northeast region) because people are more comfortable and feel safer sharing the data.

**Data**

The research questions will be addressed using the data from Guttmacher.
The first set of data is about [abortion rates and numbers](https://data.guttmacher.org/states/table?state=AL+AK+AZ+AR+CA+CO+CT+DE+DC+FL+GA+HI+ID+IL+IN+IA+KS+KY+LA+ME+MD+MA+MI+MN+MS+MO+MT+NE+NV+NH+NJ+NM+NY+NC+ND+OH+OK+OR+PA+RI+SC+SD+TN+TX+UT+VT+VA+WA+WV+WI+WY&topics=65+66&dataset=data). 
The second dataset used from Guttmacher was about [pregnancies and abortions averted](https://data.guttmacher.org/states/table?state=AL+AK+AZ+AR+CA+CO+CT+DE+DC+FL+GA+HI+ID+IL+IN+IA+KS+KY+LA+ME+MD+MA+MI+MN+MS+MO+MT+NE+NV+NH+NJ+NM+NY+NC+ND+OH+OK+OR+PA+RI+SC+SD+TN+TX+UT+VT+VA+WA+WV+WI+WY&dataset=data&topics=113). 


MIT License Copyright (c) 2019 Guttmacher Institute & Elliana Beberness

Link to the Seattle Open Data Terms of Use and Privacy: https://data.seattle.gov/stories/s/Data-Policy/6ukr-wvup/ (Links to an external site.)

**Values of all fields in the file:**
* abortion_stats: abortion statistic dataset
* abortion_nums: rows including only abortion numbers per state
* abortion_rate: rows including only abortion rates per state
* state_by_num & state_by_rate: abbreviation of state name
* avg_pacific_num: average number of abortion rates calculated from the pacific region of the United States
* avg_midwest_num: average number of abortion rates calculated from the midwest region of the United States
* avg_rocky_mountain_num: average number of abortion rates calculated from the rocky mountain region of the United States
* avg_southwest_num: average number of abortion rates calculated from the southwest region of the United States
* avg_southeast_num: average number of abortion rates calculated from the southeast region of the United States
* avg_northeast_num: average number of abortion rates calculated from the northeast region of the United States
* contraceptives_data: data about contraceptives used to prevent abortions and pregnancies
* abortions_averted: abortions averted using contraceptives from a publically funded center
* pregnancies_averted: pregnancies averted using contraceptives from a publically funded center


**Special considerations:**
* Only specific columns of the datasets are used for the evaluation, including "U.S. State	Abortion rate (the no. of abortions per 1,000 women aged 15-44), by the state of occurrence, 2017" and "No. of abortions, by the state of occurrence, 2017" from the first dataset about abortion rates and numbers. The second dataset about pregnancy and abortion aversion included "No. of pregnancies averted by publicly funded centers, 2016" and "No. of abortions averted by publicly funded centers, 2016". 
* Rates and numbers may be more commonly reported in places with more lenient abortion laws. 
* Data about abortion rates and numbers is from 2017, while data about the pregnancies and abortions averted is from 2016.  

