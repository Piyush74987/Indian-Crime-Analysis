<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Indian Crime Analysis (2001–2013)</title>
</head>
<body>
    <h1>🕵️‍♂️ Indian Crime Analysis (2001–2013)</h1>
    <p>This project contains a data analysis of crimes reported in India from 2001 to 2013. It involves data preprocessing, exploratory data analysis (EDA), and Power BI-based interactive dashboards for visual insight generation.</p>

  <h2>📚 Table of Contents</h2>
    <ul>
        <li><a href="#introduction">Introduction</a></li>
        <li><a href="#project-structure">Project Structure</a></li>
        <li><a href="#technologies-used">Technologies Used</a></li>
        <li><a href="#dataset-information">Dataset Information</a></li>
        <li><a href="#usage">Usage</a></li>
        <li><a href="#results">Results</a></li>
        <li><a href="#contributing">Contributing</a></li>
        <li><a href="#license">License</a></li>
    </ul>

  <h2 id="introduction">🔍 Introduction</h2>
    <p>The <strong>Indian Crime Analysis</strong> project provides insights into crime trends across Indian states and union territories over 13 years. It helps in identifying high-crime regions, observing trends over time, and informing policy decisions.</p>

   <h2 id="project-structure">📁 Project Structure</h2>
    <pre>
Indian-Crime-Analysis/
├── data/                     # Raw CSV dataset
├── dashboard/                # Power BI dashboard file
├── notebooks/                # Python notebooks for EDA (optional)
├── images/                   # Screenshots of visualizations
├── README.md                 # Project documentation
└── crime_analysis_dashboard.pbix  # Power BI dashboard
    </pre>

   <h2 id="technologies-used">🛠️ Technologies Used</h2>
    <ul>
        <li><strong>Python</strong> – Pandas, NumPy, Seaborn, Matplotlib</li>
        <li><strong>Power BI</strong> – Data visualization and dashboards</li>
        <li><strong>Git/GitHub</strong> – Version control</li>
    </ul>

  <h2 id="dataset-information">📊 Dataset Information</h2>
    <ul>
        <li><strong>File:</strong> Crimes_in_india_2001-2013(in)(in).csv</li>
        <li><strong>Attributes:</strong>
            <ul>
                <li>STATE/UT</li>
                <li>CRIME HEAD</li>
                <li>YEAR</li>
                <li>VALUE (number of cases)</li>
            </ul>
        </li>
        <li><strong>Source:</strong> Likely from <a href="https://data.gov.in">data.gov.in</a></li>
    </ul>

  <h2 id="usage">▶️ Usage</h2>
    <h3>🔵 Power BI</h3>
    <ol>
        <li>Open the file <code>crime_analysis_dashboard.pbix</code> in Power BI Desktop.</li>
        <li>If prompted, relink the dataset to the CSV file located in <code>/data</code>.</li>
        <li>Interact with the dashboard using filters for year, state, and crime type.</li>
    </ol>

   <h2 id="results">📈 Results</h2>
    <ul>
        <li>Top Crime-Prone States: Uttar Pradesh, Maharashtra, Madhya Pradesh</li>
        <li>Consistent rise observed in cybercrimes and crimes against women</li>
        <li>Visuals include bar charts, line charts, and heatmaps for crime trends</li>
    </ul>

   <h2 id="contributing">🤝 Contributing</h2>
    <p>Contributions are welcome! Follow these steps to contribute:</p>
    <ol>
        <li>Fork the repository</li>
        <li>Create a new branch:
            <pre><code>git checkout -b feature/your-feature-name</code></pre>
        </li>
        <li>Commit your changes:
            <pre><code>git commit -m "Add your message"</code></pre>
        </li>
        <li>Push to the branch:
            <pre><code>git push origin feature/your-feature-name</code></pre>
        </li>
        <li>Open a pull request</li>
    </ol>

   <h2 id="license">📃 License</h2>
    <p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>
</body>
</html>
