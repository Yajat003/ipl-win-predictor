# IPL Win Probability Prediction

This project aims to predict the outcome of T20 cricket matches using machine learning techniques. By analyzing various match-related features such as:
- batting team, 
- bowling team, 
- venue (city), and
- in-game statistics (like runs, wickets, overs), 
the model learns patterns that influence the match results. 
The pipeline includes data preprocessing using `OneHotEncoder` for categorical variables and a machine learning model to make real-time predictions.


## Setup Instructions

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Yajat003/ipl-win-predictor.git
    cd ipl-win-predictor
    ```

2. **Create a virtual environment:**

    ```bash
    conda create -p virtual_environment_name python==python_version -y
    ```
    
3. **Activate virtual Environment:**

    ```bash
    conda activate virtual_environment_name 
    ```        

4. **Install required packages:**

    ```bash
    pip install -r requirements.txt
    ```

5. **Start the application:**

    ```bash
    streamlit run app.py
    ```