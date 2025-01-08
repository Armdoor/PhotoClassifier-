<h1>PhotoClassifier: CNN-Based Image Classification</h1>
    <p>
        This project demonstrates how to train a simple image classifier using PyTorch, leveraging a 
        Convolutional Neural Network (CNN) for accurate image classification.
    </p>
    <hr>
    <h2>Overview</h2>
    <p>The project consists of the following main components:</p>
    <ol>
        <li>
            <strong>Dataset Class</strong>
            <ul>
                <li>Implements a custom dataset class for loading and preprocessing images.</li>
                <li>Handles image transformations (e.g., resizing, normalization) directly within the class for efficient data handling during training and evaluation.</li>
            </ul>
        </li>
        <li>
            <strong>Model Design</strong>
            <ul>
                <li>Defines a CNN-based architecture optimized for image classification.</li>
                <li>Includes layers such as convolutional, pooling, and fully connected layers to extract features and predict image classes.</li>
            </ul>
        </li>
        <li>
            <strong>Model Training</strong>
            <ul>
                <li>Trains the CNN model using labeled image data.</li>
                <li>Implements loss calculation, backpropagation, and optimization to improve the model's accuracy over multiple epochs.</li>
            </ul>
        </li>
        <li>
            <strong>Evaluation</strong>
            <ul>
                <li>Loads the trained model's weights and performs inference on a test dataset.</li>
                <li>Measures the model's performance through metrics like accuracy, precision, and recall.</li>
            </ul>
        </li>
    </ol>
    <hr>
    <h2>Files</h2>
    <ul>
        <li><code>PhotoClassifier.ipynb</code>: Contains the dataset class, CNN model definition, training pipeline, and evaluation logic.</li>
    </ul>
    <hr>
    <h2>Requirements</h2>
    <ul>
        <li>Python 3.x</li>
        <li>PyTorch</li>
        <li>torchvision</li>
        <li>Matplotlib (for visualization)</li>
    </ul>
    <hr>
    <h2>Credits</h2>
    <p>
        This project is inspired by foundational concepts in deep learning and image classification, 
        using PyTorch for model implementation and training.
    </p>
