# AI Assignment Agent

This script is designed to evaluate the performance of a generative AI model in answering questions accurately based on provided data. It utilizes the Google Gemini And OpenAI ChatGPT API's to generate answers to a set of questions derived from a JSON file containing training data. The script processes each question, formats it according to specific instructions, and then compares the AI-generated answers to the actual answers within a defined tolerance level to determine correctness.

Key Features:
- Loads training data from a JSON file and iterates through a specified number of questions.
- Utilizes Google Gemini and OpenAI API's for generating answers.
- Formats the input for the AI model according to detailed instructions, ensuring the model receives all necessary context.
- Compares the AI-generated answers to the actual answers, taking into account a tolerance for numerical comparison.
- Updates and displays a plot in real-time to visualize the number of correct answers versus the number of questions asked using Plotly.

Requirements:
- Google Generative AI and Open AI libraries
- Set your own API Keys as system variables
- Plotly for visualization
- JSON for data handling
- OS, fpdf  and re (regular expression) modules for file and string operations

The script aims to provide a quantitative assessment of the AI model's accuracy in a controlled experimental setup, with potential applications in evaluating AI models for research assistance or data analysis tasks.
It will then auto generate a report which analyzes and compares the accuracies of the two models. The results for each model performance are detailed separately from the report for you to verify the reports accuracy.
 
