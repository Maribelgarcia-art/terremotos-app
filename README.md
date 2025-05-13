📊 Features

Comprehensive Data Analysis: Explore seismic events with multiple visualization options
Interactive Filters: Filter data by date, magnitude, depth, event type, and region
Geographic Analysis: View events on interactive maps with cluster detection
Temporal Analysis: Analyze patterns across time (daily, weekly, hourly)
Advanced Statistics: Correlation analysis, regional comparisons, and magnitude distribution
Responsive Design: Built with a user-friendly interface that works on various screen sizes

📋 Dashboard Sections
1. General Summary

Overview metrics and statistics
Magnitude and depth distributions
Relationship between magnitude and depth
Top regions with seismic activity

2. Geographic Analysis

Interactive event map
Heat map of activity density
DBSCAN cluster analysis with parameter adjustment
Detailed cluster information and statistics

3. Temporal Analysis

Daily evolution of seismic activity
Weekly patterns visualization
Hourly distribution analysis
Heat maps for temporal patterns

4. Advanced Analysis

Correlation matrix between seismic parameters
Regional magnitude comparisons
Custom variable comparisons with trend lines
Statistics by magnitude category

🚀 Installation
Prerequisites

Python 3.7+
pip package manager

Setup

Clone the repository:

bashgit clone https://github.com/your-username/seismic-dashboard.git
cd seismic-dashboard

Create a virtual environment (recommended):

bashpython -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install required packages:

bashpip install -r requirements.txt

Download seismic data:

Option 1: Use the included sample data file
Option 2: Download the latest "all_month.csv" from the USGS Earthquake Feed


Update the data path in the application:

Open app.py
Modify the path in the load_data() function to point to your data file



💻 Usage

Start the Streamlit application:

bashstreamlit run app.py

Open your web browser and navigate to:

http://localhost:8501

Use the sidebar filters to customize your analysis:

Select date range
Adjust magnitude range
Set depth parameters
Filter by event type or region


Explore the different tabs to analyze seismic data from various perspectives

📊 Data Source
This dashboard uses earthquake data in CSV format from the USGS Earthquake Hazards Program. The data includes:

Event time and location
Magnitude and depth
Geographic coordinates
Event type and other metadata

🛠️ Technologies Used

Streamlit: Web application framework
Pandas: Data manipulation and analysis
NumPy: Numerical computing
Plotly Express: Interactive visualizations
Matplotlib: Static visualizations
Scikit-learn: Machine learning for cluster analysis (DBSCAN)

📝 Requirements
Required Python packages:
streamlit>=1.22.0
pandas>=1.5.0
numpy>=1.23.0
plotly>=5.10.0
matplotlib>=3.5.0
scikit-learn>=1.0.0
🔄 Future Improvements

 Add predictive analytics capabilities
 Implement real-time data streaming
 Enhance cluster analysis with more algorithms
 Add export options for visualizations
 Implement user accounts and saved preferences

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

Fork the repository
Create your feature branch (git checkout -b feature/amazing-feature)
Commit your changes (git commit -m 'Add some amazing feature')
Push to the branch (git push origin feature/amazing-feature)
Open a Pull Request

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
👥 Acknowledgments

Earthquake data provided by the USGS Earthquake Hazards Program
Built with Streamlit's excellent framework for data applications
Inspired by the need for accessible seismic data visualization tools
