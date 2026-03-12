# Algal Blooms in Lake Chapala: A Differential Equation Model

This project develops a **differential equation model** to study algal bloom dynamics in **Lake Chapala, Mexico**, complying with provided project guidelines and expectations. The final model developed in this project captures how periodic pesticide application and government intervention in different forms that influence algae population density over time. The idea is simple: determine the growth function & the death function of algal population and express the differential equation model as `"Growth term - Death term"`.

Using observed environmental data, the parameters of the model are calibrated to represent:
* pesticide application cycles (periodic schedule) 
* maximum percent growth rate 
* gradual decrease of bloom intensity  

Later in the project, the model is solved analytically and analyzed to determine when the algae population exceeds the **odor threshold of 100 g/m²**, which can negatively affect drinking water quality and cause disturbance to local people and tourists.

This project demonstrates:
* Differential equation modeling  
* Parameter calibration from real-world observations  
* Analytical solution of separable differential equations  
* Environmental interpretation of mathematical models

## Project Structure

```
algal-bloom-de-model/
│
├── src/                                # contains the LaTeX source code for the paper
│   └── main.tex 
│   └── bibliography/                   # BibTeX references
│       └── biblio.bib
│
├── figures/                            # graphs used in the paper
│   ├── v1.png
│   └── ...
│
├── paper/                              # final compiled paper
│   └── algal_bloom_model_final.pdf
│
├── docs/                               # project guideline & expectations
│   └── <project-guideline>
│
├── project/                            # portable LaTeX project archive (can be imported directly into Overleaf or other LaTeX editors)
│   └── <project>.zip
│
├── README.md                           # project overview and instructions
└── LICENSE                             # project license
```

## Getting Started

There are two ways to view or work with this project.

#### 1. Read the Final Paper

The compiled paper is available here. Simply open the PDF in `/algal-bloom-de-model/paper/Algal-Blooms-A-DE-Model.pdf` to read the full project.

#### 2. Compile the Paper Locally

##### **Prerequisites**
You will need an `Overleaf account`, which is a free online LaTeX editor:
* Go to overleaf.com and create an account (it's free!).
* That's literally it!

##### **Import the Project**

The project import-ready file is provided. Just import the project `/algal-bloom-de-model/project/Algal_Blooms_in_Lake_Chapala__A_Differential_Equation_Model.zip` into overleaf following the steps below:

```
1. Download the file located at: `/algal-bloom-de-model/project/Algal_Blooms_in_Lake_Chapala__A_Differential_Equation_Model.zip`.
``` 
```
2. Log in to Overleaf.
   Click **New Project → Upload Project**.
   Upload the `.zip` file.
``` 
Overleaf will automatically extract the project and compile the paper.

## Built With

* **LaTeX** – scientific document preparation
* **BibTeX** – bibliography and citation management 
* **GeoGebra** – graphing and visualization of the model

## Contributing

Contributions are welcome! Open an issue or submit a pull request if you want to make a correction or improve the project.

## Author

* **Soikat Saha**
* **Shruti D Mishra**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* Environmental data provided through the course project description
* Special thanks to **`Professor Cayce Fylling`** for guidance and support throughout this project
* The LaTeX and open-source mathematics community