# 📊 Demographic-Data-Analyzer
A Python program that analyzes demographic data from a CSV file to compute insights such as average age, education distribution, income percentages, and occupation trends.
## ✨ Features
- Computes the number of people by race.
- Calculates the average age of men.
- Computes percentage of people with a Bachelor's degree.
- Calculates income percentages for higher vs. lower education.
- Finds minimum working hours and income distribution.
- Identifies countries with the highest percentage of rich people.
- Determines top occupation in India among high earners.
## 📋 Prerequisites
Before running this project, ensure you have:
- Python 3.8+
- Pandas library
- A CSV file named adult.data.csv inside a data folder
- Basic understanding of Python and data analysis with Pandas
## 🚀 Getting Started
1. Clone the repository:
```bash
git clone https://github.com/your-username/Demographic-Data-Analyzer.git
cd Demographic-Data-Analyzer
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the project:
```bash
python main.py
```
## 🗂️ Project Structure
```
📁 Demographic-Data-Analyzer
├── main.py               # Entry script
├── demographic_data.py   # Core calculations
├── data/
│   └── adult.data.csv    # Dataset
├── requirements.txt
├── test_module.py
└── README.md
```
## 🛠️ Usage
Example usage inside Python:
```python
from demographic_data import calculate_demographic_data

result = calculate_demographic_data(print_data=True)
print(result)

```
Expected output:
```python
{
 'race_count': {'White': 27816, 'Black': 3124, 'Asian-Pac-Islander': 1039, ...}, 
 'average_age_men': 39.4,
 'percentage_bachelors': 16.4,
 'higher_education_rich': 46.5,
 'lower_education_rich': 17.4,
 'min_work_hours': 1,
 'rich_percentage': 10.0,
 'highest_earning_country': 'United-States',
 'highest_earning_country_percentage': 32.3,
 'top_IN_occupation': 'Prof-specialty'
}

```
## ✅ Tests
Run the FreeCodeCamp test suite:
```bash
python test_module.py
```
## 🧠 How It Works
1. The program reads the dataset using Pandas.
2. Computes statistics on age, education, work hours, and income.
3. Groups data by race, country, and occupation to extract insights.
4. Returns results as a Python dictionary.
5. Provides insights ready for analysis or reporting.


## 🤝 Contributing
Contributions are welcome!
1. Fork the repository
2. Create a new feature branch
3. Submit a pull request
Please ensure your code is clean, structured, and well-commented.
## 📝 License
This project is licensed under the MIT license - see the LICENSE file for details. 
## 📞 Support
If you have questions or need help, feel free to:
- Open an issue on this repository  
- Connect with me on LinkedIn: https://www.linkedin.com/in/radwanhefny

Note: The dataset `adult.data.csv` is included in the repo but may not be viewable in GitHub's file preview due to its size.
