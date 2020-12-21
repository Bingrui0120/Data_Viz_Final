# Cervical Cancer in China
##### Bingrui Li

<br>

## Executive Summary
This analysis will describe the status quo of cervical cancer in China from the perspective of data visualization. In 2018, 570,000 women worldwide were still diagnosed with cervical cancer and 310,000 women died of cervical cancer. Since 2002, China has ranked first in the world in the number of deaths from cervical cancer. Cervical cancer is currently the only malignant tumor with a clear cause and fully effective tertiary prevention methods. There are three key measures for cervical cancer prevention and treatment: vaccination, screening and treatment. 

But in China, both HPV vaccination and cervical cancer screening face many difficulties. Currently, the types of HPV vaccines on the Chinese market are limited, and most of the vaccines (3 of 4) are imported products. Appointment HPV vaccines are always in short supply. In addition, many people also said that they did not know the HPV vaccine, and said that even if they are willing to receive the HPV vaccine, they have limited affordable price. However, the Chinese government previously stated that due to financial constraints, it currently does not consider including the HPV vaccine in its medical insurance policy.

In terms of cervical cancer screening, although the Chinese government has been promoting its free cervical and breast cancer screening program, the population covered by the program so far is very limited. In rural areas, women do not know much about cervical cancer, so they are not motivated to actively participate in screening. Even if they participate in cervical cancer screening, the accuracy of screening in rural medical institutions is low, and screening efficiency is also poor, causing many cases of misdiagnosis or false positives. At the government level, cervical cancer screening has not received much attention. When the government faces the impact of other infectious diseases, the funds allocated for cervical cancer screening are often squeezed.

<br>

## Every year, a large number of women die of cervical cancer.

Cervical cancer is one of the most common female malignancies worldwide. In 2018, it ranked second in incidence and third in mortality worldwide, 570,000 women worldwide were still diagnosed with cervical cancer, and 310,000 women died of cervical cancer. About 85% of new cases and 90% of deaths occurred in underdeveloped areas (FIGO, 2018). In low- and middle-income countries, the incidence of cervical cancer is almost twice that of high-income countries, and the mortality rate is three times that of high-income countries.

In developed countries, due to the widespread use of Pap smear testing, the overall incidence of cervical cancer has been declining. However, in the past two decades, the incidence and mortality of cervical cancer in China have been on the rise, especially among young women. Since 2002, China has ranked first in the world in the number of deaths from cervical cancer (Li, 2017). According to data from the National Cancer Center, a total of 75,500 people were newly diagnosed in China in 2016, and about 38,400 women died of cervical cancer. According to the China Health Statistics Yearbook, the mortality rate of women from cervical cancer increases with age. Among them, women aged 30-49 in urban areas and women aged 30-59 in rural areas accounted for the highest proportion of deaths from malignant tumors in women of the same age group.

The chart below shows the number of deaths from cervical cancer in all countries in the world in the past two decades. Among them, the blue line represents China, the orange line represents developed countries, and the gray line represents other countries. On the Dashboard, users can choose to view China, developed countries or other countries. Position the mouse on each line and Tableau will display the year, country and absolute value of the data.

#### Number of Female Death Due to Cervical Cancer World Wide
<iframe seamless frameborder="0" src="https://public.tableau.com/views/NumberofFemaleDeath/CervicalCancerDeathNumber?:language=en&:embed=yes&:display_count=yes&:showVizHome=no" width = '800' height = '600' scrolling='yes' ></iframe>

<br>

The chart below shows the number of deaths due to cervical cancer per 100,000 in all countries in the world over the past two decades. It can be seen that although China's value is in the middle position compared with other countries in the world, the number of female died due to cervical cancer in recent years is still larger than that of developed countries. Most of the countries with higher numbers in the figure come from African countries. In Africa, most people are still in extreme poverty. Therefore, the average number of women giving birth to children is much higher than that of other countries in the world, and the proportion of households using contraceptive measures is also lower than other countries. A number of studies have confirmed that the use of contraceptive measures, the number of births, the age of first sexual intercourse, and the number of sexual partners are all related to cervical cancer. Therefore, it is normal that the incidence of cervical cancer in African countries is higher than that in developed countries and China.

#### Number of Female Death per 100000 Women
<iframe seamless frameborder="0" src="
https://public.tableau.com/views/CervicalCancerDeathper100000Women/CervicalCancerDeathper100000Women?:language=en&:embed=yes&:display_count=yes&:showVizHome=no" width = '800' height = '600' scrolling='yes' ></iframe>
<br>

The figure below shows the comparison of contraceptive uses in China, developed countries and other countries. It can be seen that the percentage of China's use of contraceptives is the same as that of developed countries. However, the countries with the smaller size of each circle are mostly backward developing countries. The use of contraceptive measures is inversely related to cervical cancer mortality.

#### Percentage of Contraceptive Use World Wide
<iframe seamless frameborder="0" src="
https://public.tableau.com/views/ContraceptiveUse_16085420630200/Sheet7?:language=en&:embed=yes&:display_count=yes&:showVizHome=no" width = '800' height = '600' scrolling='yes' ></iframe>

<br>

If we put the average percentage of contraceptive use and the average deaths of cervical cancer together, we could see the their reverse relationship.

#### Average Percentage of Contraceptive Use vs Average Deaths of Cervical Cancer
<iframe seamless frameborder="0" src="
https://public.tableau.com/views/usevsdeath/Dashboard2?:language=en&:embed=yes&:display_count=yes&:showVizHome=no" width = '800' height = '600' scrolling='yes' ></iframe>

China has invested a lot of money in recent years to solve extreme poverty. China's per capita GDP increases, and the people's living standards have continued to grow. In addition, the Chinese government initiated a free cervical and breast cancer screening program for women in 2008. However, the number of female deaths from cervical cancer in China has not declined, and even tends to increase year by year.

<br>

## Cervical cancer is a preventable cancer.

Almost 100% of cervical cancers are caused by infection with a high-risk type of human HPV. Cervical cancer is currently the only malignant tumor with a clear cause and fully effective tertiary prevention methods, according to the WHO. The two main methods to control the onset of cervical cancer are through HPV vaccine and screening for precancerous lesions (FIGO, 2018). Since the advent of the HPV vaccine in 2006, a total of 107 countries around the world have officially included the HPV vaccine in their national immunization plans (WHO, 2020). Because of HPV vaccination and cancer screening, the incidence of cervical cancer in developed countries has dropped significantly in the past two to three decades. From 1975 to 2010, the incidence of cervical cancer in US female was reduced by half. From 2000 to 2015, the death toll from cervical cancer per 100,000 people also dropped from 2.8 to 2.3 per year (Curry, 2018).

The figure below compares the number of people who died of cervical cancer per 100,000 people in 1990 and 2015. It can be seen that in the past 15 years, the number of deaths from cervical cancer in developed countries has decreased. The United States fell from 3.96 to 2.98, and the United Kingdom fell from 6.44 to 3.06. However, China only dropped from 6.96 to 4.78, and its proportion is much higher than that of the United States in 1990. Therefore, the problem of cervical cancer in China brooks no delay.

#### Map of Cervical Cancer Death per 100000 Women
<iframe seamless frameborder="0" src="
https://public.tableau.com/views/Map_16085365905860/Dashboard1?:language=en&:embed=yes&:display_count=yes&:showVizHome=no" width = '1000' height = '800' scrolling='yes' ></iframe>

<br>

### HPV Vaccine

The HPV vaccination still faces many problems in China. The current public acceptance of HPV vaccine is still low. In a questionnaire (Fu, 2018), by 2015, only 25% of respondents had heard of HPV preventive vaccines, and 14% knew that HPV vaccines could prevent cervical cancer and other diseases. Although WHO recommends that HPV vaccine be included in the immunization program, in September 2019, the National Medical Insurance Administration made it clear that non-therapeutic items such as tumor screening and cervical cancer vaccination will not be considered for inclusion in the basic medical insurance fund payment scope (NHC 5448, 2019). The medical security system has not been able to expand the scope of payment to non-treatment or preventive screening items. The HPV vaccines currently on the market in China are purchased by each vaccination site, usually priced according to market rules, and citizens voluntarily vaccinate at their own expense.

#### Percentage of Government Spending on Health

<iframe seamless frameborder="0" src="
https://public.tableau.com/views/GovernmentSpending_16085440771510/GovernmentSpending?:language=en&:embed=yes&:display_count=yes&:showVizHome=no" width = '1000' height = '800' scrolling='yes' ></iframe>

Currently, there are four types of cervical cancer vaccines on the Chinese market, namely, the quadrivalent and nine-valent vaccines produced by Merck, the bivalent vaccine produced by GSK, and the domestic bivalent vaccine developed by a Xiamen biological company. It is difficult to develop HPV vaccines with quadrivalent and nine-valent (Caixin, 2019). As a biological product, vaccines are highly uncertain and have high requirements for vaccine production, transportation and storage (Zhao, 2019), so China's HPV with the quadrivalent and nine-valent vaccines are imported and the price is relatively high. Such a low-yield and high-price situation is very detrimental to increasing the HPV vaccine injection rate.

The chart below shows the HPV vaccine injection rate in the United States in recent years. It can be seen that the injection rate continues to rise. Men are also at risk of contracting the HPV virus, so the number of men vaccinated against HPV is increasing year by year. However, in China, only women can make appointments for HPV vaccination.

#### HPV Vaccine Rates in the United States
<iframe seamless frameborder="0" src="
https://public.tableau.com/views/HPV_16085442148190/Sheet8?:language=en&:embed=yes&:display_count=yes&:showVizHome=no" width = '1000' height = '800' scrolling='yes' ></iframe>

<br>

*Therefore, if China wants to reduce the incidence of cervical cancer through HPV vaccine injection, it should increase investment in cervical cancer vaccines, encourage Chinese companies to develop and produce more low-cost HPV vaccines, and increase HPV vaccine education and publicity.*

<br>

### Cervical Cancer Screening
WHO also recommends that high coverage of 80% of people at risk of cervical cancer is an important factor in the successful screening program. Since 2009, China has begun to implement the "two cancers”(cervical cancer and breast cancer) free inspection project for rural women, and through central government funding, free cervical cancer and breast cancer inspections have been launched nationwide for rural women of the right age. However, in 2015, the proportion of women aged 20-64 in China who had previously received cervical cancer screening was only 25.7% (of which 31.4% were screened for 35-64 years old), of which 30.0% in urban areas and 22.6% in rural areas (Xia, 2020).

The application of cytology screening has reduced the incidence and mortality of cervical cancer by 70% to 90% in developed countries (Zhang, 2015). At present, 95% of medical institutions in China use Papanicolaou (Pap) tests to detect cervical cancer (Fu, 2018). This method is operated by a gynecologist. The gynecologist removes a small amount of cell samples from the neck of the uterus, places them on a glass slide, and then let the cytopathologist observe whether the cell morphology is abnormal under the microscope. Although this method is easy to operate and low in cost, this method requires a high level of skill for the screening doctor (Qiao, 2008). 
 
Even for highly trained professionals, missed diagnosis still occurs. Its accuracy is affected by many factors, resulting in its low sensitivity, only 50% or even lower, and it is prone to a large number of false negative diagnosis results (Zhang, 2015). Currently in China, medical workers, especially doctors in cytopathology are very scarce (Wang, 2015). In the context of China's huge population base, it is almost impossible to screen women in rural areas for cervical cancer once every five years through cytological testing. Because the number of cervical cancer screenings is too large for institutions to cope with, some institutions will choose to outsource cell screening to third-party companies (Caixin, 2019). However, due to the difficulty of identifying the relevant responsible persons and the uneven quality of these outsourcing companies, misdiagnosis often occurs (Caixin, 2019).


#### Number of Doctors Per 1000 People Worldwide
<iframe seamless frameborder="0" src="
https://public.tableau.com/views/NumberofDoctors_16085439694380/NumberofDoctors?:language=en&:embed=yes&:display_count=yes&:showVizHome=no" width = '1000' height = '800' scrolling='yes' ></iframe>

The picture above shows  the number of doctors per 1000 people worldwide. It can be seen that there is still a big gap between the number of Chinese doctors and developed countries. The number of doctors is crucial for cervical cancer screening.

Earlier in a meeting in 2019, Song Li, deputy director of the Department of Maternal and Child Health of the National Health Commission, said, since the central authority stated that local special funds can be dynamically allocated, "some places put more funds into the prevention and control of infectious diseases, so the allocation of funds for the prevention and control of cervical cancer and breast cancer has been affected.” (Caixin, 2019)

<br>
*All in all, if China wants to reduce the incidence of cervical cancer through cervical cancer screening, it should strengthen the training of doctors in rural areas on the knowledge and technology of Pap test cytology to reduce the rate of misdiagnosis and improve work efficiency, and gradually transits the Pap test cytology methodto the VIA testing method to reduce the cost and misdiagnosis rate of cervical cancer screening to improve the efficiency of screening. In addition, the provinces and cities should all set up special funds for cervical cancer screening programs.*

<br>

### Data Source
For the ptoject, most of the data is from Gapmider(https://www.gapminder.org/data/).

Data from Gapminder website can be reused freely, but need to attribute the original data source and Gapminder. User are allowed to copy and redistribute the material in any medium or format, remix, transform, and build upon the material for any purpose, even commercially. 

All data is downloaded by indicators, and the data merge process is included in the jupyter notebook under the main branch.

In addition, the US HPV vaccine injection rate data is from the website below.
https://progressreport.cancer.gov/prevention/hpv_immunization#field_data_source

### Platforms
- Github
- Python
- Tableau

### Reference
Wen, Xiaoduo et al. “Urban-Rural Disparity in Cervical Cancer in China and Feasible Interventions for Tackling the Rural Excess.” Medicine (Baltimore) 98.1 (2019): e13907–e13907. Web.

Li, Hui et al. “The Incidence and Mortality of Cervical Cancer in Ningbo During 2006-2014, China.” Iranian journal of public health 46.10 (2017): 1324–1331. Print.
Ma Song, An Lin. A study on the death level of Chinese women from cervical cancer from 1996 to 2005. Modern Preventive Medicine, 2009, 36(01): 47-50.

Zhou Hui, Wang Dongyan, Luo Ming, Lin Zhongqiu. "FIGO 2018 Women's Cancer Report"- interpretation of cervical cancer guidelines. Chinese Journal of Practical Gynecology and Obstetrics, 2019, 35(01): 95-103.

Outline of China Cancer Prevention and Control Program (2004-2010). Chinese Cancer, 2004(02): 3-6.

A cervical cancer-free future: First-ever global commitment to eliminate a cancer: https:// www.who.int/news/item/17-11-2020-a-cervical-cancer-free-future-first-ever-global- commitment-to-eliminate-a-cancer

Curry, Krist. “Screening for Cervical Cancer: US Preventive Services Task Force Recommendation Statement.” JAMA : the journal of the American Medical Association 320.7 (2018): 674–686. Web.

Caixin, https://m.datanews.caixin.com/m/2019-11-22/101486274.html

<br>



