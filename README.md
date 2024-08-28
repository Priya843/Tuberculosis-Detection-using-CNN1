<h1>Tuberculosis Detection Using Deep Learning</h1>
<hr>
<p>This project focuses on developing and evaluating a deep learning model to detect tuberculosis (TB) from chest X-ray images. The model leverages pre-trained convolutional neural networks (CNNs) to classify images and assist in TB diagnosis.</p>
<hr>
<h2>Project Structure</h2>
<ul>
  <li>Data Downloading and Preparation:</li>
  <br>
  <p>The dataset is automatically downloaded from a specified source, uncompressed, and prepared for training and validation.</p>

  <li>Model Creation:</li>
  <br>
  <p>A function create_model is provided to build and compile the deep learning model. This function uses a pre-trained base model, applies global average pooling, and adds a dense layer with softmax activation for classification into TB-positive or TB-negative categories.</p>

  <li>Model Evaluation:</li>
  <br>
  <p>A function evaluate_model is used to assess the model's performance. It makes predictions on the validation dataset, computes a confusion matrix, and prints the accuracy score along with a detailed classification report.</p>
  
</ul>

<h1>Files</h1>
<ul>
  <li>DS_Project_9Models (1) (1).ipynb:</li>
  <p>Jupyter notebook containing the entire workflow from data preparation, model creation, training, and evaluation.</p>
</ul>

