
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
1. Clone the repository:

  ```bash
  git clone https://github.com/your_username/project_name.git
  ```
2. Navigate to the project directory:

  ```
  cd stackoverflow
  ```

3. Create a virtual environment:

  ```
  python3 -m venv env
  ```

4. Activate the virtual environment:

  For Mac/Linux:
  
  ```
  source env/bin/activate
  ```

  For Windows:

  ```
  .\env\Scripts\activate
  ```

5. Install the required packages:

  ```
  pip install -r requirements.txt
  ```

## Project Motivation<a name="motivation"></a>

In this project, I explored the following questions using Stack Overflow Annual Developer Survey data from 2023:

1. What is the most common form of employment among the participants of the survey?
2. What is the most lucrative developer type?
3. Is there any correlation between work experience and compensation?

## File Descriptions <a name="files"></a>

`requirements.txt` file lists the required packages and their versions.
`StackOverflow2023.ipynb` file contains the analysis.

## Results<a name="results"></a>

The findings generated from the analysis can be found in a Medium post available [here](https://medium.com/@dominikapiosik/how-do-the-developers-of-today-work-ff6230f860f8).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The dataset comes from Stack Overflow Insights - Stack Overflow Annual Developer Survey for 2023, the licensing for the data and other information can be found [here](https://insights.stackoverflow.com/survey).
