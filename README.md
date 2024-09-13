# Customer Segmentation and Recommendation System

This project presents a strategic approach combining customer segmentation with a recommendation system to drive sales and elevate customer satisfaction. We utilized K-Means clustering to segment customers and applied Neural Collaborative Filtering (NCF) to provide personalized recommendations based on purchasing behaviors.

## Project Overview

- **Customer Segmentation**: K-Means clustering was used to identify different customer groups based on their purchasing behaviors using RFM metrics (Recency, Frequency, Monetary).
- **Recommendation System**: A Neural Collaborative Filtering (NCF) model was implemented to provide personalized recommendations for each customer segment. The system captures user-item interactions to predict future purchase preferences.
- **Tech Stack**: Python, Pandas, Scikit-learn, PyTorch, Matplotlib

## Dataset

This project uses the [Online Retail II Dataset](https://archive.ics.uci.edu/dataset/502/online+retail+ii), originally provided by the UCI Machine Learning Repository. The dataset contains transactions from a UK-based online retail store during 2009-2011. All credit for the dataset goes to the original author(s).

### Dataset Citation:
> Chen, D. (2012). Online Retail II Dataset. UCI Machine Learning Repository. https://archive.ics.uci.edu/dataset/502/online+retail+ii

## File Structure

- **`SMM768_Code_segmentation_and_recommendation_system.ipynb`**: The Jupyter notebook containing the code for customer segmentation and the recommendation system.
- **`SMM768_RawatNikhil_Report.pdf`**: A detailed report discussing the methodology, model performance, and results.
- **`SMM768_Code_segmentation_and_recommendation_system.pdf`**: A PDF version of the Jupyter notebook for easy viewing.

## Installation

To run the project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Customer-Segmentation-and-Recommendation-System.git
    cd Customer-Segmentation-and-Recommendation-System
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook:
    ```bash
    jupyter notebook
    ```

## Usage

You can run the Jupyter notebook to see the customer segmentation and recommendation system in action. Follow the steps provided in the notebook to load the dataset and execute the models.

## Acknowledgements

The project was developed as part of an MSc course in Business Analytics.

## License

MIT License

