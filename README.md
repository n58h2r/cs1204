java c
Econ 7810 Homework #1
Fall, 2024
Due date: 2 October. 2024; 1pm.
Do not copy and paste the answers from your classmates. Two identicalhomework will be treated as cheating. Do not copy and paste the entire outputof your statistical package's. Report only the relevant part of the output. Please also submit your R-script for the empirical part. Please put all your work in one single file and upload via Moodle.
Part I: Exercises (You may use the distribution table when appropriate.)
1.1. Compute the following probabilities
(a) If Y is distributed  N(0,4) , find Pr(Y ≤ 2).
(b) If Y is distributed  N(2,9) , find Pr(Y > 2).
(c) If Y is distributed  N(60,25) , find Pr(30 ≤ Y ≤ 72).
(d) If Y is distributed  N(5,16) , find Pr(7 ≤ Y ≤ 9).
1.2. Suppose Yi, i = 1,2, … , n, are i. i. d. random variables, each distributed N(10,20).
(a). Compute Pr(9.5 ≤ Y ≤ 10.5) when (i) n=20, (ii) n=100, and (iii) n=1,000
(b). Suppose c is a positive number. Show that Pr(10 — C ≤ Y ≤ 10 +C) becomes close to 1.0 as n grows large.1.3   A survey of 1055 registered voters is conducted, and the voters are asked to choose between candidate A and candidate B. Let p denote the fraction of voters in the population who prefer candidate A, and let p(^) denote the fraction of voters in the sample who prefer Candidate A. In the survey, p(^) = 0.58.
(a). Test H0: p = 0.5 vs. H1: p ≠ 0.5  using a 5% significance level.  (b). Test  H0: p = 0.5 vs. H1: p > 0.5  using a 5% significance level.(c). Construct a 95% confidence interval for p. (d). Construct a 99% confidence interval for p. (e). construct a 50% confidence interval for p.
1.4 To investigate possible gender discrimination in a firm, a sample of 100 men and 80 women with similar job descriptions are selected at random. A summary of the resulting monthly salaries follows
Average Salary (y)
Standard Deviation (sy)
n
Men
$3100
$200
100
Women
$2900
$320
80What do these data suggest about wage differences in the firm? Do they represent statistically significant evidence that average wages of men and wo代 写Econ 7810 Homework #1 Fall, 2024R
代做程序编程语言men are different? (To answer this question, first state the null and alternative hypothesis; second, compute the relevant t-statistic; third, compare the t-statistics with the critical values to answer the question.)
Part II: Empirical Exercise (Please download the corresponding data from Moodle and use R to complete the part.)
2.1  World Bank Development Report DataThe point of this exercise is to help you understand the fact of poverty on the one hand, and acquaint you with R on the other.  You will need to download the data set (wbdr.dta); this data set contains 1997 variables, unless otherwise noted). Here are some description of the variables.
code     :        country code (alphabetical)
country  :    country name
illit_f :     % illiterate, female aged 15+
illit_m:    % illiterate, male aged 15+
illit_t :    % illiterate, total aged 15+
mort_inf :  infant mortality rate, per 1000
mort_5:  < age 5 mortality rate, per 100
gnppc:   GNP per capita (US$1995)
gnppcppp:  GNP per capita (PPP)
mort77: 1977 infant mort rate, per 1000
gnppc77: 1977 GNP per capita (US$1995)
You may use appropriate table in answering the questions. Please hand in your R script file with the problem set.
(a)       What are the mean and standard deviation of GNP per capita  (US$1995), illiteracy rate, infant mortality rate and under 5 mortality rate in 1997 across countries?
(b)     Restrict your data set to countries for which we have GNP per capita for 1997.  What are the mean, minimum, and maximum illiteracy rate, infant mortality rate (for 1997), and under 5 mortality rate among the 40 richest countries?  Among the 40 poorest countries? What does this tell you about the relationship between income and illiteracy, and income and mortality
(c)      Now from part (b), find the median GNP per capita for the richest and poorest country groups. How is different from their mean GNP per capita？Why might the mean and median be different? What information can we infer about the income distribution (inequality) from this?

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
