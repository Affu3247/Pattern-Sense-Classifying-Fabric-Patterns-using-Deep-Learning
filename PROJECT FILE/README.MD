<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Pattern Sense - Fabric Pattern Classification</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #f5f5f5;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #2c3e50;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    .container {
      max-width: 900px;
      margin: auto;
      padding: 20px;
    }
    .section {
      background-color: white;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    h2 {
      color: #34495e;
    }
    footer {
      text-align: center;
      padding: 10px;
      background-color: #2c3e50;
      color: white;
    }
  </style>
</head>
<body>

  <header>
    <h1>Pattern Sense</h1>
    <p>Classifying Fabric Patterns using Deep Learning</p>
  </header>

  <div class="container">

    <div class="section">
      <h2>Abstract</h2>
      <p>
        Pattern Sense leverages deep learning to automatically classify different fabric patterns such as floral, geometric, striped, and abstract. This project helps in automating textile sorting and style recommendation by analyzing visual features using convolutional neural networks (CNNs).
      </p>
    </div>

    <div class="section">
      <h2>Technology Stack</h2>
      <ul>
        <li>Python (TensorFlow / Keras)</li>
        <li>HTML, CSS</li>
        <li>Jupyter Notebook</li>
        <li>Google Colab</li>
        <li>Dataset from Kaggle / Custom Fabric Images</li>
      </ul>
    </div>

    <div class="section">
      <h2>Model Overview</h2>
      <p>
        The deep learning model is trained using a Convolutional Neural Network (CNN) architecture. Transfer Learning (using pretrained models like MobileNetV2) improves accuracy and reduces training time. The model classifies input fabric images into their respective pattern categories.
      </p>
    </div>

    <div class="section">
      <h2>Results</h2>
      <p>
        The model achieved over 90% accuracy on the test dataset, showing strong performance in distinguishing among multiple fabric patterns. The system is deployable for use in fashion tech applications or fabric sorting tools.
      </p>
    </div>

    <div class="section">
      <h2>Team Members</h2>
      <ul>
        <li>Thumbeti Usha Rani (Team Leader)</li>
        <li>Shaik Asma</li>
        <li>Potu Naga Malleswari</li>
        <li>Tanguturi Manasa Lakshmi</li>
      </ul>
    </div>

  </div>

  <footer>
    &copy; 2025 Pattern Sense Project | Vemana Women's Degree College
  </footer>

</body>
</html>
