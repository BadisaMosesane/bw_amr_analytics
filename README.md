# Antimicrobial Resistance Analytics Dashboard for Botswana

**Overview**

This Plotly Dash application is designed to visualize and analyze antimicrobial resistance (AMR) trends in Botswana. It leverages data on antibiotic susceptibility testing (AST) results to provide insights into the prevalence of AMR, the emergence of resistant strains, and the effectiveness of different antibiotics within Botswana health facilities(hospitals and labs).

**Key Features**

* **Interactive Visualizations:**
    - Time-series plots to track changes in AMR rates over time.
    - Bar charts to compare AMR rates across different bacterial species and antibiotics.
    - Geographic maps to visualize spatial patterns of AMR.
    - Heatmaps to identify the most critical drug-resistance combinations.
* **Data Exploration:**
    - Filter and drill down into specific datasets based on various parameters (e.g., bacterial species, antibiotic class, geographic region).
    - Customize visualizations to highlight key trends and insights.
* **Data Insights:**
    - Identify emerging trends in AMR.
    - Monitor the effectiveness of antibiotic stewardship programs.
    - Inform evidence-based decision-making for public health officials and healthcare providers.

**Getting Started**

1. **Prerequisites:**
   - Python (version 3.6 or later)
   - Pip (package installer for Python)
   - Plotly Dash 2.4 or latest
   - Pandas
   - NumPy
   - Other necessary libraries (listed in `requirements.txt`)

2. **Installation:**
   - Clone this repository:
     ```bash
     git clone https://github.com/BadisaMosesane/bw_amr_analytics.git
     ```
   - Install dependencies:
     ```bash
     cd bw_amr_analytics
     pip install -r requirements.txt
     ```

3. **Data Preparation:**
   - Prepare your AMR data in a suitable format (e.g., CSV, Excel).
   - Ensure data consistency and completeness.
   - Clean and preprocess the data as needed.

4. **Running the App:**
   - Modify the data loading and preprocessing steps in the `app.py` file to accommodate your specific data format.
   - Run the app:
     ```bash
     python app.py
     ```
   - Access the dashboard in your web browser at the specified address (usually `http://127.0.0.1:8050/`).

**Data Sources**

* **Botswana Health Information System (BHIS):** Central repository of health data in Botswana.
* **National Antimicrobial Resistance Surveillance System (NARSS):** Monitors AMR trends and provides data for analysis.

**Customization**

* **Visualizations:** Modify the code in the `app.py` file to create new visualizations or customize existing ones.
* **Data Sources:** Integrate additional data sources to expand the scope of analysis.
* **User Interface:** Customize the layout and design of the dashboard to match your preferences.

**Future Improvements**

* **Machine Learning Integration:** Incorporate machine learning models to predict future AMR trends and identify high-risk populations.
* **Real-time Data Integration:** Enable real-time updates of the dashboard with the latest data.
* **User Authentication and Authorization:** Implement user authentication and authorization to control access to sensitive data and functionalities.


## Installation and Usage

First, install all dependencies listed in requirements.txt

* Clone the repo and cd into the bw_amr_analytics directory

* $ pip install -r requirements.txt

Run app.py script to launch a local Dash server to host the Dash app. 

* python app.py

* A link will appear in your console; Navigate to http://0.0.0.0:8050 on a browser tab to see the results.



## Issues
* improve Detection  accurary
* train on more AMR data


## Licensing**
[Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)


## Contributing** 
We thank the work done by Plotly Dash https://github.com/plotly and referenced most of the work here.
Send us a PR at https://github.com/BadisaMosesane/bw_amr_analytics

**Contact**

For any questions or issues, please contact:

* **Name:** Badisa Mosesane
* **Email:** bmosesane@gmail.com



