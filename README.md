# Customer Satisfaction Analysis Project

## Overview

This project focuses on analyzing customer satisfaction based on their engagement and experience metrics. The dataset contains user activity and network performance data, which have been used to compute scores, perform clustering, and develop insights into user satisfaction.

### Key Objectives:
1. **Engagement Analysis:** Calculate user engagement metrics and assign engagement scores.
2. **Experience Analysis:** Analyze network performance to derive experience scores.
3. **Satisfaction Scoring:** Combine engagement and experience scores to compute overall satisfaction.
4. **Clustering:** Segment users into groups based on engagement and experience using k-means clustering.
5. **Prediction:** Develop a regression model to predict customer satisfaction scores.
6. **Database Integration:** Export final results to a local MySQL database.

---


---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/wendirad/weekTwo.git
   cd customer-satisfaction-analysis
   ```

2. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your MySQL database:
   - Ensure you have MySQL installed and running.
   - Import the `export_satisfaction.sql` file in the `sql` folder into your database:
     ```bash
     mysql -u username -p database_name < sql/export_satisfaction.sql
     ```

---

## Usage

1. **Data Preprocessing**: 
   - Clean and preprocess the dataset to handle missing values and outliers.
   - Run `scripts/preprocess.py`.

2. **Engagement & Experience Analysis**:
   - Calculate engagement and experience scores using k-means clustering.
   - Run `scripts/scoring.py`.

3. **Satisfaction Scoring**:
   - Combine engagement and experience scores to calculate satisfaction scores.

4. **Modeling**:
   - Use regression to predict satisfaction scores.
   - Check the notebook in the `notebooks` folder for the modeling workflow.


## Tools and Technologies

- **Programming Language**: Python
- **Libraries**: pandas, scikit-learn, matplotlib, seaborn, MySQL Connector
- **Database**: MySQL
- **Visualization**: matplotlib, seaborn
- **Version Control**: Git

---

## Contributing

1. Fork the repository.
2. Create a new feature branch:
   ```bash
   git checkout -b feature-branch-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Your message"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch-name
   ```
5. Open a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For questions or contributions, reach out to:
- **Name**: Wendirad Demelash
- **Email**: wendiradame@gmail.com
- **GitHub**: [wendirad](https://github.com/wendirad)
```

Feel free to adjust the content based on your specific project details!
