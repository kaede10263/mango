# mango classifier
 

click [here](https://aidea-web.tw/aicup_mango) to find others information

The official competition will provide manually marked mango quality grades (3 types) and disease types (7 types) files, and divide the data into training sets, construction sets (development sets) and test sets. The target of the competition is to extract features from the images provided by the conference and identify the labels provided, and to evaluate the images based on the extracted features to confirm the correlation between grade and defective products. This competition uses WAR (Weighted Average Recall) to evaluate the accuracy of the participants' prediction results on the test corpus. The organizer will publish the relevant rules of the competition in the registration rules and specify the specifications of the type of association.
<div align=center><img src="https://github.com/kaede10263/mango/blob/master/others/score.png"/></div>

## examples
<img width="250" height="250" src="https://github.com/kaede10263/mango/blob/master/data/C1-P1_Dev/00033.jpg"/> A <img width="250" height="250" src="https://github.com/kaede10263/mango/blob/master/data/C1-P1_Dev/00027.jpg"/> B <img width="250" height="250" src="https://github.com/kaede10263/mango/blob/master/data/C1-P1_Dev/00051.jpg"/> C 

## envirment
*   python = 3.6
*   numpy = 1.14.3
*   pandas = 0.23.0
*   tensorflow-gpu= 1.1.15
*   keras = 2.2.4

## install
Install anaconda and add anaconda into envirment path.
```
conda create --name myenv python=3.6
```

clone this github and activate VM
```
activate myenv
```

and run this 

``` 
pip install -r requirements.txt
``` 

## schedule
<div align=center><img src="https://github.com/kaede10263/mango/blob/master/others/schedule.png"/></div>

