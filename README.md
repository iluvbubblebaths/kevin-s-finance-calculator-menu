<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Kevin’s Finance Calculator Manual</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #f3e5f5, #e1f5fe);
      color: #2c3e50;
    }
    header {
      background: linear-gradient(to right, #4a148c, #6a1b9a);
      color: white;
      padding: 40px;
      text-align: center;
    }
    nav {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      background-color: #6a1b9a;
      padding: 10px;
    }
    nav a {
      color: #fffde7;
      margin: 10px 15px;
      text-decoration: none;
      font-weight: bold;
      font-size: 16px;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffccbc;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
      background-color: #fce4ec;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
      margin-top: 30px;
    }
    h2 {
      color: #00796b;
      margin-bottom: 20px;
    }
    ul, ol {
      line-height: 1.8;
    }
    .highlight {
      background-color: #ffe0b2;
      padding: 10px;
      border-left: 5px solid #ff7043;
      margin: 15px 0;
    }
    footer {
      background: linear-gradient(to right, #4a148c, #6a1b9a);
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

<header>
  <h1>📘 Kevin’s Finance Calculator Manual</h1>
  <p>Your interactive guide to mastering Excel-based financial calculations</p>
</header>

<nav>
  <a href="#overview">Overview</a>
  <a href="#excel-tips">Excel Tips</a>
  <a href="#calculator-guide">Calculator Guide</a>
  <a href="#examples">Examples</a>
  <a href="#faq">FAQ</a>
  <a href="#glossary">Glossary</a>
  <a href="#contact">Contact</a>
</nav>

<section id="overview">
  <h2>🔍 Overview</h2>
  <p>Welcome to Kevin’s Finance Calculator Manual. This guide helps users navigate the Excel-based calculator, understand its logic, and use it efficiently for financial computations like Present Value, Future Value, and Loan analysis.</p>
</section>

<section id="excel-tips">
  <h2>📊 Excel Tips</h2>
  <ul>
    <li>Use <strong style="color:green;">green cells</strong> for inputs and <strong style="color:blue;">blue cells</strong> for outputs</li>
    <li>Enable macros when prompted</li>
    <li>Use dropdowns to select calculation types and interest formats</li>
    <li>Click the “Homepage” button to return to the main dashboard</li>
    <li>Ensure all required fields are filled before expecting an answer</li>
  </ul>
</section>

<section id="calculator-guide">
  <h2>🧮 Calculator Guide</h2>
  <ul>
    <li><strong>GIVEN Section:</strong> Input values like Interest Rate (r), Compounding Period (p), Years (N), PV, FV, Loan, and Increasing Rate (I)</li>
    <li><strong>REQUIRED Section:</strong> Choose what to calculate (e.g., PV, FV, Loan), select interest type and formula</li>
    <li><strong>CONTROL PANEL:</strong> Use date inputs or manually enter years, toggle VLP and division settings</li>
    <li><strong>ANSWER Cell:</strong> Once all inputs are valid, the result appears automatically in the cell labeled <span class="highlight">“ANSWER:”</span></li>
  </ul>
</section>

<section id="examples">
  <h2>📘 Examples</h2>
  <div class="highlight">
    <strong>Example:</strong> Calculate Future Value  
    <ol>
      <li>Enter Present Value in GIVEN → PV</li>
      <li>Set Interest Rate and Compounding Period</li>
      <li>Select “Future Value” in REQUIRED → Requested</li>
      <li>Choose the correct formula and interest type</li>
      <li>Result appears in the cell labeled “ANSWER:”</li>
    </ol>
  </div>
</section>

<section id="faq">
  <h2>❓ FAQ</h2>
  <ul>
    <li><strong>Q:</strong> Why is my answer not showing?<br><strong>A:</strong> Ensure all required inputs are filled and dropdowns are selected correctly.</li>
    <li><strong>Q:</strong> Can I use dates instead of years?<br><strong>A:</strong> Yes! Use Start Date and End Date in the CONTROL PANEL and enable “Use Date Difference?”</li>
    <li><strong>Q:</strong> What does VLP mean?<br><strong>A:</strong> VLP is a toggle for advanced logic—enable it only if your calculation requires it.</li>
  </ul>
</section>

<section id="glossary">
  <h2>📚 Glossary</h2>
  <ul>
    <li><strong>PV:</strong> Present Value</li>
    <li><strong>FV:</strong> Future Value</li>
    <li><strong>VLP:</strong> Value Of Last Payment</li>
    <li><strong>Compounding Period:</strong> Frequency of interest application</li>
  </ul>
</section>

<section id="contact">
  <h2>📬 Contact</h2>
  <p>For feedback or support, reach out to Kevin via 0824369789 or email kevinndou529@gmail.com</p>
</section>

<footer>
  <p>&copy; 2025 Kevin’s Finance Tools. All rights reserved.</p>
</footer>

</body>
</html>


