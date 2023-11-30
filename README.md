# Elite Estate

A series of code used for understanding the behaviour of different variables in Madrid's Real Estate

# Table of contents
1. [Description](#Description)
2. [Installation](#Installation)
3. [Usage](#Usage)
7. [Authors](#Authors)
9. [License](#License)

## Description

Elite Estate is a Spanish data analytics firm based on collecting and interpreting data from the housing market. This project aims to identify the most relevant variables affecting the price of houses and their specific impact on it. For carrying this out, the dataset ['houses_Madrid.csv'](https://www.kaggle.com/datasets/mirbektoktogaraev/madrid-real-estate-market/) was thoroughly analysed. Then, diverse plots were designed for offering a grpahical representation of the data in order to facilitate the understanding of specific variables. To end, the program designed a price predictor using OOP programming, which it takes as input variables such as the number of rooms, bathrooms, square meters and the presence of a parking, and calculates the predicted price according to the data analysed.

## Installation & Usage

The program provides two ways for visualizing the code that contains the data analytics of Madrid's real estate market; from Google Collab or directly in Python.

- [Python installation](#PythonInstallation)
- [Google Collab instalation](#GoogleCollabInstallation)


### Python Installation
Firstly, install [Python](https://www.python.org/downloads/) and [PyCharm](https://www.jetbrains.com/pycharm/download/).

Once you have installed both programs you are ready to begin seeing Elite Estate analysis.

The first step you need to follow is to create a folder in your computer in a place you will remember. This is very important, as you will need to save the data frame 'houses_Madrid.csv' in the same folder / environment. 

Once you have created this folder,  open up Pycharm, press on the three lines on the top left side, then click on file, new project and make sure you save the project in the previously created folder. In order for you to check where you are saving this new project you will have to look on the top of the emergent window, where it says "Location:",  if the following path leads to your folder you are done and can press "Create" on the botton right. If the path isn't leading you to the folder you created, click on the small folder at the right of the bar and look for the folder you created, once you find it click on top of it and then press on "Ok", now you are good to go and can press on "Create" at the bottom right.

Download the 'requirements.txt' and the 'eliteestate.py' files. Save them in the same folder for better organisation.

Then, install the requirements in your Pycharm terminal.

```python
pip install -r requirements.txt
```

The next step is the final one. Open the 'LanguageHUB.py' file which is the one containing the program. 

Run the code in the terminal and enjoy!

```python
python eliteestate.py
```

### Google Collab Installation

Download the 'EliteEstate.ipynb' file and have it located

After this, you will need to visit [Google Drive](https://www.google.com/drive/) and sign in and upload the 'EliteEstate.ipynb' document to 'Your Drive'. 

Once the file is uploaded, click on it to open it.

Follow the instructions shown in the file to upload the data frame 'madrid_Houses.csv' into your environment.

From here, run the cells in their respective order and you will be able to see the abalysis carried out.


## Authors
Rubén Segura: [Github](https://github.com/rubensegu)

Gonzalo Mir: [Github](https://github.com/gonzalomirr)

Yago Moreno: [Github](https://github.com/ymoreno2022)

Andrés Ramírez: [Github](https://github.com/andresramirezzz)

## License

Copyright (c) [2023] [Elite Estate]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "EliteEstate.py"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
