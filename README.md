# Classification of Mobile Phone Price Using Machine Learning Algorithms

In this project, only machine learning techniques were used, utilizing data obtained both from Kaggle and independently from the internet using Python. 

The project consists of two parts, where we compare whether we need all the features for classification or if selecting specific features would also be effective.

During the processes, the GridSearch function is used to input various parameters, allowing us to find the best ones.

# Outputs
![image](https://github.com/user-attachments/assets/9151705c-d058-470d-ab37-c935708d39cf)

## First Part

Confusion matrix and Comparison between models

![image](https://github.com/user-attachments/assets/85d1457e-a904-4408-85f8-2d4d27430dec)

## Second Part

The effect of each feature on the price

![image](https://github.com/user-attachments/assets/2d6e401b-0cf1-44aa-8648-70beb443f81c)

Confusion matrix and Comparison between models

![image](https://github.com/user-attachments/assets/b8e6654b-233c-4822-bd66-1ee56102484f)

### Final Comparison Between First and Second Part

![image](https://github.com/user-attachments/assets/7469ae55-6af8-41ea-bb35-0bbc668a6a1c)

# Dataset

pc - Primary Camera mega pixels

fc - Front Camera mega pixels

sc_h - Screen Height of mobile in cm

sc_w - Screen Width of mobile in cm

m_dep - Mobile Depth in cm

px_width - Pixel Resolution Width

px_height - Pixel Resolution Height

ram - Random Access Memory in Mega Bytes

int_memory - Internal Memory in Giga Bytes

four_g - Has 4G or not

three_g - Has 3G or not

dual_sim - Has dual sim support or not

battery_power - Total energy a battery can store in one time measured in mAh

touch_screen - Has touch screen or not

clock_speed - speed at which microprocessor executes instructions

n_cores - Number of cores of processor

wifi - Has wifi or not

blue - Has bluetooth or not

mobile_wt - Weight of mobile phone

talk_time - longest time that a single battery charge will last when you are

price_range - This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).
