<h1>Arabic Text Summarization</h1>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<p>This repository contains the code for an Arabic text summarization system. The system utilizes the AraBART model, based on the Transformers architecture, to generate summaries for Arabic text documents. The model is trained using a labeled dataset and is capable of both extractive and abstractive summarization.</p>

<h2>Installation</h2>

<p>To run the code, please follow the steps below:</p>

<ol>
  <li>Clone the repository:</li>
  <code>git clone https://github.com/Geo-y20/Text-Summarization-in-Arabic.git</code>
  <li>Change the directory to the project folder:</li>
  <code>cd Text-Summarization-in-Arabic</code>
  <li>Install the required dependencies:</li>
  <code>pip install -r requirements.txt</code>
</ol>

<h2>Usage</h2>

<h3>Training</h3>

<p>To train the summarization model, you need to provide a labeled dataset. The dataset should be in JSONL format, where each line represents a document with its corresponding summary. Modify the <code>train.py</code> file to load your labeled dataset and adjust the training parameters if necessary. Then, run the following command to start the training process:</p>
<code>python train.py</code>

<h3>Inference</h3>

<p>To generate summaries using the trained model, you can provide a separate validation dataset or test the model on your own text data. Modify the <code>inference.py</code> file to load your dataset and adjust the inference parameters as needed. Run the following command to generate summaries:</p>
<code>python inference.py</code>

<h2>Directory Structure</h2>

<p>The repository structure is organized as follows:</p>

<pre>
- data/
  - labeled_dataset.jsonl      # Labeled dataset for training
  - validation_dataset.jsonl   # Dataset for validation or testing
- models/
  - trained_model/             # Saved trained model
    - config.json
    - pytorch_model.bin
    - ...
- utils/
  - preprocessing.py           # Preprocessing utilities
  - evaluation.py              # Evaluation metrics
- train.py                     # Training script
- inference.py                 # Inference script
- requirements.txt             # Dependencies
- README.md                    # Project documentation
- LICENSE                      # License information
</pre>

<h2>Contributing</h2>

<p>Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.</p>

<h2>License</h2>

<p>This project is licensed under the MIT License.</p>

<h2>Contact</h2>

<p>For any questions or inquiries, please feel free to reach out to the project maintainers:</p>

<ul>
  <li>George Youhana - g.ghaly0451@student.aast.edu</li>
  <li>Mostafa Magdy - Mustafa.10770@stemredsea.moe.edu.eg </li>
  <li>Abdallah Alkhouly- a.alkholy53@student.aast.edu</li>
  <li>Ahmed Hafez</li>
  <li>Mahmoud Yasser- mahmoudyaser3110@gmail.com </li>
</ul>
