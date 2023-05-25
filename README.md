<h1 align="center"><h1 align="center">Chess Tournament Manager - OpenClassRooms Project 04 </h1><br>
<br>
Ce script Python est le quatrieme projet réalisé dans le cadre d'une formation chez OpenClassrooms.

## OVERVIEW
Beta version of a chess tournament manager (Swiss system).
<br>
<br>
## REQUISITORIES <br>
<br>
Python3<br>
<br>

## INSTALLATION
Start by closing the repository :
```
git clone https://github.com/Ashywar/OCR_P4
```
Start access the project folder

## for Windows
Create a virtual environment
```
python -m venv env
```
Enable the virtual environment
```
cd env/scripts
source activate
```

## for Linux or macOS
Create a virtual environment 
```
python3 -m venv env
```
Activate the virtual environment with 
```
source env/bin/activate 
```
## . . . 
Install the python dependencies to the virtual environment
```
pip install -r requirements.txt
```
  
## Use FLAKE8
In order to generate a flake8 report, run the following command :
```
flake8 --ignore=E501,W503 --format=html --htmldir=flake-report --exclude=venv
```
Open the html file into the flake-report repertory to show the report.

## LAUNCH 
Run
```
python main.py
```
1. Create 8 players. <br>
2. Create a new tournament. <br>
3. The computer generates pairs of players for the first round. <br>
4. When the round is finished, enter the results. <br>
5. Repeat steps 3 and 4 for subsequent rounds until 4 rounds are played, and the tournament is over. <br>


