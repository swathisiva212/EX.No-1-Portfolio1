Ex01 Portfolio
Date:
AIM
To create a Portfolio using HTML and CSS.

ALGORITHM
STEP 1
Create an HTML file (index.html)

STEP 2
Create a CSS file (style.css)

STEP 3
Include a navigation bar with links to different sections.

STEP 4
Add structured sections for introduction, about, projects, and contact details.

STEP 5
Define global styles for fonts, colors, and layout.

STEP 6
Style the header, navigation bar, and sections.

STEP 7
Use Flexbox or CSS Grid for layout design.

STEP 8
Add hover effects and transitions for interactivity.

STEP 9
Add Images and Media.

STEP 10
Use optimized images for a professional look.

STEP 11
Open the HTML file in a browser to check layout and functionality.

STEP 12
Fix styling issues and refine content placement.

STEP 13
Deploy the Portfolio.

STEP 14
Upload to GitHub Pages for free hosting.

PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multi-Page Resume</title>
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: #f4f4f4;
        }
        .resume {
            width: 800px;
            background: white;
            margin: 20px auto;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.2);
            border-radius: 10px;
            padding: 20px;
            page-break-after: always;
            display: flex;
        }
        .left {
            width: 30%;
            background: #2a5298;
            color: white;
            padding: 20px;
            text-align: center;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .right {
            width: 70%;
            padding: 20px;
        }
        .left img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            border: 3px solid white;
            margin-bottom: 10px;
        }
        .section {
            margin-bottom: 20px;
        }
        .section h2 {
            color: #2a5298;
            border-bottom: 2px solid #2a5298;
            padding-bottom: 5px;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <div class="resume">
        <div class="left">
            <img src="profile.jpg" alt="Profile Image">
            <h2>swathi</h2>
            <p>Data scientist</p>
            <ul>
                <li>Email: swathi12@gmail.com</li>
                <li>Phone: (123) 456-7890</li>
                <li>LinkedIn: linkedin.com/in/swathi</li>
                <li>GitHub: github.com/swathi</li>
            </ul>
        </div>
        <div class="right">
            <div class="section">
                <h2>Summary</h2>
                <p> Data Scientist with [3] years of experience in analyzing data, building machine learning models, and delivering actionable insights to solve business problems. Skilled in data analysis, statistical modeling, and data visualization using Python, SQL, and machine learning frameworks.</p>

                </p>
            </div>
        </div>
    </div>
    <div class="resume">
    <div class="section">
        <h2>Skills</h2>
        <ul>
        <li>Programming: Python, R, SQL</li>
         <li>Machine Learning: Linear Regression, Decision Trees, Random Forest, Neural Networks</li> 
        <li>TensorFlow, Scikit-learn, Pandas, NumPy.</li>
        <li>Visualization: Power BI, Tableau, Matplotlib, Seaborn</li> 
         <li>Databases: MySQL, MongoDB</li>
        <li>Cloud Platforms: AWS, Google Cloud</li>
        </ul> 
    </div> 
    </div>  
    <div class="resume">
        <div class="section">
            <h2>Experience</h2>
            <p><strong>Data scientist</strong> - ABC Corp[3 years]</p>
            <p>Analyzed large datasets using Python and SQL to extract actionable insights Developed machine learning models for customer segmentation and sales forecasting Presented findings through interactive dashboards using Tableau and Power BI</p>
            <p><strong>Data analyst</strong>ABC Corp[1 years]</p>
            <p>Performed data cleaning and exploratory data analysis Created automated reports and dashboards to track key performance metrics Used SQL queries to extract and manipulate data from relational databases</p>
                
                
        </div>
    </div>
    
    <div class="resume">
        <div class="section">
            <h2>Education</h2>
            <p><strong>Bachelor of CSE</strong> - XYZ University (2026-2027)</p>
            <p>Studied core computer science application ,python libraries ,excel, SQL.</p>
            <p><strong>Master's in Computer Science</strong> - ABC University (2028 - 2029)</p>
            <p>Specialized in  data analysis ,visualization,communication ,problem solving and database.</p>
        </div>
    </div>
    
    <div class="resume">
        <div class="section">
            <h2>Projects</h2>
            <p><strong>Python,tensor flow</strong> - Sentiment Analysis using NLP</p>
            <p><strong>scikit-learn</strong> -Customer Churn Prediction Model</p>
            <p><strong>Tableau,SQL</strong> - Sales Forecasting Dashboard </p>
            <p><strong>powerBI</strong> - Sales performance Dashboard</p>
        </div>
    </div>
    
    <div class="resume">
        <div class="section">
            <h2>Certifications</h2>
            <ul>
                <li>Data Science Certification</li>
                <li>Machine Learning Certification </li>
                <li>SQL for Data Science</li>
                <li>powerBI Dashboard Certification </li>
            </ul>
        </div>
        </div>
</body>
</html>
```
OUTPUT:

RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.

