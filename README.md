<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Customer Retention Prediction System</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:Arial, Helvetica, sans-serif;
        }

        body{
            background:#f4f7fb;
            color:#222;
            line-height:1.7;
        }

        .container{
            width:90%;
            max-width:1200px;
            margin:auto;
            padding:40px 0;
        }

        h1,h2,h3{
            color:#0d47a1;
            margin-bottom:15px;
        }

        h1{
            font-size:42px;
            text-align:center;
            margin-bottom:20px;
        }

        p{
            margin-bottom:15px;
        }

        .hero{
            background:white;
            padding:40px;
            border-radius:20px;
            box-shadow:0 5px 20px rgba(0,0,0,0.1);
            margin-bottom:40px;
        }

        .section{
            background:white;
            padding:30px;
            margin-bottom:30px;
            border-radius:18px;
            box-shadow:0 4px 15px rgba(0,0,0,0.08);
        }

        ul{
            margin-left:20px;
            margin-top:10px;
        }

        li{
            margin-bottom:10px;
        }

        table{
            width:100%;
            border-collapse:collapse;
            margin-top:20px;
        }

        table th{
            background:#0d47a1;
            color:white;
            padding:12px;
        }

        table td{
            border:1px solid #ddd;
            padding:12px;
        }

        pre{
            background:#1e1e1e;
            color:#00ff88;
            padding:20px;
            border-radius:10px;
            overflow-x:auto;
            margin-top:15px;
        }

        .badge{
            display:inline-block;
            background:#0d47a1;
            color:white;
            padding:8px 15px;
            border-radius:30px;
            margin:5px;
            font-size:14px;
        }

        .footer{
            text-align:center;
            padding:30px;
            color:#666;
        }

        .highlight{
            color:#1565c0;
            font-weight:bold;
        }
    </style>
</head>

<body>

<div class="container">

    <!-- HERO SECTION -->
    <div class="hero">

        <h1>🚀 Customer Retention Prediction System</h1>

        <p>
            A Machine Learning powered 
            <span class="highlight">Customer Churn Prediction Web Application</span>
            built using Flask, Scikit-Learn, and Machine Learning models 
            to predict whether a telecom customer is likely to stay or leave.
        </p>

        <div>
            <span class="badge">Python</span>
            <span class="badge">Flask</span>
            <span class="badge">Machine Learning</span>
            <span class="badge">Scikit-Learn</span>
            <span class="badge">HTML/CSS</span>
        </div>

    </div>

    <!-- PROJECT OVERVIEW -->
    <div class="section">

        <h2>📌 Project Overview</h2>

        <p>
            Customer churn is one of the biggest challenges for telecom companies.
            This project helps businesses predict customer retention using customer
            behavior and service usage data.
        </p>

        <ul>
            <li>✅ Takes customer information as input</li>
            <li>✅ Processes data using ML preprocessing pipelines</li>
            <li>✅ Predicts customer churn probability</li>
            <li>✅ Displays STAY or LEAVE prediction</li>
        </ul>

    </div>

    <!-- PROJECT STRUCTURE -->
    <div class="section">

        <h2>📂 Project Structure</h2>

<pre>
Customer_Retention_Prediction_System/
│
├── .venv/
├── logs/
├── templates/
│   └── index.html
│
├── app.py
├── main.py
├── All_Models.py
├── feature_scaling.py
├── handle_missing_values.py
├── filter_methods.py
├── logging_code.py
├── var_out.py
├── Categorical_to_num.py
│
├── Model.pkl
├── Normalizer.pkl
│
├── requirements.txt
├── Procfile
│
├── Churn_fs.csv
├── Churn_updated.csv
├── Churn_Cat_to_num.csv
├── Telco-Customer-Churn.csv
│
└── README.md
</pre>

    </div>

    <!-- FEATURES -->
    <div class="section">

        <h2>✨ Features</h2>

        <ul>
            <li>✅ Customer Churn Prediction</li>
            <li>✅ Beautiful Flask Web Interface</li>
            <li>✅ Data Preprocessing Pipeline</li>
            <li>✅ Feature Engineering</li>
            <li>✅ Missing Value Handling</li>
            <li>✅ Feature Scaling</li>
            <li>✅ Probability-Based Prediction</li>
            <li>✅ Health Check API</li>
            <li>✅ ML Model Integration</li>
            <li>✅ Deployment Ready</li>
        </ul>

    </div>

    <!-- WORKFLOW -->
    <div class="section">

        <h2>🧠 Machine Learning Workflow</h2>

        <h3>1️⃣ Data Collection</h3>
        <p>Telecom Customer Churn Dataset</p>

        <h3>2️⃣ Data Preprocessing</h3>
        <ul>
            <li>Missing Value Handling</li>
            <li>Outlier Treatment</li>
            <li>Feature Scaling</li>
            <li>Categorical Encoding</li>
        </ul>

        <h3>3️⃣ Feature Engineering</h3>
        <ul>
            <li>Tenure</li>
            <li>Monthly Charges</li>
            <li>Total Charges</li>
            <li>Internet Services</li>
            <li>Contract Type</li>
            <li>Streaming Services</li>
        </ul>

        <h3>4️⃣ Model Training</h3>

<pre>
pickle.dump(model, open('Model.pkl', 'wb'))
pickle.dump(normalizer, open('Normalizer.pkl', 'wb'))
</pre>

    </div>

    <!-- TECHNOLOGIES -->
    <div class="section">

        <h2>⚙️ Technologies Used</h2>

        <table>
            <tr>
                <th>Technology</th>
                <th>Purpose</th>
            </tr>

            <tr>
                <td>Python</td>
                <td>Programming Language</td>
            </tr>

            <tr>
                <td>Flask</td>
                <td>Web Framework</td>
            </tr>

            <tr>
                <td>Pandas</td>
                <td>Data Processing</td>
            </tr>

            <tr>
                <td>Scikit-Learn</td>
                <td>Machine Learning</td>
            </tr>

            <tr>
                <td>HTML/CSS</td>
                <td>Frontend Design</td>
            </tr>

            <tr>
                <td>Pickle</td>
                <td>Model Serialization</td>
            </tr>
        </table>

    </div>

    <!-- FLASK FLOW -->
    <div class="section">

        <h2>🔥 Flask Application Flow</h2>

<pre>
User Input
    ↓
HTML Form
    ↓
Flask Backend
    ↓
Feature Processing
    ↓
Normalization
    ↓
Model Prediction
    ↓
Result Display
</pre>

    </div>

    <!-- PREDICTION -->
    <div class="section">

        <h2>📊 Prediction Logic</h2>

        <p>The model predicts:</p>

        <ul>
            <li>✅ Customer Will STAY</li>
            <li>⚠️ Customer Will LEAVE</li>
        </ul>

        <p>
            Based on churn probability threshold and customer service data.
        </p>

    </div>

    <!-- INSTALLATION -->
    <div class="section">

        <h2>▶️ Installation & Setup</h2>

        <h3>1️⃣ Clone Repository</h3>

<pre>
git clone https://github.com/your-username/customer-retention-prediction-system.git
</pre>

        <h3>2️⃣ Navigate to Project</h3>

<pre>
cd customer-retention-prediction-system
</pre>

        <h3>3️⃣ Create Virtual Environment</h3>

<pre>
python -m venv .venv
</pre>

        <h3>4️⃣ Activate Environment</h3>

<pre>
.venv\Scripts\activate
</pre>

        <h3>5️⃣ Install Dependencies</h3>

<pre>
pip install -r requirements.txt
</pre>

        <h3>6️⃣ Run Flask App</h3>

<pre>
python app.py
</pre>

    </div>

    <!-- APPLICATION URL -->
    <div class="section">

        <h2>🌐 Application URLs</h2>

        <table>
            <tr>
                <th>Service</th>
                <th>URL</th>
            </tr>

            <tr>
                <td>Home</td>
                <td>http://127.0.0.1:5000</td>
            </tr>

            <tr>
                <td>Health Check</td>
                <td>http://127.0.0.1:5000/health</td>
            </tr>
        </table>

    </div>

    <!-- FUTURE -->
    <div class="section">

        <h2>🚀 Future Improvements</h2>

        <ul>
            <li>Deep Learning Integration</li>
            <li>Real-Time Dashboard</li>
            <li>Database Support</li>
            <li>Docker Deployment</li>
            <li>REST API</li>
            <li>Explainable AI</li>
        </ul>

    </div>

    <!-- AUTHOR -->
    <div class="section">

        <h2>👨‍💻 Author</h2>

        <p>
            <strong>Sachin Muskudi</strong>
        </p>

        <p>
            Data Science Intern passionate about:
        </p>

        <ul>
            <li>Machine Learning</li>
            <li>Deep Learning</li>
            <li>NLP</li>
            <li>Generative AI</li>
            <li>Agentic AI</li>
            <li>Multimodal AI</li>
        </ul>

    </div>

    <!-- GITIGNORE -->
    <div class="section">

        <h2>⭐ .gitignore</h2>

<pre>
.venv/
__pycache__/
*.pyc
logs/
</pre>

    </div>

    <!-- FOOTER -->
    <div class="footer">

        <h3>🏆 Customer Retention Prediction System</h3>

        <p>
            End-to-End Machine Learning Project with Flask Deployment
        </p>

    </div>

</div>

</body>
</html>
