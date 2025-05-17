# Ex01 Portfolio
## Date:04.03.2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
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
      flex-direction: row;
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
      border-radius: 10px 0 0 10px;
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

    ul {
      list-style: none;
      padding: 0;
      text-align: left;
    }

    li {
      margin-bottom: 8px;
    }

    .section {
      margin-bottom: 20px;
    }

    .section h2 {
      color: #2a5298;
      margin-bottom: 10px;
      font-size: 22px;
      font-weight: 600;
    }

    p, li {
      font-size: 15px;
      line-height: 1.6;
    }
  </style>
</head>
<body>

  <div class="resume">
    <div class="left">
      <img src="profile.jpg" alt="Profile Image" />
      <h2>SWATHI S</h2>
      <p>Data Scientist</p>
      <ul>
        <li><strong>Email:</strong> swathi12@gmail.com</li>
        <li><strong>Phone:</strong> (123) 456-7890</li>
        <li><strong>LinkedIn:</strong> linkedin.com/in/swathi</li>
        <li><strong>GitHub:</strong> github.com/swathi</li>
      </ul>
    </div>
    <div class="right">
      <div class="section">
        <h2>ABOUT ME</h2>
        <p>Data Scientist with 3 years of experience in analyzing data, building machine learning models, and delivering actionable insights to solve business problems. Skilled in data analysis, statistical modeling, and data visualization using Python, SQL, and machine learning frameworks.</p>
      </div>
    </div>
  </div>

 
  <div class="resume">
    <div class="section">
      <h2>Skills</h2>
      <ul>
        <li><strong>Programming:</strong> Python, R, SQL</li>
        <li><strong>Machine Learning:</strong> Linear Regression, Decision Trees, Random Forest, Neural Networks</li>
        <li><strong>Libraries:</strong> TensorFlow, Scikit-learn, Pandas, NumPy</li>
        <li><strong>Visualization:</strong> Power BI, Tableau, Matplotlib, Seaborn</li>
        <li><strong>Databases:</strong> MySQL, MongoDB</li>
        <li><strong>Cloud Platforms:</strong> AWS, Google Cloud</li>
      </ul>
    </div>
  </div>

  <div class="resume">
    <div class="section">
      <h2>Experience</h2>
      <p><strong>Data Scientist</strong></p>
      <p>Analyzed large datasets using Python and SQL to extract actionable insights. Developed machine learning models for customer segmentation and sales forecasting. Presented findings through interactive dashboards using Tableau and Power BI.</p>

      <p><strong>Data Analyst</strong></p>
      <p>Performed data cleaning and exploratory data analysis. Created automated reports and dashboards to track key performance metrics. Used SQL queries to extract and manipulate data from relational databases.</p>
    </div>
  </div>

  <div class="resume">
    <div class="section">
      <h2>Education</h2>
      <p><strong>Bachelor of CSE</strong> SAVEETHA ENGINEERING COLLEGE (2024-2027)</p>
      <p>Studied core computer science applications,DataScience includes Python libraries, Excel, and SQL.</p>
      <p><strong>Master's in Computer Science</strong> - ABC University (2028–2029)</p>
      <p>Specialized in data analysis, visualization, communication, problem solving, and databases.</p>
    </div>
  </div>

  <div class="resume">
    <div class="section">
      <h2>Projects</h2>
      <p><strong>Python, TensorFlow:</strong> Sentiment Analysis using NLP</p>
      <p><strong>Scikit-learn:</strong> Customer Churn Prediction Model</p>
      <p><strong>Tableau, SQL:</strong> Sales Forecasting Dashboard</p>
      <p><strong>Power BI:</strong> Sales Performance Dashboard</p>
    </div>
  </div>

  <div class="resume">
    <div class="section">
      <h2>Certifications</h2>
      <ul>
        <li>Data Science Certification</li>
        <li>Machine Learning Certification</li>
        <li>SQL for Data Science</li>
        <li>Power BI Dashboard Certification</li>
      </ul>
    </div>
  </div>

</body>
</html>
```

## OUTPUT
![image](https://github.com/user-attachments/assets/b14eba38-42fa-4c49-ba46-880c609d62c0)
![image](https://github.com/user-attachments/assets/8890ed3d-14ad-4d1d-b5d2-70902994263e)
![image](https://github.com/user-attachments/assets/fe3539f0-e8ef-4693-8435-5c949c461277)
![image](https://github.com/user-attachments/assets/93e1d45e-1f1e-4587-b1f3-4dd740ba8cc8)
![image](https://github.com/user-attachments/assets/fa8afe59-f882-405c-92ff-5e9a603acd4e)
![image](https://github.com/user-attachments/assets/1a4bcbf5-36f3-435d-9345-d9d251eea69a)






## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
