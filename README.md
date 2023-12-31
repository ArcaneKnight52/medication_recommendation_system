# Medicine Recommendation System

This recommendation system suggests alternative or substitute medicines based on search results. Its primary goal is to provide recommendations for replacing a searched medicine.

## How to Run the Application Locally

1. Clone this GitHub repository.
2. Extract the contents of **pickle-files.rar** to obtain the "similarity.pkl" and "medicine_dict.pkl" pickle files.
3. Download and install the PyCharm IDE. Open the application folder in PyCharm.
4. Import the necessary libraries: *streamlit*, *pandas*, and *pickle*.
5. Open a terminal.
6. Run the command: `streamlit run app.py`

> **Note:** If you encounter the error "*streamlit is not recognized as an internal or external command*" even after importing all the libraries, follow these steps:
> 1. Create a new Python project.
> 2. Import the required libraries (*streamlit*, *pandas*, and *pickle*).
> 3. Include the `css` and `images` folders along with the extracted pickle files.

---

## Dataset
You can access the dataset [here](https://www.kaggle.com/code/mpwolke/medicine-recommendation/data) on Kaggle.
