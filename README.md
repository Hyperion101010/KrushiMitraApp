# Krushi-Mitra: A smart app for farming needs.

##### Our final year project

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Farming is quite a time consuming occupation with a steep learning curve involving periodic monitoring.
A new person has to go through the hassle of having to refer multiple resources for different activities(pre-seeding, sowing, Vegetative state, Pollination, Harvest, weeding, checking weather conditions, crop diseases, crop price).
To tackle these issues, we have created an application where a hobbyist/novice can be guided in such a way that they are able to learn to cultivate maize.


## Features
- Prediction of temp, humidity reflected in cultivation tasks.
- Identify maize disease and provide remedies.
- A planned schedule to guide the user throughout the cycle on basis of week and cultivation stage.
- Expenditure calculator for profit/loss calculation of user.

## Demo

![Sample illustration](/docs/videodemo.gif)

## Sample photos

#### Dashboard:
![Screenshot](/docs/dash.png)

#### Cultivation:
![Screenshot](/docs/cult1.png)

![Screenshot](/docs/cult2.png)

#### Expenditure:
![Screenshot](/docs/exp.png)

#### Profile:
![Screenshot](/docs/prof.png)

## ML models

Present in ML models folder as .ipynb files

- CNN corn scratch [link](https://colab.research.google.com/drive/1KUmPDlDO_hN7gEpKLSRM3RC1f1bjywIU?usp=sharing) 
- CNN VGG [link](https://colab.research.google.com/drive/1QzEUXhAe_TluBLAMFYLrrASfkezlusCW?usp=sharing)
- CNN EfficientNet [link](https://colab.research.google.com/drive/1LF20vPGKmrjW_R5ess9M9u54czhUxmJb?usp=sharing) 
- weather lstm daily [link](https://colab.research.google.com/drive/1uMGvNQVqMVMbSyRTvYSabh9TTURF9YS3?usp=sharing) 
- weather arima monthly [link](https://colab.research.google.com/drive/13jkhs62m2uARdLbjAhgPRh2z58r4DFra?usp=sharing) 
- weather arima daily [link](https://colab.research.google.com/drive/1n_BPc_Yj_WWPXU158zO0ekRnvubOS4M5?usp=sharing) 
- weather FBProphet [link](https://colab.research.google.com/drive/1U_I5pYd7lRCCsEJoiYI5ZiinDvr621Ny?usp=sharing) 

## Tech
Our app makes use of a lot of tech stack for ML an other applications.

- [Heroku] - Service to deploy Python/ML model
- [Flask] - Minimal web service to implement APIs
- [MaterialUI] - For UI needs
- [Android Studio] - For development
- [Pandas, FBProphet, LSTM, Keras, tensorflow and many more] - For ML development

## Installation
You can either build this app using android studio or use the apk given in repo.

## Development
Want to contribute? Great!
Open a PR let me know.

## License
MIT

**Free Software, Hell Yeah!**