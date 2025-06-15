# 🎬 Netflix EDA Dashboard with Gradio

An interactive Exploratory Data Analysis (EDA) dashboard built using Gradio, allowing users to explore the Netflix Movies and TV Shows dataset. This project demonstrates data loading, cleaning, filtering, and interactive visualization of key trends and distributions within the Netflix catalog.

## ✨ Features

* **File Upload:** Easily upload your `netflix_titles.csv` dataset.
* **Content Type Filtering:** Filter between Movies, TV Shows, or view both.
* **Release Year Range Selection:** Interactively select a range of release years to focus your analysis.
* **Country Filter:** Select multiple countries to analyze content from specific regions.
* **Rating Filter:** Filter content based on its age rating (e.g., TV-MA, PG-13).
* **Genre/Category Filter:** Dive into specific genres (e.g., "Dramas," "Comedies").
* **Dynamic Visualizations:**
    * **Content Type Distribution:** Pie chart showing the proportion of Movies vs. TV Shows.
    * **Top 10 Countries by Content Production:** Bar chart highlighting countries with the most titles.
    * **Content Added Over Time:** Line chart illustrating the yearly trend of titles added to Netflix.
    * **Top 10 Genres/Categories:** Bar chart for the most prevalent genres.
    * **Ratings Distribution:** Bar chart showing the breakdown of content ratings.
    * **Movie Duration Distribution:** Histogram for movie lengths (in minutes).
* **Filtered Data Overview:** Displays a snippet of the dataset based on current filters.

## 🛠️ Technologies Used

* **Python**: The core programming language.
* **Gradio**: For creating the interactive web application interface.
* **Pandas**: For data manipulation, cleaning, and analysis.
* **NumPy**: For numerical operations, especially during data preprocessing.
* **Plotly Express**: For generating interactive and aesthetically pleasing data visualizations.

## 📊 Dataset

The dataset used in this project is `netflix_titles.csv`, which contains information about movies and TV shows available on Netflix as of a certain date.

You can download the original dataset from Kaggle:
[Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)

**Please ensure the `netflix_titles.csv` file is placed in the root directory of this project alongside `app.py` for the application to run correctly.**

## 🚀 How to Run Locally

Follow these steps to set up and run the application on your local machine:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/netflix-gradio-eda.git](https://github.com/YOUR_USERNAME/netflix-gradio-eda.git)
    cd netflix-gradio-eda
    ```
2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    ```
3.  **Activate the virtual environment:**
    * **On Windows:**
        ```bash
        .\venv\Scripts\activate
        ```
    * **On macOS/Linux:**
        ```bash
        source venv/bin/activate
        ```
4.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
5.  **Run the Gradio application:**
    ```bash
    python app.py
    ```
    This will start the Gradio server, and you'll typically see a local URL (e.g., `http://127.0.0.1:7860`) in your terminal. Open this URL in your web browser.

Once deployed, your app will be accessible at:
**[YOUR_HUGGINGFACE_SPACES_LINK]**
(e.g., `https://huggingface.co/spaces/YOUR_USERNAME/netflix-eda-dashboard`)

## 📸 Screenshots
![image](https://github.com/user-attachments/assets/20727042-e8e4-4800-87ae-c4877d0f2572)



## 💡 Future Enhancements

* **Advanced Filtering:** Implement more complex filtering options, such as filtering by director, cast, or description keywords.
* **Statistical Summaries:** Add sections for deeper statistical insights (e.g., mean/median duration by genre, average ratings by country).
* **Comparison Tools:** Allow users to compare distributions or trends between selected categories (e.g., compare movie durations across different ratings).
* **User Feedback:** Implement a simple feedback mechanism within the Gradio app.
* **Download Filtered Data:** Provide an option to download the currently filtered dataset.

---

## ✍️ Author

Suvajit Bhattacharjee - https://www.linkedin.com/in/suvajitbhattacharjee/

---
