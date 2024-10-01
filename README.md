# CA in Practice

## Overview

**CA in Practice** is an educational project aimed at replicating and understanding the concepts of **Correspondence Analysis (CA)** as described in Michael Greenacre's book *"La práctica del análisis de correspondencias"* (Fundación BBVA, 2008). The goal of this project is to provide a hands-on implementation of the exercises presented in the book, ensuring that users can learn and explore the methods of correspondence analysis in an accessible way.

This project is developed strictly for educational purposes, focusing on understanding and reproducing the original examples from Greenacre's book without applying them to other real-world domains, such as finance or investments.

## Objectives

The main objectives of this project are:

- To understand the basic principles of Correspondence Analysis (CA).
- To replicate exercises and concepts from *"La práctica del análisis de correspondencias"* by Michael Greenacre.
- To verify and validate the outcomes of these exercises by comparing them with those presented in the book.
- To provide a comprehensive educational resource for those learning about correspondence analysis, by offering a detailed implementation of the book’s concepts.
- To develop a deeper understanding of the visualization of categorical data using methods such as scatter plots and correspondence maps.

## Project Structure

The repository is organized as follows:

- **data/**: Contains the data files used for exercises and replications from the book.
- **notebooks/**: Jupyter notebooks replicating the exercises and concepts from Greenacre's book.
  - Each notebook corresponds to a chapter or a specific topic from the book.

## Attribution and Disclaimer

This project is inspired by and based on the book *"La práctica del análisis de correspondencias"* by Michael Greenacre (Fundación BBVA, 2008). The implementation of the concepts and exercises presented in this repository is intended solely for educational and research purposes.

**Michael Greenacre has not participated in, approved, or endorsed this work.** The concepts and methodologies implemented here are interpreted and applied independently by the project author, **L. Felipe Castañeda G.**, based on the knowledge presented in Greenacre's book. Any errors or modifications from the original work are solely the responsibility of the author of this repository.

## How to Use This Repository

1. Clone the repository:

   ```
   git clone https://github.com/lfelipecas/ca-in-practice.git
   ```

2. Navigate to the `notebooks/` directory to explore the Jupyter notebooks, which provide detailed step-by-step replications of the analyses from the book.

3. The data needed for each notebook is stored in the `data/` directory and loaded directly into each notebook.

## Requirements

This project uses **Python 3.9.19**. The required Python libraries are included in the `requirements.txt` file:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `prince` (for Correspondence Analysis and Multiple Correspondence Analysis)
- `scipy`
- `jupyterlab`

To install the dependencies, run:

```
pip install -r requirements.txt
```

## Author

This project was created by L. Felipe Castañeda G.. Feel free to connect with me:
- GitHub: https://github.com/lfelipecas
- LinkedIn: https://www.linkedin.com/in/l-felipe-casta%C3%B1eda-g-008027155/

## License

Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)

You are free to:
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material

Under the following terms:
- Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- NonCommercial — You may not use the material for commercial purposes.

No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

For more details, refer to: https://creativecommons.org/licenses/by-nc/4.0/