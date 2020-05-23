
# AI Content Machine: Post Generation and Engagement Metrics Prediction Agent

This project implements an agent that interacts with a CSV file containing data and metrics from various posts. The agent performs two main tasks:

1. **Generation of new posts**: Based on historical data, the agent generates new content.
2. **Engagement metrics prediction**: The agent predicts the engagement metrics of the new posts based on the historical data.

## Features

- Loads data from a CSV file containing metrics of previous posts.
- Automatically generates new posts.
- Predicts engagement metrics using the historical post data.
- User-friendly interface that integrates functionalities via a visual interface based on Langflow.

## Dependencies

This project uses [Langflow](https://github.com/logspace-ai/langflow) as the workflow framework, which allows you to easily configure and connect different components. The main dependencies are:

- Python 3.8 or higher
- Langflow
- AstraDB

## Installation

Follow the steps below to set up the project:

1. Install Langflow using `pip`:
   ```bash
   pip install langflow
   ```

2. Run Langflow:
   ```bash
   langflow run
   ```

3. Open your browser and go to `http://localhost:7860` to access the Langflow graphical interface.

## Configuration

After starting Langflow, follow these steps to configure the agent:

1. Upload the "Task Tiktok videos agent.json" inside the designated section:  
   <img src="./guidance/first_screenshot.png" alt="Task Tiktok videos agent" width="800" height="600"/>
2. In the Langflow interface, enter the necessary **API keys**. You must provide an OpenAI API Key and your AstraDB settings, such as the URL and key.
   <img src="./guidance/second_screenshot.png" alt="API KEY" width="800" height="600"/>
3. Enter the **CSV file** in the corresponding component:  
   <img src="./guidance/third_screenshot.png" alt="CSV file upload" width="800" height="600"/>
   
   Also, upload the CSV file into the CSV agent section:  
   <img src="./guidance/fourth_screenshot.png" alt="CSV agent upload" width="800" height="700"/>


## Usage

- The agent will load data from the CSV and allow you to generate new posts based on previous metrics.
- It will also predict the engagement metrics of the new posts using the historical data.

Simply run Langflow and provide the correct information in the graphical interface to execute new predictions or generate new posts.

