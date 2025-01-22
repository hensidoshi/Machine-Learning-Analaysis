# Machine Learning Analysis

This project is a web-based application that allows users to upload a dataset, perform machine learning analysis, and compare the accuracy of well-known algorithms. The application is built using Flask, with a modern user interface and robust backend functionality.

## Features
- Upload datasets in CSV format.
- Preprocess data (handle missing values, encode non-numeric data, and standardize features).
- Compare multiple machine learning algorithms using K-Fold cross-validation.
- Display results dynamically in an intuitive web interface.
- Highlight the best-performing model.

## Algorithms Compared
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Support Vector Machine (SVM)
5. K-Nearest Neighbors (k-NN)
6. Naive Bayes Classifier
7. Gradient Boosting Classifier

## Project Structure
```
Machine-Learning-Analaysis/
├── app.py                # Main Flask application
├── templates/            # HTML templates for the web interface
│   ├── index.html        # Upload form page
│   └── results.html      # Results display page
├── uploads/              # Temporary folder for uploaded datasets
└── README.md             # Project documentation (this file)
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/hensidoshi/Machine-Learning-Analaysis.git
   cd Machine-Learning-Analaysis
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

   If `requirements.txt` is missing, install the following manually:
   ```bash
   pip install flask pandas numpy scikit-learn
   ```

## Usage
1. Start the Flask application:
   ```bash
   python app.py
   ```

2. Open a web browser and navigate to:
   [http://127.0.0.1:5000](http://127.0.0.1:5000)

3. Upload your dataset (CSV format) with a target column named `Outcome`.

4. View the results, including model accuracies and the best-performing algorithm.

## Example Datasets
Make sure your dataset includes a target column (e.g., `Outcome`, `Target`, `Label`) and is in CSV format. An example diabetes dataset can be used for testing.

## Screenshots
### Homepage
![Homepage](https://via.placeholder.com/800x400?text=Homepage)

### Results Page
![Results Page](https://via.placeholder.com/800x400?text=Results+Page)

## Contributing
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For any inquiries, reach out via:
- Email: [hensidoshi711@gmail.com](mailto:hensidoshi711@gmail.com)
- GitHub: [github.com/hensidoshi](https://github.com/hensidoshi)
