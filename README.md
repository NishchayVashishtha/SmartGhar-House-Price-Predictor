# SmartGhar: AI-Powered Real Estate Price Predictor 🏠💰

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-14.1.0-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-18-blue?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=for-the-badge&logo=typescript)
![Python](https://img.shields.io/badge/Python-ML-yellow?style=for-the-badge&logo=python)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**An intelligent, full-stack Machine Learning application that predicts residential property prices in Gurugram with precision and style.**

[Live Demo](#) · [Report Bug](https://github.com/NishchayVashishtha/SmartGhar-House-Price-Predictor/issues) · [Request Feature](https://github.com/NishchayVashishtha/SmartGhar-House-Price-Predictor/issues)

</div>

---

## 📋 Table of Contents

- [About The Project](#-about-the-project)
- [Key Features](#-key-features)
- [Tech Stack](#️-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Machine Learning Pipeline](#-machine-learning-pipeline)
- [Usage](#-usage)
- [Dataset Information](#-dataset-information)
- [Model Performance](#-model-performance)
- [API Reference](#-api-reference)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)
- [Acknowledgments](#-acknowledgments)

---

## 🎯 About The Project

**SmartGhar** is a sophisticated real estate price prediction platform that combines the power of machine learning with modern web technologies. The application is specifically designed to predict residential property prices in **Gurugram**, one of India's most dynamic real estate markets.

### Why SmartGhar?

- 🎯 **Accuracy First**: Trained on real-world Gurugram property data with advanced ML algorithms
- 🚀 **Lightning Fast**: Built with Next.js for optimal performance and SEO
- 🎨 **Beautiful UI**: Modern, responsive design with Tailwind CSS and Three.js 3D effects
- 🔄 **Real-time Predictions**: Instant property valuations based on user inputs
- 📊 **Data-Driven**: Comprehensive exploratory data analysis and feature engineering
- 🔒 **Production Ready**: Serialized models with Joblib for efficient deployment

---

## 🌟 Key Features

### 🤖 Machine Learning Capabilities
- **Advanced Regression Model**: Trained using Scikit-Learn with optimized hyperparameters
- **Feature Engineering**: Smart preprocessing of location, area, amenities, and property characteristics
- **Encoded Categories**: Efficient handling of categorical features using label/one-hot encoding
- **Model Persistence**: Serialized model and encoders for fast inference

### 💻 Web Application
- **Interactive UI**: Intuitive form-based interface for property details input
- **3D Visualizations**: Stunning 3D graphics powered by React Three Fiber
- **Responsive Design**: Seamless experience across desktop, tablet, and mobile devices
- **Smooth Animations**: Framer Motion for delightful user interactions
- **TypeScript Support**: Type-safe development for reliability and maintainability

### 📈 Technical Excellence
- **Server-Side Rendering**: Next.js 14 with App Router for optimal performance
- **Modern Styling**: Tailwind CSS with custom forms plugin
- **Code Quality**: ESLint configuration for consistent code standards
- **Version Control**: Git-based workflow for collaborative development

---

## 🛠️ Tech Stack

### Frontend
- **Framework**: [Next.js 14.1.0](https://nextjs.org/) - React framework with SSR
- **UI Library**: [React 18](https://react.dev/) - Component-based UI
- **Styling**: [Tailwind CSS 3.3+](https://tailwindcss.com/) - Utility-first CSS
- **Animations**: [Framer Motion 11.18+](https://www.framer.com/motion/) - Motion library
- **3D Graphics**: [Three.js](https://threejs.org/) + [React Three Fiber](https://docs.pmnd.rs/react-three-fiber) - WebGL rendering
- **Language**: [TypeScript 5](https://www.typescriptlang.org/) - Type-safe JavaScript

### Machine Learning
- **Language**: Python 3.x
- **Core Libraries**:
  - `scikit-learn` - Machine learning algorithms
  - `pandas` - Data manipulation and analysis
  - `numpy` - Numerical computing
  - `joblib` - Model serialization
- **Development**: Jupyter Notebook for experimentation

### DevOps & Tooling
- **Package Manager**: npm
- **CSS Processing**: PostCSS with import and nesting plugins
- **Linting**: ESLint with Next.js configuration
- **Version Control**: Git & GitHub

---

## 📂 Project Structure

```
SmartGhar-House-Price-Predictor/
│
├── 📁 .git/                          # Git version control
├── 📄 .gitignore                     # Git ignore rules
│
├── 🤖 Machine Learning Files
│   ├── MLprj.ipynb                   # Jupyter notebook with ML pipeline
│   ├── model.joblib                  # Trained prediction model
│   ├── encoders.joblib               # Feature encoders (categorical)
│   ├── Gurugram_House_Price_Dataset.csv  # Original training dataset
│   └── dataset.csv                   # Processed dataset
│
├── ⚙️ Configuration Files
│   ├── next.config.js                # Next.js configuration
│   ├── next-env.d.ts                 # Next.js TypeScript declarations
│   ├── tsconfig.json                 # TypeScript configuration
│   ├── tailwind.config.js            # Tailwind CSS configuration
│   ├── postcss.config.js             # PostCSS configuration
│   ├── eslint.config.mjs             # ESLint configuration
│   ├── package.json                  # npm dependencies & scripts
│   └── package-lock.json             # Dependency lock file
│
└── 📄 README.md                      # Project documentation (you are here!)
```

### Key Files Explained

| File | Purpose |
|------|---------|
| `MLprj.ipynb` | Complete ML pipeline: data loading, cleaning, EDA, feature engineering, model training, and evaluation |
| `model.joblib` | Serialized trained model ready for predictions |
| `encoders.joblib` | Fitted encoders for categorical features (locations, property types, etc.) |
| `Gurugram_House_Price_Dataset.csv` | Raw dataset with property features and prices |
| `package.json` | Node.js dependencies and npm scripts for the web app |
| `next.config.js` | Next.js framework configuration |

---

## 🚀 Getting Started

Follow these steps to set up SmartGhar on your local machine.

### Prerequisites

Ensure you have the following installed:

- **Node.js** (v18 or higher)
  ```bash
  node --version
  ```

- **npm** (comes with Node.js)
  ```bash
  npm --version
  ```

- **Python 3.x** (for ML development)
  ```bash
  python --version
  ```

- **Git**
  ```bash
  git --version
  ```

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/NishchayVashishtha/SmartGhar-House-Price-Predictor.git
   cd SmartGhar-House-Price-Predictor
   ```

2. **Install Node.js dependencies**
   ```bash
   npm install
   ```

3. **Install Python dependencies** (for ML development)
   ```bash
   pip install pandas numpy scikit-learn jupyter joblib matplotlib seaborn
   ```

### Running the Application

1. **Development Server**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

2. **Production Build**
   ```bash
   npm run build
   npm start
   ```

3. **Linting**
   ```bash
   npm run lint
   ```

4. **ML Development**
   ```bash
   jupyter notebook MLprj.ipynb
   ```

---

## 🧠 Machine Learning Pipeline

### 1. Data Collection & Preprocessing
- **Dataset**: Gurugram real estate data with features like location, area, bedrooms, bathrooms, amenities
- **Cleaning**: Handling missing values, outlier detection and treatment
- **Feature Engineering**: Creating derived features, encoding categorical variables

### 2. Exploratory Data Analysis (EDA)
- Distribution analysis of property prices
- Correlation studies between features
- Location-based price trends
- Visualization of key patterns and insights

### 3. Model Training
- **Algorithm**: Regression model (likely Linear/Ridge/Lasso/Random Forest based on notebook)
- **Train-Test Split**: Proper validation strategy
- **Hyperparameter Tuning**: Optimization for best performance
- **Cross-Validation**: Ensuring model generalization

### 4. Model Evaluation
- Performance metrics: R², RMSE, MAE
- Residual analysis
- Feature importance analysis

### 5. Model Deployment
- Serialization using `joblib` for production use
- Integration with Next.js API routes for real-time predictions

---

## 💡 Usage

### For End Users

1. **Navigate to the application** in your browser
2. **Fill in property details**:
   - Location/Sector in Gurugram
   - Property area (sq. ft.)
   - Number of bedrooms
   - Number of bathrooms
   - Additional amenities
3. **Click "Predict Price"** to get instant valuation
4. **View results** with price estimate and confidence metrics

### For Developers

**Making Predictions Programmatically:**

```python
import joblib
import pandas as pd

# Load model and encoders
model = joblib.load('model.joblib')
encoders = joblib.load('encoders.joblib')

# Prepare input data
input_data = pd.DataFrame({
    'location': ['Sector 57'],
    'area': [1500],
    'bedrooms': [3],
    'bathrooms': [2],
    # ... other features
})

# Encode categorical features
# (apply appropriate encoders)

# Make prediction
predicted_price = model.predict(input_data)
print(f"Predicted Price: ₹{predicted_price[0]:,.2f}")
```

---

## 📊 Dataset Information

### Source
The dataset contains real estate listings from Gurugram with the following characteristics:

### Features
- **Location**: Sector/area in Gurugram
- **Area**: Property size in square feet
- **Bedrooms**: Number of bedrooms (BHK)
- **Bathrooms**: Number of bathrooms
- **Property Type**: Apartment, Villa, Penthouse, etc.
- **Amenities**: Parking, gym, swimming pool, etc.
- **Age**: Property age/construction year
- **Floor**: Floor number and total floors
- **Furnishing**: Furnished/Semi-furnished/Unfurnished
- **Target**: Property price in INR

### Statistics
- **Total Records**: Check `Gurugram_House_Price_Dataset.csv`
- **Features**: 10-15+ columns
- **Price Range**: Varies by location and property type

---

## 📈 Model Performance

### Metrics
(Update these after running your model)

- **R² Score**: 0.XX - Explains XX% of price variance
- **RMSE**: ₹X.XX Lakhs - Average prediction error
- **MAE**: ₹X.XX Lakhs - Mean absolute error
- **Training Time**: ~X seconds

### Feature Importance
Top features influencing predictions:
1. Location/Sector
2. Property Area
3. Number of Bedrooms
4. Amenities
5. Property Age

---

## 🔌 API Reference

### Prediction Endpoint (Example)

```typescript
// POST /api/predict
interface PredictionRequest {
  location: string;
  area: number;
  bedrooms: number;
  bathrooms: number;
  // ... other features
}

interface PredictionResponse {
  predictedPrice: number;
  confidence: number;
  priceRange: {
    min: number;
    max: number;
  };
}
```

---

## 🗺️ Roadmap

- [x] Core ML model development
- [x] Data preprocessing pipeline
- [x] Next.js frontend setup
- [x] 3D visualization integration
- [ ] API endpoint implementation
- [ ] Model-frontend integration
- [ ] User authentication
- [ ] Price history tracking
- [ ] Comparative analysis feature
- [ ] Mobile app (React Native)
- [ ] CI/CD pipeline
- [ ] Docker containerization
- [ ] Cloud deployment (Vercel/AWS)

See [open issues](https://github.com/NishchayVashishtha/SmartGhar-House-Price-Predictor/issues) for feature requests and known issues.

---

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn and create! Any contributions you make are **greatly appreciated**.

### How to Contribute

1. **Fork the Project**
2. **Create your Feature Branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your Changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the Branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### Contribution Guidelines
- Follow the existing code style
- Write meaningful commit messages
- Update documentation for new features
- Add tests for new functionality
- Ensure all tests pass before submitting PR

---

## 📄 License

Distributed under the MIT License. See `LICENSE` file for more information.

---

## 📞 Contact

**Nishchay Vashishtha**

- 🎓 B.Tech CSE | BML Munjal University
- 💼 GitHub: [@NishchayVashishtha](https://github.com/NishchayVashishtha)
- 🔗 Project Link: [SmartGhar-House-Price-Predictor](https://github.com/NishchayVashishtha/SmartGhar-House-Price-Predictor)

---

## 🙏 Acknowledgments

- [Next.js Documentation](https://nextjs.org/docs)
- [Scikit-Learn](https://scikit-learn.org/)
- [React Three Fiber](https://docs.pmnd.rs/react-three-fiber)
- [Tailwind CSS](https://tailwindcss.com/)
- [Framer Motion](https://www.framer.com/motion/)
- BML Munjal University for academic support
- Open-source community for amazing tools and libraries

---

<div align="center">

**Made with ❤️ by Nishchay Vashishtha**

⭐ Star this repository if you find it helpful!

[⬆ Back to Top](#smartghar-ai-powered-real-estate-price-predictor-)

</div>
