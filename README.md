## North Carolina State Center Birth Statistics Case Study

**Introduction**

The North Carolina State Center for Health Statistics and Howard W. Odum Institute for Research in Social Science at the University of North Carolina at Chapel Hill make publicly available birth and infant death data for all children born in the state of North Carolina. The dataset, spanning from 1968 to the present, encompasses a wide record of data collection. Within the extensive dataset that comprises of 120,300 entries from 2001, we will focus on a random sample of 800 births, from which a subset of 80 records has been selected for this case study.

For this study we will extract a sample of 80 observations from the available 800 observations using **R**.

**Objectives**

Numerical and graphical statistics will be utilized to characterize this dataset with focus on variables such as age of the mother, weeks of gestation, weight gained during pregnancy, child weight (in grams) and child weight in ounces, and the whether the mother smoked or not during pregnancy. The aim is to assess the potential impact of smoking status on weight. A detailed description of data, including the data type and unit of measure for each variable will be provided. Note that the following description of the data as to data type and unit of measure for each variable is critical to the analysis including choice of type of analysis.

**Data Description**

![Screenshot 2024-01-15 123711](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/d4e0cea6-3aba-429c-996f-105802dd6a96)

**Note:** MAGE is a discrete quantitative variable. WEEKS, GAINED, TOUNCES, and TGRAM are continuous quantitative variables. SMOKE is a qualitative categorical value with numerical values (1 OR 0).

**Results and Discussion**

Draw a simple random sample (SRS) of size 80 from this 800 observation dataset. Use this SRS size 80 sample, for each of the 5 quantitative variables MAGE, WEEKS, GAINED, TOUNCES, and TGRAMS:

**a)   Calculate the mean, median, standard deviation, IQR, and range.**

![Screenshot 2024-01-25 162336](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/7bb910d7-a44a-45af-8d97-0b2c8bdb9cff)

•	Sample of 80 observations in total. The mean is 27.375 and the median is 28. Variability as measured by the SD for this sample is 6.3213; Range is 27 and IQR is 9.25.

![Screenshot 2024-01-25 162350](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/b4caa6c3-d961-480d-b0ba-8739c64694b5)

•	Sample of 80 observations in total. The mean is 38.837 and the median is 39. Variability as measured by the SD for this sample is 2.052; Range is 14 and IQR is 2.00.

![Screenshot 2024-01-25 162411](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/2d291545-b886-4784-b7f9-d628115077a0)

•	Sample of 80 observations in total with 2 missing values. The mean is 29.8589 and the median is 28. Variability as measured by the SD for this sample is 14.827; Range is 95 and IQR is 15.

![Screenshot 2024-01-25 162423](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/62e50f35-c545-483e-a157-3f1476abf104)

•	Sample of 80 observations in total. The mean is 116.175 and the median is 117. Variability as measured by the SD for this sample is 19.539; Range is 120 and IQR is 22.50.

![Screenshot 2024-01-25 162441](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/4056e720-f698-4ff4-a24e-bef09dc520ab)

•	Sample of 80 observations in total. The mean is 3293.561 and the median is 3316.95. Variability as measured by the SD for this sample as 553.9446; Range is 3402 and IQR is 637.875.

**b)   Calculate the skew and kurtosis

![Screenshot 2024-01-25 162818](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/16374ad6-e94f-45a9-a255-2106dfdc20a5)

•	The random sample count is 80. Skew for mage was -0.05 and kurtosis was 0.71

![Screenshot 2024-01-25 162911](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/60f52295-d71a-4c0d-9177-4b39630fc5d8)

•	The random sample count is 80. Skew for weeks was -0.36 and kurtosis was 2.86

![Screenshot 2024-01-25 163013](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/96ec4a38-a63d-4743-aebf-c3ff668d9bcd)

•	Out of a sample size of 80 values, two values were missing under gained. Skew was 1.63 and kurtosis was 5.09. Gained is the only variable with a positive number skew.

![Screenshot 2024-01-25 163028](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/9ddf9449-a64c-42d2-bc40-06b7ccc2efc0)

•	The random sample count is 80. Skew for tounces is -0.92 and kurtosis is 2.69.

![Screenshot 2024-01-25 163136](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/4cd86c59-6710-4f00-b71a-a3aa55be6ae5)

•	The random sample count is 80. Skew for tgrams was -0.92 and the kurtosis was at 2.69, the same as variable tounces.

**c)   Construct a histogram and comment on the shape of the distribution.**

**Mage**

![image](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/2db2f0d4-c9ef-43b1-bb07-f5db4b1199be)

![image](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/8b6d953a-1848-43ac-86cd-607b9e258661)

•	There is a large deviation of data for variable mage (age of mother) as illustrated by the distribution curve. There are no extreme values. The mean is 27.375 and SD is 6.321. Kurtosis is platykurtic.

**Weeks**

![image](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/f94161f6-22b9-4426-865d-1607d3bfb776)

![image](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/b01035fb-75af-4d45-aaeb-840b0a873b3b)

•	The distribution of the variable weeks is concentrated between 36-40 weeks of gestation. The mean is 38.837 and SD is 2.052. The distribution resembles a bell-shaped curve. Weeks has the lowest SD compared to the other variables. Kurtosis is mesokurtic.

**Gained**

![image](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/b6dd8ae6-b852-46c6-bd6b-cd6ef4376603)

![image](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/2e676906-8577-4a07-b7cf-cf70b4aa1335)

•	Out of a sample size of 80, two values were missing under gained. The distribution line is positively skewed for the variable with most values on the left. The mean is 29.858 and the SD is 14.827. Distribution is concentrated between values of 10 to 40 pounds of weight gained during pregnancy. Kurtosis is mesokurtic.

**Tounces**

![image](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/1ef37a3a-ff43-4091-9f76-75176416ceda)

![image](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/ec964325-de29-46f4-9b7c-bb7d0a3215ae)

•	The distribution is skewed negatively to the right for the variable tounces (weight of child in ounces). The mean is 116.175 and the SD is 19.539. Data distribution is identical to the variable tounces. The skew (-0.92) and kurtosis (2.69) are the same. Kurtosis is leptokurtic.

**Tgrams**

![image](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/75a91edf-035b-4b2b-b8ba-59342f35b290)

![image](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/adcb5a83-2a04-4045-9124-f70fe33aa64a)

•	The variable tgrams (weight of child in grams) is negatively skewed to the right. The mean is 3293.561 and the SD is 553.9946. Kurtosis is leptokurtic.

**d)   Do the histograms for TOUNCES and TGRAMS look strikingly similar? Why?**

The histograms for TOUNCES and TGRAMS do look similar. The variable TOUNCES is identified as the weight of a child in ounces while the variable TGRAMS is identified as the weight of a child in grams. The mean for TOUNCES is 116.17 while the mean for TGRAMS is 3293.56, a wide range that reflects a lower density and frequency for TOUNCES and a greater density and frequency for TGRAMS. The distribution for both histograms is identical because the skew (-0.92) and kurtosis (2.69) for both is the same. The distribution is skewed negatively to the right and the distribution curve peaks at around ~120 ounces, converting to about ~3401 grams.

**e)   Construct box-and-whisker plots.**

Exploratory Data Analysis

Box and whisker plots make use of the quartiles of a data set. A boxplot reveals information regarding the amount of spread, location of concentration, and symmetry of a data set.

IQR = Q3 - Q1

Range = Upper extreme – lower extreme

**MAGE**

![image](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/31084b21-098e-4d16-afe0-e0b9f03ed99f)

![Screenshot 2024-01-25 163315](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/b08fae53-7dac-4848-b531-a52066c8e421)

•	There was a total of 80 observations. The mean mage (age) was 27.38, close to the median of 28 years old. Variability as measured by the standard deviation for this sample was 6.32 years. The range for the median quartile (IQR) of observations was 9.25 years. The IQR of the variable mage is Q3 (32) – Q1 (22.75) = 9.25. Lower extreme = 10; upper extreme = 42; Range = 27

**WEEKS**

![image](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/9adf4aa8-8d44-4863-8096-7bf9bc8c21b3)

![Screenshot 2024-01-25 163430](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/9c88957d-c1e1-4dea-9944-4da86e36db94)

•	There was a total of 80 observations. The mean weeks was 38.84, close to the median of 39 weeks. Variability as measured by the standard deviation for this sample was 2.025 weeks. The range for the median quartile of observations (IQR) was 2.0 weeks. The IQR of the variable weeks is Q3 (40) – Q1 (38) = 2. Lower extreme = 31; upper extreme = 45; Range = 14

**GAINED**

![image](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/62140234-3fbb-44b9-8989-8f969c180cde)

![Screenshot 2024-01-25 163513](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/a728d515-6cdc-4a61-b9a9-64ac1fcb50ba)

•	Out of a sample size of 80, two values were missing under gained. The mean pounds gained was 29.86, close to the median of 28. Variability as measured by the standard deviation for this sample was 14.827. The range for the median quartile of observations (IQR) was 15 pounds. The IQR of the variable gained is Q3 (35) – Q1 (20) = 15. Lower extreme = 0; upper extreme = 95. Range = 95

**TOUNCES**

![image](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/d0a187ef-8856-4c3d-8d18-0d4aaaaace64)

![Screenshot 2024-01-25 163607](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/7cca5b05-4681-46fd-a951-0c0aac83dd44)

•	There was a total of 80 observations. The mean tounces was 116.2, close to the median of 117. Variability as measured by the standard deviation for this sample was 119.539. The range for the median quartile of observations (IQR) was 22.5 ounces. The IQR of the variable gained is Q3 (128.2) – Q1 (105.8) = 15. Lower extreme = 38; upper extreme = 158. Range = 120

**TGRAMS**

![image](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/6d4f9797-2a9a-400b-a31d-49803cf0504b)

![Screenshot 2024-01-25 163636](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/4cf0e004-0b23-4e20-9e0d-1ad08c1a28bb)

•	There was a total of 80 observations. The mean tgrams was 3294 grams, close to the median of 3317 grams. The variability measured by the standard deviation for this sample was 553.944 grams. The range for the median quartile (IQR) of observations was 637.875 grams. The IQR of the variable weeks is Q3 (3636) – Q1 (2998) = 637.875. Lower extreme = 1077; upper extreme = 4479; Range = 3402.


**f)   Construct side-by-side box-and-whisker plots for the variable TGRAMS for women who admitted to smoking and for those who did not admit to smoking. Do you see a difference in birth weight (TGRAMS) in the two groups? Which group has more variability?**

![image](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/9b3f4a5e-d034-4e80-ba85-ba0c858c1c99)

**Smoke** variable

**0** = mother did not smoke during pregnancy 

**1** = mother did smoke during pregnancy

![Screenshot 2024-01-15 124121](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/28d68608-d958-49dd-89b9-00e08c4d6dd7)

**Range** (Max – min) = 3402

**IQR** (Q3 – Q1) = 723

![Screenshot 2024-01-15 124131](https://github.com/efejzic/Birth-Statistics-Case-Study/assets/119814593/138feee9-ba73-45a7-bf07-9d38c0f28974)

**Range** (Max – min) = 1503

**IQR** (Q3 – Q1) = 369


The boxplot illustrates that the median for non-smokers and smokers is within the same range, 3345 grams for non-smokers and 3317 for smokers. However, there is more distribution and variability within the first quartile and third quartile for child birthweight in grams for non-smokers than for the smokers. The mean for non-smokers was slightly less at 3284 grams than the mean for smokers at 3345 grams. The IQR for non-smokers is greater at 723 than the IQR for non-smokers at 369. There is more variability in range for non-smokers at 3402 than for smokers at 1503. 

**Conclusion**

The sample dataset of 80 records showed a wide range of ages for pregnant mothers with a median age of 28 years old. The weeks of gestation for this sample size concentrated between 36-48 weeks of gestation with a median record at 39 weeks. Out of the sample size of 80, two values were missing for the variable gained. The variable indicates pounds gained pregnancy and the median number of pounds is 28 with a standard deviation of 14.827. The histogram for this variable represents a mesokurtic distribution, with concentration falling between 10 to 40 pounds of weight gained. Tounces represent the weight of the child in ounces and tgrams represent the weight in grams, both with a skew of -0.92 and kurtosis of 2.69. In a graphical representation, the skew negatively distributes the data to the left and the kurtosis presents a sharper peak compared to a normal distribution (a bell-shaped curve). When examining the weight of infants in grams, there is greater variability observed among non-smoking mothers compared to those who smoke. Mothers who abstain from smoking during pregnancy tend to exhibit a wider range of childbirth weights in grams.
