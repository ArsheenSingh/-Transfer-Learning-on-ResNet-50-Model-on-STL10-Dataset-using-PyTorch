# -Transfer-Learning-on-ResNet-50-Model-on-STL10-Dataset-using-PyTorch
Transfer learning on ResNet-50 using PyTorch, fine-tuned on the STL10 dataset. Achieves 99.68% accuracy with data augmentation, fine-tuning, and robust evaluation. Utilizes torchvision, NumPy, and Matplotlib for efficient training and visualization. 🚀📊 Check out the notebook for full implementation!
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>🚀 Transfer Learning on ResNet-50 Model on STL10 Dataset using PyTorch</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f7f7f7;
      color: #333;
      margin: 2rem;
      line-height: 1.6;
    }
    h1, h2 {
      color: #222;
    }
    pre {
      background: #eaeaea;
      padding: 1rem;
      border-radius: 5px;
      overflow-x: auto;
    }
    a {
      color: #007acc;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <h1>🚀 Transfer Learning on ResNet-50 Model on STL10 Dataset using PyTorch</h1>
  
  <h2>📄 Description</h2>
  <p>
    This project applies transfer learning by fine-tuning a pre-trained ResNet-50 model on the STL10 dataset using PyTorch. The approach achieves an impressive test accuracy of <strong>99.68%</strong>. Explore the full process in the 
    <a href="./notebooks/transfer_learning_ResNet_STL10_pytorch.ipynb">notebook</a>.
  </p>
  
  <h2>✨ Interesting Techniques</h2>
  <ul>
    <li>🔥 <strong>Transfer Learning:</strong> Reuses a pre-trained ResNet-50 to accelerate training on STL10.</li>
    <li>🛠️ <strong>Fine-Tuning:</strong> Adjusts model layers for optimal performance on new data.</li>
    <li>📊 <strong>Robust Evaluation:</strong> Employs comprehensive metrics to reach 99.68% accuracy.</li>
    <li>💡 <strong>Data Augmentation:</strong> Uses image transformations to improve model generalization. Learn more about <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations" target="_blank">web animations</a> on MDN.</li>
  </ul>
  
  <h2>🔧 Technologies & Libraries</h2>
  <ul>
    <li>🐍 <strong>PyTorch:</strong> The main framework for building and training the model.</li>
    <li>📚 <strong>torchvision:</strong> Provides datasets and pre-trained models.</li>
    <li>🔢 <strong>NumPy:</strong> For efficient numerical computations.</li>
    <li>📈 <strong>Matplotlib:</strong> Used to visualize evaluation metrics and training progress.</li>
  </ul>
  
  <h2>📁 Project Structure</h2>
  <pre>
/notebooks
   transfer_learning_ResNet_STL10_pytorch.ipynb   # Jupyter notebook with full code and evaluation
/models
   resnet50_finetuned.pth                         # Fine-tuned model weights
/data
   STL10/                                       # STL10 dataset files
/results
   evaluation.txt                              # Evaluation metrics and results
   accuracy.png                                # Graphs of accuracy and loss trends
/utils
   helper_functions.py                         # Utility scripts for data processing and visualization
  </pre>
  <p>
    <strong>/notebooks:</strong> Contains the main notebook detailing the transfer learning workflow.<br>
    <strong>/models:</strong> Stores saved model weights after fine-tuning.<br>
    <strong>/data:</strong> Holds the STL10 dataset used for training and testing.<br>
    <strong>/results:</strong> Includes evaluation outputs and visualizations.<br>
    <strong>/utils:</strong> Consists of helper scripts for data preparation and analysis.
  </p>
</body>
</html>
