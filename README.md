# Burnout in Irish Farmers

## Table of Contents
1. [Research](#1-research)
   - [1.1 Background](#11-background)
   - [1.2 Dairy Farming](#12-dairy-farming)
2. [Choosing Data Variables](#2-choosing-data-variables)
   - [2.1 Burnout](#21-burnout)
   - [2.2 Sleep Quality](#22-sleep-quality)
   - [2.3 Age](#23-age)
   - [2.4 Hectares Owned](#24-hectares-owned)
3. [Data Preparation](#3-data-preparation)
   - [3.1 Import Libraries](#31-import-libraries)
   - [3.2 Synthesizing the Dataset](#32-synthesizing-the-dataset)
     - [3.2.1 Defining Variables](#321-defining-variables)
       - [Number of Entries](#number-of-entries)
       - [Burnout](#burnout)
       - [Sleep Quality](#sleep-quality)
       - [Hectares Owned](#hectares-owned)
       - [Age](#age)
     - [3.2.2 Creating DataFrame](#322-creating-dataframe)
   - [Descriptive Statistics](#descriptive-statistics)
   - [Plot Distribution](#plot-distribution)
   - [Performing Shapiro-Wilk Test for Age](#performing-shapiro-wilk-test-for-age)
4. [Analysis](#4-analysis)
5. [References](#5-references)

## 1. Research <a name="1-research"></a>

### 1.1 Background <a name="11-background"></a>

The agricultural sector is a vital part of Ireland's economy and rural culture. However, it is also known for being one of the most stressful occupations, leading to increased rates of anxiety, depression, stress, and even suicide among farmers. Farming, particularly dairy farming, has been associated with high levels of workplace accidents and fatalities. Dairy farming, although representing a smaller percentage of farms in Ireland, is overrepresented in terms of fatalities. Stressors specific to dairy farming may contribute to this overrepresentation.

### 1.2 Dairy Farming <a name="12-dairy-farming"></a>

Research has shown that dairy farmers make up a significant proportion of farming fatalities in Ireland, despite being a minority among farms. The excess stressors experienced by dairy farmers may result in burnout, a psychological syndrome emerging as a prolonged response to chronic interpersonal stressors on the job. Understanding the factors contributing to burnout among dairy farmers is crucial for addressing occupational health in the agricultural sector.

## 2. Choosing Data Variables <a name="2-choosing-data-variables"></a>

### 2.1 Burnout <a name="21-burnout"></a>

Burnout is a critical variable in this study, representing the psychological well-being of farmers. A binary variable (1=burnout, 0=no burnout) is used, with a probability of burnout set to 23.6% based on research findings.

### 2.2 Sleep Quality <a name="22-sleep-quality"></a>

Sleep quality is closely related to burnout, as poor sleep can exacerbate the effects of stress. Sleep quality is assessed as 'Poor' or 'Good' with a 50.1% probability of being poor, as per research findings.

### 2.3 Age <a name="23-age"></a>

Age is a significant factor in the experience of burnout. It reflects different life stages and career phases, influencing stress perception and coping mechanisms. Age is generated as a continuous variable with a normal distribution based on research findings.

### 2.4 Hectares Owned <a name="24-hectares-owned"></a>

The size of the land owned (hectares) can be an indicator of the scale and type of farming operations, affecting stress levels and burnout rates. It is a categorical variable based on research findings.

## 3. Data Preparation <a name="3-data-preparation"></a>

### 3.1 Import Libraries <a name="31-import-libraries"></a>

The following libraries are imported for data analysis and visualization: NumPy, Pandas, SciPy.stats, Matplotlib, and Seaborn.

### 3.2 Synthesizing the Dataset <a name="32-synthesizing-the-dataset"></a>

#### 3.2.1 Defining Variables <a name="321-defining-variables"></a>

##### Number of Entries
The dataset includes 200 entries to represent the population of Irish farmers.

##### Burnout
Burnout is generated as a binary variable with a 23.6% probability of burnout.

##### Sleep Quality
Sleep quality is generated as a binary variable with a 50.1% probability of poor sleep quality.

##### Hectares Owned
Hectares owned is a categorical variable with probabilities based on research findings.

##### Age
Age is generated as a continuous variable with a normal distribution.

#### 3.2.2 Creating DataFrame <a name="322-creating-dataframe"></a>

A DataFrame is created to organize the data variables.

## 4. Analysis <a name="4-analysis"></a>

Data analysis includes visualizations of age distribution, burnout rates, sleep quality, and hectares owned. A Shapiro-Wilk test is performed to assess the normality of the age variable.

## 5. References <a name="5-references"></a>

References to relevant research articles and sources are provided for further reading and citation.

- Alpass, F., Flett, R., Humphries, S., Massey, C., Morriss, S., & Long, N. (2004). Stress in Dairy Farming and the Adoption of New Technology. International Journal Of Stress Management, 11(3), 270-281.
- Ang, H. (2010). Occupational stress among the New Zealand farmers: A review. Labour, Employment And Work In New Zealand.
- Åkerstedt, T., Kecklund, G., & Axelsson, J. (2007). Impaired sleep after bedtime stress and worries. Biological Psychology, 76(3), 170-173.
- Bakker, A., & Demerouti, E. (2007). The Job Demands‐Resources model: state of the art. Journal Of Managerial Psychology, 22(3), 309-328.
- Bennett, K. (2016). An Exploratory Study of the effects of Stress and Fatigue on Irish Farm Safety (Higher Diploma). DBS School.
- CDC. (2016). Morbidity and Mortality Weekly Report. Centres for Disease Control and Prevention.
- Leonard, J. (2015). Stress Management in Farming in Ireland. Nuffield Ireland.
- Loughrey, J., & Hennessy, T. (2016). Farm income variability and off-farm employment in Ireland. Agricultural Finance Review, 76(3), 378-401.
- Maslach, C., Schaufeli, W. B., & Leiter, M. P. (2001). Job burnout. Annual Review of Psychology, 52, 397-422.
- Matplotlib developers. (n.d.). Matplotlib Documentation.
- McConaghy, D. (2016). Health and Social Effects of the Agricultural Downturn in Northern Ireland: A Descriptive Study. Rural Support.
- NumPy developers. (n.d.). NumPy Documentation.
- O'Connor, S., et al. (2024). Sleep issues and burnout in Irish farmers: A cross-sectional survey. Safety Science, 171, 106377.
- Scott, B. A., Aronson, K. R., & Delgado, D. (2007). The role of sleep quality in the well-being of medical residents. Journal of Occupational Health Psychology, 12(3), 289.
- SciPy community. (n.d.). SciPy Documentation.
- Söderström, M., Jeding, K., Ekstedt, M., Perski, A., & Åkerstedt, T. (2012). Insufficient sleep predicts clinical burnout. Journal of Occupational Health Psychology, 17(2), 175.
- Stack Overflow. (n.d.).
- Sundquist, K., Johansson, S. E., DeMarinis, V., Johansson, L. M., & Sundquist, J. (2013). Burnout and psychiatric morbidity among farmers. Journal of Occupational and Environmental Medicine, 55(1), 23-28.
- Zis, P., Artemiadis, A. K., Bargiotas, P., Nteveros, A., & Hadjigeorgiou, G. M. (2014). Medical studies should not be an exhausting experience: Burnout in medical students and its predictors. International Journal of Environmental Research and Public Health, 11(12), 12108-12120.
