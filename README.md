# mango
 
Rank the mangos into three parts. One is "A", the others is "B" and others is "C".

[website](https://aidea-web.tw/aicup_mango).

A              B                   C
<img src="https://github.com/kaede10263/mango/blob/master/data/C1-P1_Dev/00033.jpg"/><img src="https://github.com/kaede10263/mango/blob/master/data/C1-P1_Dev/00027.jpg"/><img src="https://github.com/kaede10263/mango/blob/master/data/C1-P1_Dev/00051.jpg"/>




## envirment
*   python = 3.6
*   scrapy = 2.0.0
*   numpy = 1.14.3
*   pandas = 0.23.0

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



## command use
here is the folder

``` 
cd  D:\GDbackup\PROJECT\tree\Beijing_plant\plant_crawler
```
do this command

```
scrapy crawl plant_spyder
```

You will get "hello.csv" in the path.

```
python combine.py
```

You will get "result.csv" in the path.