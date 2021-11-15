# **shredder-Machine-Hand-Safety**

The main aim of this project is to avoid the accidents in shredding ( Waste Recycling Industry ) .
The Basic function of this project is to draw the virtual safety line ( Blue & Red ) as per the Safety Guidelines 
as well as Considering the Orientation of Machineand Continiosly detect the Hand of Worker as the Hand Crosses the Safety line ,
Alarm Will raise and Machine will Turned OFF with the Help of Relay & Electrical Circuit.


## What is Shredder Machine and How it looks Like ?


    An industrial shredder is a piece of heavy duty equipment designed to shred dense and light materials to prepare them 
    for recycling or for the destruction of unusable products. They are an environmentally sound device that takes otherwise
    useless materials and transforms them into raw forms for remanufacturing or  waste management.
    Industrial shredders vary from office equipment designed to destroy sensitive documents to huge commercial industrial 
    shredders that prepare materials for disposal or recycling. In recent years, shredders have become an essential part of 
    manufacturing and production as an assist to helping reduce the amount of waste dumped into landfills.

#### shredder MAchine


![Shredder Machine ](https://papershredders.co.in/wp-content/uploads/2018/11/Heavy-Duty-Shredder-Machine-Price.jpg?250?style=centerme)


----
## Q1 : How To run this Project ?

#### step1 : Clone the Git repository 

```bash 
    $ git clone https://github.com/shubhamchau222/shredder-Machine-Hand-Safety.git

```

#### step2 : create the fresh annconda env & activate it 

```bash 
    $ conda create -n shredder python=3.7 -y 
    $ conda activate shredder

```
- make sure the env is activated or not

#### step3 : Install the Dependancies

```bash

    $ pip install -r requirements.txt

```
- if you get any error while installing deps Please  change the versions of problematic packages


---
## Q2: To create env & install all deps in single shot :

* Open your git bash terminal at the project dir & fire command 

```bash 
    $ bash setup_enviroment.sh

```
* This command will create the fresh env & install all Dependancies in single Shot.
* If you're getting any error then you can follow the above procedure manually.

## **now we good to go**

---    

#### To run the project 

```bash 

    $ python hand_detection.py

```

- in case if you get any error related to the camera( if video isn't redering )
- then change the argument of vs = VideoStream(0).start() from the hand_detection.py file 


---

# Operational Video + circuit Diagram will be posted very soon.


# Thanks For visting !! Happy Learning! 








