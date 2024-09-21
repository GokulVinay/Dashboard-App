<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <title>CNAPP Dashboard</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background-color: #f4f4f4;
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
      background-color: #fff;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    h1 {
      text-align: center;
      color: #333;
    }

    h2 {
      color: #a900ff;
    }

    p,
    ul {
      line-height: 1.6;
      color: #555;
    }

    .features ul,
    .technologies ul,
    .setup-instructions ol,
    .usage ol {
      padding-left: 20px;
    }

    .badges {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 20px;
    }

    .badge {
      padding: 5px 10px;
      background-color: #2e2e2e;
      border-radius: 5px;
      color: #fff;
      font-size: 14px;
      display: inline-block;
    }

    .link {
      text-decoration: none;
      color: #a900ff;
    }

    .section {
      margin-bottom: 40px;
    }

    .align-center {
      text-align: center;
    }

    .code-block {
      background-color: #f1f1f1;
      padding: 10px;
      border-radius: 5px;
      font-family: monospace;
    }
  </style>
</head>

<body>
  <div class="container">
    <h1>CNAPP Dashboard</h1>

    <div class="section">
      <p class="align-center">
        You can check the live version of the project here: <a class="link" href="https://cnapp-dashboard1.netlify.app/"
          target="_blank">CNAPP Dashboard</a>
      </p>
    </div>

    <div class="section features">
      <h2>Features</h2>
      <ul>
        <li><strong>Dynamic Widget Display:</strong> Displays widgets organized by categories.</li>
        <li><strong>Add New Widgets:</strong> Users can add new widgets to specific categories.</li>
        <li><strong>Widget Filtering:</strong> Search and filter widgets by name.</li>
        <li><strong>Delete Widgets:</strong> Remove unwanted widgets from categories.</li>
        <li><strong>Modal Interactions:</strong> Utilizes modals for adding widgets and confirming deletions.</li>
        <li><strong>Responsive Design:</strong> Adapts to different screen sizes for optimal viewing.</li>
      </ul>
    </div>

    <div class="section technologies">
      <h2>Technologies Used</h2>
      <div class="badges">
        <span class="badge">React</span>
        <span class="badge">Redux Toolkit</span>
        <span class="badge">Tailwind CSS</span>
        <span class="badge">React Icons</span>
        <span class="badge">Chart.js</span>
        <span class="badge">React Chartjs-2</span>
      </div>
    </div>

    <div class="section setup-instructions">
      <h2>Setup Instructions</h2>
      <ol>
        <li>
          <p><strong>Clone the repository:</strong></p>
          <pre class="code-block">git clone https://github.com/rd273001/CNAPP-Dashboard.git
cd CNAPP-Dashboard</pre>
        </li>
        <li>
          <p><strong>Install dependencies:</strong></p>
          <pre class="code-block">npm install
# OR
yarn</pre>
        </li>
        <li>
          <p><strong>Start the application:</strong></p>
          <pre class="code-block">npm run dev
# OR
yarn dev</pre>
        </li>
      </ol>
      <p>This will start the development server and make the application available at <a class="link"
          href="http://localhost:3000" target="_blank">http://localhost:3000</a> in your default web browser.</p>
    </div>

    <div class="section usage">
      <h2>Usage</h2>
      <ol>
        <li><strong>Adding Widgets:</strong>
          <p>Click the "Add Widget" button on a category card or the "Add Widget" button in the header. Fill in the widget
            details in the modal and click "Add Widget".</p>
        </li>
        <li><strong>Filtering Widgets:</strong>
          <p>Use the search bar in the header to filter widgets by name.</p>
        </li>
        <li><strong>Deleting Widgets:</strong>
          <p>Click the "Delete" button on a widget card. Confirm the deletion in the modal.</p>
        </li>
      </ol>
    </div>

    <div class="section future-enhancements">
      <h2>Future Enhancements</h2>
      <ul>
        <li><strong>Widget Customization:</strong> Allow users to customize widget appearance and data displayed.</li>
        <li><strong>Data Persistence:</strong> Implement data storage to save dashboard configurations.</li>
        <li><strong>User Authentication:</strong> Add user accounts and role-based access control.</li>
        <li><strong>More Widget Types:</strong> Introduce a wider variety of widgets for different data visualizations.</li>
      </ul>
    </div>

    <div class="section contribution">
      <h2>Contribution</h2>
      <p>Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or
        improvements.</p>
    </div>
  </div>
</body>

</html>
