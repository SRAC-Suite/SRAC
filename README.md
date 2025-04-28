<style>
body {
    font-family: 'Helvetica Neue', 'Roboto', 'Segoe UI', Arial, sans-serif;
    background-color: #ffffff;
    color: #333333;
    margin: 0;
    padding: 0 20px;
    line-height: 1.6;
    max-width: 1200px;
    margin: 0 auto;
}

h1, h2, h3, h4, h5 {
    color: #009530;
    font-weight: 600;
    margin-top: 1.2em;
    margin-bottom: 0.5em;
}

h1 {
    font-size: 2.5em;
    border-bottom: 3px solid #009530;
    padding-bottom: 10px;
    text-align: center;
}

h2 {
    font-size: 1.8em;
    border-bottom: 2px solid #009530;
    padding-bottom: 6px;
}

h3 {
    font-size: 1.5em;
}

h4 {
    font-size: 1.3em;
    color: #006E2E;
}

a {
    color: #3366CC;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
    color: #009530;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin: 20px 0;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

th, td {
    border: 1px solid #e0e0e0;
    padding: 12px 15px;
    text-align: left;
}

th {
    background-color: #009530;
    color: white;
    font-weight: 600;
}

tr:nth-child(even) {
    background-color: #f5f5f5;
}

tr:hover {
    background-color: #f0f0f0;
}

blockquote {
    background-color: #f9f9f9;
    border-left: 6px solid #009530;
    margin: 10px 0;
    padding: 5px 10px;
    color: #555;
    font-style: italic;
}

code {
    background-color:rgb(52, 97, 164);
    padding: 2px 6px;
    border-radius: 4px;
    font-family: Consolas, 'Courier New', monospace;
    font-size: 95%;
}

ul, ol {
    padding-left: 15px;
    margin-bottom: 10px;
}

ul li {
    margin-bottom: 4px;
}

ul li::marker {
    color: #009530; /* Green bullet points */
}

.feature-box {
    background-color: #f9f9f9;
    border-left: 4px solid #009530;
    padding: 10px;
    margin: 10px 0;
    border-radius: 0 5px 5px 0;
}

footer {
    text-align: center;
    padding: 15px 0;
    font-size: 0.9em;
    color: #666;
    margin-top: 50px;
    border-top: 1px solid #eee;
}

hr {
    border: 0;
    height: 1px;
    background: #ddd;
    margin: 15px 0;
}

.button {
    background-color: #009530;
    color: white;
    padding: 10px 25px;
    text-align: center;
    border-radius: 5px;
    display: inline-block;
    font-size: 16px;
    font-weight: bold;
    margin: 15px 0;
    text-decoration: none;
    transition: background-color 0.3s ease;
    border: none;
    cursor: pointer;
}

.button:hover {
    background-color: #006E2E;
}

.logo-container {
    text-align: center;
    margin: 10px 0;
}

.section-container {
    margin: 10px 0;
    padding: 20px;
    background-color: #ffffff;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
}

@media (max-width: 768px) {
    body {
        padding: 0 15px;
    }
    h1 {
        font-size: 2em;
    }
    h2 {
        font-size: 1.5em;
    }
}
</style>

<div class="logo-container">
</div>

# SRAC: Student Result Analysis Compiler
---

## Overview

<div class="section-container">
    <p><strong>SRAC (Student Result Analysis Compiler)</strong> is a purpose-built application designed to automate and optimize the process of analyzing student academic results for educational institutions. It replaces time-consuming manual workflows with a fast, accurate, and efficient automated system.</p>
    <p><strong>Challenge Addressed:</strong> Manual processing of student results is inherently slow, susceptible to errors, and scales poorly with large student numbers.</p>
    <p><strong>SRAC Solution:</strong> Provides a robust tool to significantly reduce processing time, enhance data accuracy, and deliver comprehensive analytical insights with minimal manual intervention.</p>
</div>

---

## 🎬 Application Demo

<div class="section-container">
    <p>Observe the workflow and capabilities of SRAC:</p>
    <div style="text-align: center;">
        <a href="https://www.youtube.com/watch?v=NV3BSmPhQcU" target="_blank">
            <img src="https://img.youtube.com/vi/NV3BSmPhQcU/0.jpg" alt="SRAC Demo Video" style="max-width: 80%; border-radius: 5px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
        </a>
        <p><em>(Click the image above to watch the demonstration on YouTube)</em></p>
    </div>
</div>

---

## ✨ Core Features & Benefits

<div class="section-container">
    <div class="feature-box">
        <h4>Process Automation</h4>
        <p>Eliminates manual data handling in result download, extraction, and analysis, minimizing errors and saving significant time.</p>
    </div>
    <div class="feature-box">
        <h4>Versatile Reporting</h4>
        <p>Generate and export results in multiple standard formats (PDF, Excel) and customizable templates suitable for institutional needs.</p>
    </div>
    <div class="feature-box">
        <h4>Automated PDF Integration</h4>
        <p>Intelligently processes source PDF result files, automating data extraction.</p>
    </div>
    <div class="feature-box">
        <h4>Data Management</h4>
        <p>Includes features for secure report backup and options for direct distribution via email.</p>
    </div>
    <div class="feature-box">
        <h4>In-Depth Analysis</h4>
        <p>Enables generation of detailed reports for individual students and comparative analysis across subjects.</p>
    </div>
    <div class="feature-box">
        <h4>Enhanced Visualization</h4>
        <p>Presents complex data through clear, color-coded graphs and charts for improved comprehension and decision-making.</p>
    </div>
</div>

---

## ⚙️ Installation and Usage

<div class="section-container">
    <h3>Prerequisites</h3>
    <ul>
        <li><strong>External Dependencies:</strong> All required components will be included in the package. Simply run the installer and restart your system to begin using SRAC.</li>
    </ul>
    <h3>Installation Steps</h3>
    <ol>
        <li>Navigate to the <strong><a href="https://github.com/SRAC-Suite/SRAC/releases">Releases Section</a></strong> of this repository.</li>
        <li>Download the latest installer package.</li>
        <li>Execute the installer and follow the provided setup instructions.</li>
    </ol>
    <h3>Basic Operation</h3>
    <ol>
      <li>Launch SRAC from your desktop or start menu</li>
      <li>Input the USN list and result download URL in the designated fields</li>
      <li>Navigate to the PDF section and select target result files</li>
      <li>Process and generate the revaluation PDF documents</li>
      <li>Use the email module to distribute reports to management</li>
      <li>Create secure backups of all generated data</li>
      <li>View comprehensive reports in your specified output folder</li>
    </ol>
</div>

---

## 📊 Performance Advantage

<div class="section-container">
    <p>SRAC delivers substantial improvements in efficiency and reliability compared to manual methods:</p>
    <ul>
        <li><strong>Unmatched Speed:</strong> Reduces processing time by over <strong>99%</strong>. Analysis tasks that typically take days are completed within <strong>minutes</strong>.
            <ul>
                <li><em>Efficiency Example:</em> Processing results for over 500 students can be achieved in approximately <strong>12 minutes</strong>.</li>
            </ul>
        </li>
        <li><strong>Guaranteed Accuracy:</strong> Automation eliminates the risk of human error in data transcription and calculation.</li>
        <li><strong>Scalability & Consistency:</strong> Maintains high performance and reliability regardless of the volume of data being processed.</li>
    </ul>
</div>

---

## 🙏 Acknowledgements

<div class="section-container">
    <p>The development of SRAC was supported by the Department of Computer Science and Engineering at ACS College of Engineering, under the guidance of Dr. T Senthil Kumaran.</p>
</div>

---

## 📞 Support

<div class="section-container">
    <p>For technical support, bug reports, or feature requests, please raise an issue in the <a href="https://github.com/SRAC-Suite/SRAC/issues">Issues section</a> of this repository. Our team actively monitors and responds to all submitted issues.</p>
</div>
<footer>
    <p>© 2025 SRAC - All Rights Reserved</p>
    <div style="text-align: center; margin-top: 15px;">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQb3sGnL2EssrzxOx9g9f6q3GccttdnCcZg1w&s" alt="Make in India" style="width: 120px; height: auto;">
    </div>
</footer>