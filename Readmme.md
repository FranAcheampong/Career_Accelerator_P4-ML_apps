# 🚀 Friendly Web Interface for ML Projects with  Streamlit 🚀

## Description
*Machine learning models, regardless of their quality, remain ineffectual until they are deployed. Streamlit presents an opportunity by granting the capability to render our machine learning models beneficial to users worldwide. With a simple click on the link provided by Streamlit, individuals can conveniently access and interact with our models through the Streamlit interface. This remarkable feature empowers users to explore and manipulate the outcomes achieved by our models.*

## Summary
| Code      | Name        | Published Article |  Deployed App |
|-----------|-------------|:-------------:|------:|
| P4| CORPORATION FAVORITA GROCERY STORE SALES PREDICTION STREAMLIT APP|  [Read the Article](https://medium.com/@acheampongfrancis95/corporation-favorita-grocery-store-sales-prediction-streamlit-app-77ee89b9983e) | [Check the visuals on PowerBI](https://app.powerbi.com/groups/me/reports/3114c4fa-c8d8-46d8-98d3-102b0cadf47b/ReportSection) |

## Project Description
The Favorita Grocery Sales Forecasting dataset is a fascinating collection of data that provides a great opportunity for analysis and prediction. In this article, we will take a deep dive into the dataset, explore its various attributes, and analyze the sales patterns to build a robust sales forecasting model and answer some pertinent question on the dataset.

# 🚀 Friendly Web Interface for ML Projects with  Gradio 🚀

## Description
*In the realm of data-driven decision making, predicting customer churn is a critical task for businesses, particularly in the telecom industry. By leveraging machine learning algorithms and creating intuitive user interfaces, businesses can gain valuable insights into customer behavior and take proactive measures to retain their valuable clientele. In this article, we will explore how a user-friendly GUI was implemented using Gradio to streamline telecom churn prediction.*

## Summary
| Code      | Name        | Published Article |  Deployed App |
|-----------|-------------|:-------------:|------:|
| P4| Streamlining Telecom Churn Prediction with a User-Friendly GUI|  [Read the Article](https://medium.com/@acheampongfrancis95/streamlining-telecom-churn-prediction-with-a-user-friendly-gui-bebb83b370bd) | [Check the visuals on PowerBI](https://app.powerbi.com/groups/me/reports/3114c4fa-c8d8-46d8-98d3-102b0cadf47b/ReportSection) |

## Project Description


## Setup
You have two ways in order to setup and run this project.

### Manual Setup

For manual installation, you need to have [`Python3`](https://www.python.org/) on your system. Then you can clone this repo and being at the repo's `root :: friendly_web_interface_for_ML_models> ...`  follow the steps below:

- Windows:
        
        python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  

- Linux & MacOs:
        
        python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  

The both long command-lines have a same structure, they pipe multiple commands using the symbol **;** but you may manually execute them one after another.

1. **Create the Python's virtual environment** that isolates the required libraries of the project to avoid conflicts;
2. **Activate the Python's virtual environment** so that the Python kernel & libraries will be those of the isolated environment;
3. **Upgrade Pip, the installed libraries/packages manager** to have the up-to-date version that will work correctly;
4. **Install the required libraries/packages** listed in the `requirements.txt` file so that it will be allow to import them into the python's scripts and notebooks without any issue.

**NB:** For MacOs users, please install `Xcode` if you have an issue.



## App Execution
- Run the demo apps (being at the repository root):
        
  Gradio:
    
    - Demo

          python gradio_project/basic_demo/app.py

    - Teleco Churn prediction

          python gradio_project/classification/app.py
  


  - Go to your browser at the following address :
        
      http://127.0.0.1:7860/


  Streamlit: 

      streamlit run streamlit_project/basic_demo/app.py

  - Go to your browser at the following address :
        
      http://localhost:8501


## Screenshots

<table>
    <tr>
        <th>Gradio Teleco Churn Prediction</th>
    </tr>
    <tr>
        <td><img src="C:/Users/user/Desktop\AZUBI AFRICA/SecondPhase/LP4\Career_Accelerator_P4-ML_apps/screenshots/GradioInterface.PNG"/></td>
    </tr>
</table>

<table>
    <tr>
        <th>Streamlit Regression Analysis App</th>
    </tr>
    <tr>
        <td><img src="C:/Users/user/Desktop/AZUBI AFRICA/SecondPhase/LP4/Career_Accelerator_P4-ML_apps/screenshots/StreamlitApp.PNG"/></td>
    </tr>
</table>

## Resources
Here are some ressources you would read to have a good understanding of Gradio and Streamlit :
- [Get started with Streamlit](https://docs.streamlit.io/library/get-started/create-an-app)

- [Get started with Gradio](https://gradio.app/getting_started/)

## Contributing

Feel free to make a PR or report an issue 😃.

Oh, one more thing, please do not forget to put a description when you make your PR 🙂.

## Author
Acheampong Francis
Azubi Africa, Trainee

- [Acheampong Francis](https://medium.com/@acheampongfrancis95)
