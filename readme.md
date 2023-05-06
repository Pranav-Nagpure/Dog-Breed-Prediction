<a name="readme-top"></a>

<div align="center">

# __Dog Breed Prediction__

### Built Using
  
[![Python][python-shield]][python-url]
[![Streamlit][streamlit-shield]][streamlit-url]
[![Keras][keras-shield]][keras-url]
[![TensorFlow][tensorflow-shield]][tensorflow-url]
[![NumPy][numpy-shield]][numpy-url]

Visit the <a href="https://dogbreed-predictor.onrender.com">Web Application</a> deployed on render

</div>

## __About__
<p align="justify">
A Web Application to Predict the Breed of Dogs from an image using a <a href="https://arxiv.org/abs/1610.02357">Xception Convolutional Neural Network</a> and Logistic Regression using transfer learning.

Data Source: https://www.kaggle.com/datasets/catherinehorng/dogbreedidfromcomp

Model was built with this <a href="https://github.com/Pranav-Nagpure/Dog-Breed-Prediction-NB">IPython Notebook</a>
</p>

## __Getting Started__

This Project is Built With [![Anaconda][anaconda-shield]][anaconda-url] [![VSCode][vscode-shield]][vscode-url] [![Render][render-shield]][render-url]

### __Installation__
To use the app on local machine, open Anaconda Prompt and run the following commands:

1. Clone the Repository
```sh
git clone https://github.com/Pranav-Nagpure/Dog-Breed-Prediction.git
```

2. Change Working Directory
```sh
cd Dog-Breed-Prediction
```

3. If needed create a Virtual Environment and activate it
```sh
conda create -n environment_name python=3.10
conda activate environment_name
```

4. Install the requirements
```sh
conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0
python -m pip install -r requirements.txt
```

5. Run the App
```sh
streamlit run app.py
```

6. App will open in a browser

<p align="right">
(<a href="#readme-top">back to top</a>)
</p>

[python-shield]: https://raw.githubusercontent.com/Pranav-Nagpure/Support-Repository/master/images/python-shield.png "Python"
[python-url]: https://www.python.org

[streamlit-shield]: https://raw.githubusercontent.com/Pranav-Nagpure/Support-Repository/master/images/streamlit-shield.png
[streamlit-url]: https://streamlit.io "Streamlit"

[keras-shield]: https://raw.githubusercontent.com/Pranav-Nagpure/Support-Repository/master/images/keras-shield.png
[keras-url]: https://keras.io "Keras"

[tensorflow-shield]: https://raw.githubusercontent.com/Pranav-Nagpure/Support-Repository/master/images/tensorflow-shield.png
[tensorflow-url]: https://www.tensorflow.org "TensorFlow"

[numpy-shield]: https://raw.githubusercontent.com/Pranav-Nagpure/Support-Repository/master/images/numpy-shield.png
[numpy-url]: https://numpy.org "NumPy"

[anaconda-shield]: https://raw.githubusercontent.com/Pranav-Nagpure/Support-Repository/master/images/anaconda-shield.png
[anaconda-url]: https://www.anaconda.com "Anaconda"

[vscode-shield]: https://raw.githubusercontent.com/Pranav-Nagpure/Support-Repository/master/images/vscode-shield.png
[vscode-url]: https://code.visualstudio.com "VSCode"

[render-shield]: https://raw.githubusercontent.com/Pranav-Nagpure/Support-Repository/master/images/render-shield.png
[render-url]: https://render.com "Render"