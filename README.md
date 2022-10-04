# Project Name

> Lending Club Case Study

## Table of Contents

- [Project Name](#project-name)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
  - [Conclusions](#conclusions)
  - [Technologies Used](#technologies-used)
  - [Acknowledgements](#acknowledgements)
  - [Contact](#contact)
  - [Local setup of repository with vscode](#local-setup-of-repository-with-vscode)

## General Information

- Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return.
- The aim of this project is to analyse the data and suggest the driver variables behind loan default.

## Conclusions

- Charged off proportion is higher for applicants with one or two derogatory public records.
- Charged off proportion is higher for applicants with two bankruptcy records.
- Charged off proprtion is higher for loans given to small businesses.
- Charged off proportion is higher for loans with Grade G.
  - As we move across the grades from A to F the fully paid proprtion falls.
- Charged off proportion is higher for loans with Subgrade F5.
  - As we move across the sub grades from A1 to F5 the fully paid proprtion falls.
- Charged off proportion is higher for applicants with less than one year of work experience.
- Charged off proportion is higher for long term(60) loans.
General observations:
- Lenders invest higher value in riskier loans(Grade G) with higher interest rates.
- Interest rate increases as the loan grade degrades.
- Most Loans are for debt consolidation.

## Technologies Used

- jupyter - version 1.0.0
- pandas - version 1.3.5
- matplotlib - version 3.5.3
- seaborn - version 0.12.0
- numpy - version 1.21.6
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

## Contact

Created by [Kishore](https://github.com/kishore-n-george) - feel free to contact me!

## Local setup of repository with vscode

- Create a virtual env by running `python -m venv .venv`
- Activate the venv by running `source ./.venv/bin/activate`
- Install the dependencies by running `pip3 install -r requirements.txt`
- Run the following commnads to make jupyter notebook use the venv `pip3 install ipykernel`
- `python3 -m ipykernel install --user --name=lending-club`
- Restart vscode.
