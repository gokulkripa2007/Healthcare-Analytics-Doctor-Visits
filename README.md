<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Healthcare Analytics – Doctor Visits</title>
</head>

<body>

    <h1>Healthcare Analytics – Doctor Visits</h1>

    <h2>📌 Project Overview</h2>
    <p>
        This project analyzes healthcare data to understand
        <strong>patient doctor-visit patterns</strong>. The analysis focuses on
        <strong>gender, illness score, age, and doctor visits</strong> using
        Python-based data analysis and visualization.
    </p>

    <h2>🎯 Objectives</h2>
    <ul>
        <li>Compare doctor visits between <strong>male and female patients</strong>.</li>
        <li>Analyze the relationship between <strong>illness score and average doctor visits</strong>.</li>
        <li>Identify patterns in doctor visits across different illness levels.</li>
        <li>Examine doctor visits based on <strong>illness, gender, and age</strong>.</li>
    </ul>

    <h2>🛠️ Technologies Used</h2>
    <ul>
        <li><strong>Python</strong> – Data analysis and processing</li>
        <li><strong>Pandas</strong> – Data analysis and manipulation</li>
        <li><strong>Matplotlib</strong> – Data visualization</li>
        <li><strong>Seaborn</strong> – Statistical visualization</li>
        <li><strong>Google Colab</strong> – Development environment</li>
        <li><strong>CSV Dataset</strong> – Healthcare data source</li>
    </ul>

    <h2>📊 Analysis &amp; Visualizations</h2>

    <h3>1. Average Doctor Visits by Gender</h3>

    <p>
        The data is grouped by gender to calculate the
        <strong>count, mean, and median</strong> of recorded doctor visits.
    </p>

    <p><strong>Graph Title:</strong> Average Doctor Visits by Gender</p>

    <ul>
        <li>Female – Mean: <strong>0.361954</strong></li>
        <li>Male – Mean: <strong>0.236334</strong></li>
    </ul>

    <h3>2. Illness Score vs. Average Doctor Visits</h3>

    <p>
        The data is grouped according to illness score to analyze the
        <strong>average number of recorded doctor visits</strong>.
    </p>

    <p><strong>Graph Title:</strong> Illness Score vs. Average Doctor Visits</p>

    <table border="1" cellpadding="8" cellspacing="0">
        <thead>
            <tr>
                <th>Illness Score</th>
                <th>Mean Doctor Visits</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>0</td>
                <td>0.078507</td>
            </tr>
            <tr>
                <td>1</td>
                <td>0.295482</td>
            </tr>
            <tr>
                <td>2</td>
                <td>0.403805</td>
            </tr>
            <tr>
                <td>3</td>
                <td>0.420664</td>
            </tr>
            <tr>
                <td>4</td>
                <td>0.576642</td>
            </tr>
            <tr>
                <td>5</td>
                <td>0.813559</td>
            </tr>
        </tbody>
    </table>

    <h3>3. Doctor Visits by Illness, Gender and Age</h3>

    <p>
        A scatter plot is used to visualize doctor visits based on illness
        score while including <strong>gender and age</strong>.
    </p>

    <ul>
        <li><strong>X-axis:</strong> Illness Score</li>
        <li><strong>Y-axis:</strong> Doctor Visits</li>
        <li><strong>Hue:</strong> Gender</li>
        <li><strong>Point Size:</strong> Age</li>
    </ul>

    <h2>📈 Key Insights</h2>
    <ul>
        <li>
            The average recorded doctor visits differ between
            <strong>female and male groups</strong>.
        </li>
        <li>
            Average doctor visits generally <strong>increase with illness score</strong>
            in the analyzed data.
        </li>
        <li>
            <strong>Gender and age</strong> provide additional information for
            understanding doctor-visit patterns.
        </li>
    </ul>

    <h2>👥 End Users</h2>
    <ul>
        <li><strong>Hospitals and Healthcare Organizations</strong></li>
        <li><strong>Doctors and Medical Professionals</strong></li>
        <li><strong>Healthcare Administrators</strong></li>
        <li><strong>Healthcare Analysts and Researchers</strong></li>
        <li><strong>Government and Health-Planning Agencies</strong></li>
    </ul>

    <h2>🚀 How to Run</h2>

    <ol>
        <li>Open the project notebook in <strong>Google Colab</strong>.</li>
        <li>Upload the healthcare CSV dataset.</li>
        <li>Run the data-loading and preprocessing cells.</li>
        <li>Execute the analysis and visualization cells.</li>
        <li>View the generated tables and graphs.</li>
    </ol>

    <h2>📁 Project Structure</h2>

    <pre>
Healthcare-Analytics-Doctor-Visits/
│
├── README.md
├── Healthcare_Analytics_Doctor_Visits.ipynb
└── healthcare_doctor_visits.csv
    </pre>

    <h3>📄 File Description</h3>

    <ul>
        <li>
            <strong>README.md</strong> – Contains the project overview,
            objectives, technologies, analysis, insights, and conclusion.
        </li>

        <li>
            <strong>Healthcare_Analytics_Doctor_Visits.ipynb</strong> –
            Contains the Python code, data analysis, and visualizations.
        </li>

        <li>
            <strong>healthcare_doctor_visits.csv</strong> –
            Contains the healthcare dataset used for the analysis.
        </li>
    </ul>

    <h2>📌 Conclusion</h2>

    <p>
        This project demonstrates how healthcare data can be analyzed to
        understand <strong>doctor-visit patterns based on gender, illness
        score, and age</strong>. The analysis uses data processing and
        visualization techniques to identify relationships and trends in
        recorded doctor visits, providing meaningful insights into
        <strong>healthcare utilization</strong>.
    </p>

</body>
</html>
Healthcare_Analytics_Doctor_Visits.ipynb – Contains the Python code, data analysis, and visualizations.

healthcare_doctor_visits.csv – Contains the healthcare dataset used for the analysis.


📌 Conclusion

This project demonstrates how healthcare data can be analyzed to understand doctor-visit patterns based on gender, illness score, and age. The analysis uses data processing and visualization techniques to identify relationships and trends in recorded doctor visits, providing meaningful insights into healthcare utilization.
