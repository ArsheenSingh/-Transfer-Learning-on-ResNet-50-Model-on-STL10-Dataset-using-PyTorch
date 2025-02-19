
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>
  <h1>🚀 Transfer Learning on ResNet-50 Model on STL10 Dataset using PyTorch</h1>
  
  <h2>📄 Description</h2>
  <p>
    Transfer learning on ResNet-50 using PyTorch, fine-tuned on the STL10 dataset. Achieves 99.68% accuracy with data augmentation, fine-tuning, and robust evaluation. Utilizes torchvision, NumPy, and Matplotlib for efficient training and visualization. 🚀📊 Check out the notebook for full implementation! Explore the full process in the 
    <a href="transfer_learning_ResNet_STL10_pytorch.ipynb">notebook</a>.
  </p>
  
  <h2>✨ Interesting Techniques</h2>
  <ul>
    <li>🔥 <strong>Transfer Learning:</strong> Reuses a pre-trained ResNet-50 to accelerate training on STL10.</li>
    <li>🛠️ <strong>Fine-Tuning:</strong> Adjusts model layers for optimal performance on new data.</li>
    <li>📊 <strong>Robust Evaluation:</strong> Employs comprehensive metrics to reach 99.68% accuracy.</li>
    <li>💡 <strong>Data Augmentation:</strong> Uses image transformations to improve model generalization. 
  </ul>
  
  <h2>🔧 Technologies & Libraries</h2>
  <ul>
    <li>🐍 <strong>PyTorch:</strong> The main framework for building and training the model.</li>
    <li>📚 <strong>torchvision:</strong> Provides datasets and pre-trained models.</li>
    <li>🔢 <strong>NumPy:</strong> For efficient numerical computations.</li>
    <li>📈 <strong>Matplotlib:</strong> Used to visualize evaluation metrics and training progress.</li>
  </ul>
 <h1>STL-10 Dataset Overview 📸🔍</h1>
    <img src='stl10_enhanced_overview.png' alt='STL-10 Enhanced Overview'/>
    <p>The STL-10 dataset is a widely-used image dataset designed for developing unsupervised feature learning,
    classification, and other machine learning tasks. It contains 10 classes of objects, each with numerous labeled
    images, making it ideal for training and testing models. The dataset includes:</p>
    <ul>
        <li>5,000 labeled training images</li>
        <li>8,000 labeled test images</li>
        <li>100,000 unlabeled images for unsupervised learning</li>
    </ul>
    <p>The 10 classes are: airplanes 🛩️, birds 🐦, cars 🚗, cats 🐱, deer 🦌, dogs 🐶, horses 🐴, monkeys 🐒, ships 🚢, and trucks 🚚.
    Each image is 96x96 pixels in size, providing a good balance between detail and computational efficiency.</p>
    <p>The STL-10 dataset is often used as a benchmark for evaluating the performance of various machine learning
    models, particularly in the field of computer vision. Its diverse set of images and the inclusion of unlabeled
    data make it a valuable resource for researchers and developers alike.</p>
  
  <h2>📁 Project Structure</h2>
  <p>
    <strong>notebooks:</strong> Contains the main notebook detailing the transfer learning workflow.<br>
    <strong>models:</strong> Stores saved model weights after fine-tuning.<br>
    <strong>/data:</strong> Holds the STL10 dataset used for training and testing.<br>
    <strong>/results:</strong> Includes evaluation outputs and visualizations.<br>
    <strong>/utils:</strong> Consists of helper scripts for data preparation and analysis.
  </p>
</body>
</html>
