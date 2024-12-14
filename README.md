# Interactive ML Model Explanation Tool

A backend service that allows users to upload machine learning models and receive interactive explanations of model decisions. Built using Python, Flask, and SHAP.

## Features
- Upload machine learning models securely.
- Generate explanations using SHAP.
- RESTful API endpoints for integration.

## Quick Start
1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd interactive-ml-explainer
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the server:
   ```bash
   python main.py
   ```

4. Test API endpoints:
   - Upload model: `/upload`
   - Explain model: `/explain`

## Dependencies
- Flask: Web framework for the API.
- SHAP: Model explanation library.
- joblib: For saving and loading models.
- numpy: Array manipulation library.

## Contributions
Feel free to open issues and submit pull requests.

## License
MIT