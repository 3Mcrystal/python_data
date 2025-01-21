# COVID Data Analysis and Visualization

This project provides tools to analyze and visualize COVID-19 data using Streamlit, Pandas, Matplotlib, and Plotly.

## Installation

1. Clone the repository:
    ```sh
    git clone git@github.com:3Mcrystal/python_data.git
    cd python_data
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Launch the Project

To start the Streamlit application, run the following command:
```sh
streamlit run app.py
```

## Deploy Project 
https://pythondata-tzr8jen4gvxr3fvahlwurq.streamlit.app/

## Diagram

            +----------------+
            |     app.py     |
            +----------------+
                     |
       +---------------------------+
       |        src/               |
       +---------------------------+
       | file_reader.py  analyzer.py|
       | visualizer.py              |
       +---------------------------+
                     |
            +----------------+
            |      data/      |
            +----------------+
