<body>

<h1>Global Banks ETL Project</h1>

<p>This repository contains a comprehensive ETL (Extract, Transform, Load) pipeline project for extracting, transforming, and loading data of the largest banks in the world. The project is implemented in Python and demonstrates the process of data extraction from a web page, transformation for analysis, and loading into a database.</p>

<h2>Table of Contents</h2>
<ul>
    <li><a href="#introduction">Introduction</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#requirements">Requirements</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#project-structure">Project Structure</a></li>
    <li><a href="#functions-overview">Functions Overview</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
</ul>

<h2 id="introduction">Introduction</h2>
<p>The Global Banks ETL project showcases a typical ETL pipeline using Python. The primary goal is to extract data on the largest banks by market capitalization from Wikipedia, transform it by cleaning and converting currencies, and load the processed data into a CSV file and an SQLite database.</p>

<h2 id="features">Features</h2>
<ul>
    <li><strong>Data Extraction:</strong> Fetches data from the web using <code>requests</code> and parses HTML with <code>BeautifulSoup</code>.</li>
    <li><strong>Data Transformation:</strong> Cleans and processes data using <code>pandas</code>, including currency conversion.</li>
    <li><strong>Data Loading:</strong> Saves transformed data into a CSV file and an SQLite database.</li>
    <li><strong>Logging:</strong> Implements logging to track the progress of the ETL process using the <code>icecream</code> library.</li>
</ul>

<h2 id="requirements">Requirements</h2>
<ul>
    <li>Python 3.x</li>
    <li><code>requests</code></li>
    <li><code>BeautifulSoup</code></li>
    <li><code>pandas</code></li>
    <li><code>sqlite3</code></li>
    <li><code>datetime</code></li>
    <li><code>icecream</code></li>
</ul>
