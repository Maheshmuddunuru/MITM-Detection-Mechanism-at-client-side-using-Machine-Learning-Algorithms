# Research Methodology Project

![social](https://img.shields.io/github/followers/Maheshmuddunuru?style=social)![twitter](https://img.shields.io/twitter/follow/MaheshK71025493?style=social)
This is a README file indicating the use of this repository

## Table of Contents

1. [Title of the Project](#Name-of-the-Project)
2. [Description](#Description)
3. [Languages](#Languages-Used)
4. [Packages](Packages)
5. [Files to run](#Files-to-run)
6. [Lists In Markdown](#lists-in-markdown)
7. [Necessary Things for a README](#necessary-things-for-a-readme)

## Name of the Project

- MITM Detection Mechanism at client side using Machine Learning Algorithms

## Description
Man-in-the-Middle attacks are talked about a lot in the technical field of computer security because they are one of the biggest concerns for professionals. MitM (Man in the Middle) attacks occur when an attacker intercepts data in the middle of a conversation by using a technique of interjecting themselves. Aside from attacking the data flow between the endpoints, attackers compromise the integrity and confidentiality of that data, as well. Through communication interception, an adversary can eavesdrop on confidential information and modify message integrity. Additionally, an adversary may intercept, modify, or destroy messages to end communication for one of the parties, thereby constituting a compromise of availability. In order to prevent the man in the middle attacks there are several methods, firewalls and intrusion detection systems, but unfortunately these methods are only applied to the administrative side of operations, i.e., Enterprise WIDS (Wireless Intrusion Detection System). The client system is not equipped to detect, prevent, and control these attacks, making it vulnerable to attack for the attacker. Our goal is to build a quality Intrusion Detection system using Anomaly Detection in Machine Learning that will detect network attacks on a client side basis in order to prevent those attacks from happening.

## Languages Used

I have used python Language for this project and to run the Model.ipynb file you need to have a Google colab account or jupyter notebook in your system.

## Packages
This project requires the following packages.
```bash 
import pandas as pd
from sklearn import svm
import numpy as np
from sklearn.svm import OneClassSVM
from sklearn.model_selection import train_test_split  
```

## Files to run

The main file to run this project is available here [Model.ipynb](https://github.com/Maheshmuddunuru/MITM-Detection-Mechanism-at-client-side-using-Machine-Learning-Algorithms/blob/main/Model.ipynb) and the dataset required to run the code is available in the Dataset folder [WIFIDATACSV1.csv](https://github.com/Maheshmuddunuru/MITM-Detection-Mechanism-at-client-side-using-Machine-Learning-Algorithms/blob/main/Dataset/WIFIDATAcsv1.csv)
<br/>
Datasets Folder-- The dataset used for this project can also be found here along with the original database file from where it originated.

## Usage

- Open the Google colab or Jupyter notebook.
- Load the Model.ipynb file to the notebook.
- Download the dataset WIFIDATAcsv1.csv file to the notebook and adjust the current path of the dataset in the Model.ipynb file.
- Following is a screenshot of the dataset
   <br/>
 ![alt text](https://github.com/Maheshmuddunuru/MITM-Detection-Mechanism-at-client-side-using-Machine-Learning-Algorithms/blob/main/Review%20of%20data.jpg)
   <br/>
- The following is a snippet of code from the project.
   <br/>
 ![alt text](https://github.com/Maheshmuddunuru/MITM-Detection-Mechanism-at-client-side-using-Machine-Learning-Algorithms/blob/main/codesnippet.jpg)
   <br/>
- Make sure all the resources and packages are included and run the code.
- Upon running the code, you will get output with the accuracy.
## Support
You can reach out to me at one of the following places:
- via [email](mmuddunu@lakeheadu.ca)
- via ![twitter](https://img.shields.io/twitter/follow/MaheshK71025493?style=social)

Here's a list of cool pokemon:

- Mew
- Mewtwo
- Celebi
- Arceus
- Porygon
- Mimikyu

Here's a list of my favorite pens:

1. Lamy 200
2. Herbin
3. Pilot

Here's a nested list!

1. This is a number
   1. This is a sub-number
   2. This is another sub-number
2. This is a number
   - This is a subpoint
   - This is another sub-point
     1. This is a sub-sub number

## Necessary Things for a README

Depending on exactly what sort of project you are doing, there are a number of things that you may or may not want to include in a readme. There is really no **one true way** to do it. Readme's are a kind of _artform_.

*__However__* there are a few things that you should consider including:

1. Name of your project.
2. Description of your project.
3. Badges.
4. Graphics / Visuals
5. Install Instructions
6. Usage (how does one use the program once it is installed.)
7. Support / Contact Details.
8. Road-map (future ideas)
9. How to contribute
10. Authors / Acknowledgements (give credit where credit is due!)
11. License
12. Project Status

## Name of your Project

- This should be, simply, the name of your project.. maybe with some kind of a version Number

## Description of your project

- This is a brief, but accurate description telling potential users _exactly_ what your project is about. This is akin to an "abstract" in academic works. 

## Badges

![social](https://img.shields.io/github/followers/trevortomesh?style=social)![twitter](https://img.shields.io/twitter/follow/trevortomesh?style=social)![languages](https://img.shields.io/github/languages/count/trevortomesh/research-methods-class)

- Badges are small images that convey meta data such as whether or not all the tests are passing, version numbers, languages used, etc. 
- Get badges at shields.io

## Visuals

- Visuals are very important! You might want to include screenshots of your code in operation. GIFS are also great!
- Just use the "![ ]()" to input images.

## Installation 

- Describe how your software / development is installed. Sometimes it's easy as something like:

```bash
sudo apt-get install my-cool-thing
```

- often it involves a bit of  downloading sources and building:

```bash
git clone my-cool-repo.git
cd /my-cool-repo
cd /build
make
```

- You should list out steps as unambiguously as humanly possible!!
- Often people don't read the actual install instructions, but they just copy and paste what is in the black boxes. __Keep this in mind!__

## Usage

- Describe how the program / project is going to be used once it is installed. 
- If it is a command line app, you'll want to give CLI examples:

```bash
cool-project -arg1 -arg2
```

- then maybe show a screenshot of  the results :smile:

## Support

- tell users how they can get a hold of you

Contact: [email me](trevor.tomesh@gmail.com)

## Road-map

- List your panned future developments
- This is a good way to keep track of what it is that you want to do in the future!


## License

- Depending on what kind of project you are doing, you might have a specific copyright. 
- Usually on github, everything is open source!
- You can find license info here: [license](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/licensing-a-repository)
  
## Project Status

- A lot of the time people will abandon projects. You should always at least let people know if you aren't interested in working on a project anymore!
- Someone might want to pick it up on your behalf!

