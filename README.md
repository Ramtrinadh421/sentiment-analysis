# Build + Deploy a Sentiment Analysis Model to classify Amazon Alexa Reviews into Positive & Negative

An end-to-end toolkit on building a sentiment prediction model with a Jupyter notebook and deploying the model pickle on a local machine using Flask.  
**Author:** Ram Trinadh

Our use case is review classification of Amazon Alexa customer feedback into positive and negative.

**Dataset source:**  
[Amazon Reviews (Kaggle)](https://www.kaggle.com/sid321axn/amazon-alexa-reviews)

---

## How the model works

- Preprocess the Alexa reviews dataset.
- Extract features and vectorize text.
- Train a sentiment analysis pipeline using scikit-learn.
- Export the model and deploy with a Flask web app.
- Users can input their review and receive instant positive/negative classification.

---

## Steps to run on Windows

* **Prerequisites:** [Python 3.9](https://www.python.org/downloads/) (make sure Python is added to [PATH](https://medium.com/co-learning-lounge/how-to-download-install-python-on-windows-2021-44a707994013)), and [Git](https://git-scm.com/download/win) Client

* Open GIT CMD or Windows Terminal → navigate to working directory → Clone this Github Repo:
    ```
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```
* Create a virtual environment
    * Install virtual environment:
        ```
        pip install virtualenv
        ```
    * Create virtual environment by the name ENV:
        ```
        virtualenv ENV
        ```
    * Activate ENV:
        ```
        .\ENV\Scripts\activate
        ```
* Install project dependencies:
    ```
    pip install -r requirements.txt
    ```
* Run the project:
    ```
    python app.py
    ```
    - Look for the local host address printed, e.g. `127.0.0.1:5000`
    - Open this in your browser to use the app

* To close → Go back to Terminal, type `ctrl+c`  
* Deactivate Virtual Environment:
    ```
    deactivate
    ```

---

## Steps to run on Mac

* **Prerequisites:** [Python 3.9](https://www.python.org/downloads/)
* Open Terminal → navigate to working directory → Clone this Github Repo:
    ```
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```
* Create a virtual environment
    * Install virtual environment:
        ```
        pip install virtualenv
        ```
    * Create virtual environment by the name ENV:
        ```
        virtualenv ENV
        ```
    * Activate ENV:
        ```
        source ENV/bin/activate
        ```
* Install project dependencies:
    ```
    pip install -r requirements.txt
    ```
* Run the project:
    ```
    python app.py
    ```
    - Look for the local host address printed, e.g. `127.0.0.1:5000`
    - Open this in your browser to use the app

* To close → Go back to Terminal, type `ctrl+c`  
* Deactivate Virtual Environment:
    ```
    deactivate
    ```

---

## Project Structure

├── app.py
├── requirements.txt
├── README.md
├── notebooks/
│ └── sentiment_analysis.ipynb
├── static/
└── templates/


---

## Troubleshooting

- **Install/build errors:** Some libraries need MS C++ Build Tools. [Download here](https://visualstudio.microsoft.com/visual-cpp-build-tools/).
- **Insufficient storage:** Use a folder or drive with enough free space.
- **Git not recognized:** Reinstall Git, select "Git from the command line and also from 3rd-party software" during setup.

---

## License

This project is for educational purposes only.

---

**Project by Ram Trinadh**
