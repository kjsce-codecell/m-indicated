[![Build Status](https://travis-ci.org/Showndarya/Hacktoberfest.svg?branch=master)](https://travis-ci.org/Showndarya/Hacktoberfest)
![Open Source Love](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-red.svg)
![GitHub](https://img.shields.io/github/license/kjsce-codecell/m-indicated.svg)
![GitHub forks](https://img.shields.io/github/forks/kjsce-codecell/m-indicated.svg)
![GitHub issues](https://img.shields.io/github/issues/kjsce-codecell/m-indicated.svg)
![GitHub pull requests](https://img.shields.io/github/issues-pr/kjsce-codecell/m-indicated.svg)
![GitHub contributors](https://img.shields.io/github/contributors/kjsce-codecell/m-indicated.svg)
![GitHub top language](https://img.shields.io/github/languages/top/kjsce-codecell/m-indicated.svg)

# M-Indicated :book:

An exhaustive collection of Local Train timings as json files for easy access.

## How to contribute 

> [Refer the template provided below to add your word](https://github.com/kjsce-codecell/m-indicated/CONTRIBUTING.md)

## Create your first pull request :sunglasses:

> [Fork this repository](https://help.github.com/articles/fork-a-repo/)

>  Clone the forked repository from your account

> Add your JSON file to the respective folder.

> Commit your changes with an appropriate message.

> [Create a pull request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/)

## Example file
path: `startStation/startTime.json` (first letter needs to be capitalized)
```json
{
    "timing": "startTime_in_HH:MM_in 24 hour format",
    "path": {
        "start":"startStation",
        "end":"endStation"
    },
    "type": "Fast/Slow"
}
```

path: `DI/09-05.json`
```json
{
    "timing":"09:05",
    "path":{
        "start":"DI",
        "end":"CSMT"
    },
    "type": "Slow"
}
```

## Station Codes  
Station Code | Station Name |
--- | --- |
CSMT | Chhatrapati Shivaji Maharaj Terminal |
BY | Byculla |
C | Kurla |
V | Vidyavihar |
D | Dadar |
T | Thane |
DI | Dombivli |
K | Kalyan |
A | Ambernath |
BL | Badlapur |
TI | Titwala |
AS | Asangaon |
N | Kasara |
S | Karjat |
KP | Khopoli |
G | Ghatkopar |
CH | Churchgate |
B | Bandra |
AD | Andheri |
BO | Borivali |
BY | Bhayandar |
BS | Vasai Road |
V | Virar |
DN | Dahanu |
VS | Vashi |
NU | Nerul |
PL | Panvel |



## Hall of Fame :fire:

Check out the [Hall of Fame]() for a list of contributors with a minimum of one commit with their gravatar. To know more about a contributor, click on the gravatar to go to their github profile.
