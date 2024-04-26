# My Learning Repository 📚

Welcome to my personal Learning Repository! This repository is my go-to resource for consolidating various learning materials sourced from different platforms such as YouTube tutorials, official documentation, and more. It serves as my reference point for enhancing my skills and exploring new topics.

## Purpose 🎯

The main purpose of this repository is to organize and store learning materials for my personal use and reference. By curating content from diverse sources, I aim to create a comprehensive collection that caters to my learning goals and interests.

## Contents 📝

### 1. Tensorflow Tutorial for Python in 10 Minutes by Nicholas Renotte (tensorflow)
- [YouTube Link](https://www.youtube.com/watch?v=6_2hzRopPbQ)
    1. 
- [Documentation](https://www.tensorflow.org/api_docs/python/tf/all_symbols)
    1. Notes
- [Notes for Jupyter in VSCode]
    1. For VSCode, go inside your project folder and initialize a virtual environment using "python -m venv env" and activate it using ".\env\Scripts\activate.Ps1" in PowerShell.
    2. If you are using Jupyter Notebook, run "pip install ipykernel" first before installing other dependencies using "pip install -r requirements.txt".
    3. Aside from #2, 

    these are all for Python scripts, jupyter notebooks have a different way of activating the virtual environment using venv instead, also next time, 1 workspace = 1 virtual environment

    jupyter kernelspec uninstall env



## Python Virtual Environments in VS Code: Notebooks & Scripts

**Let's set up virtual environments for your Python projects in VS Code!**

**1. Get Ready:**

- Make sure you have Python installed (`python --version` or `python3 --version`).
- Grab the Python extension for VS Code from the Extensions marketplace.

**2. Create Your Environment:**

- Open VS Code, navigate to your project directory, and open the terminal (**Terminal > New Terminal**).
- Create a virtual environment named `env` (change the name if you prefer):

   ```bash
   python -m venv env  # Windows
   python3 -m venv env  # macOS/Linux
   ```

**3. Activate It:**

- Windows: `.\env\Scripts\activate.ps1`
- macOS/Linux: `source env/bin/activate`
- Your terminal prompt will show the active environment (e.g., `(env)your_username...`).

**4. Install Dependencies (Notebooks & Scripts):**

- Create a `requirements.txt` file in your project directory, listing your needed packages (one per line).
- Install them all at once: `pip install -r requirements.txt`

**5. Jupyter Notebook (Optional):**

- If you use Jupyter Notebooks, install `ipykernel` within the active environment: `pip install ipykernel`
- Launch Jupyter Notebook from the terminal, specifying your notebook file path:

   ```bash
   jupyter notebook PATH_TO_YOUR_NOTEBOOK.ipynb
   ```

**6. Running Python Scripts:**

- Keep the virtual environment active (step 3).
- Navigate to your project directory in the terminal.
- Run your script: `python my_script.py`

**7. Deactivate (Optional):**

- When you're done, deactivate the environment: `deactivate`

**Pro Tips:**

- Create separate virtual environments for each project to avoid dependency conflicts.
- Always activate the virtual environment when working on a specific project to use the correct dependencies.

**Skip the `jupyter kernelspec uninstall env` command** for now. It's for advanced kernel management.



I'd be glad to create improved documentation for setting up virtual environments for Python in VS Code, covering both Jupyter Notebooks and scripts:

**Setting Up Virtual Environments for Python in VS Code**

**1. Prerequisites:**

- Ensure you have Python installed on your system. You can check by running `python --version` or `python3 --version` in your terminal.
- Download and install the Python extension for VS Code from the Extensions marketplace.

**2. Creating a Virtual Environment:**

- Open VS Code and navigate to your project directory.
- Open the integrated terminal (**Terminal > New Terminal**).
- Run the following command to create a virtual environment named `env` (replace `env` with your desired name):

   ```bash
   python -m venv env
   ```

   - On macOS or Linux:

     ```bash
     python3 -m venv env
     ```

**3. Activating the Virtual Environment:**

   **Windows:**

     ```bash
     .\env\Scripts\activate.ps1
     ```

   **macOS/Linux:**

     ```bash
     source env/bin/activate
     ```

- Your terminal prompt will now indicate that the virtual environment is active (e.g., `(env)your_username@your_machine:~/project_directory$`).

**4. Installing Dependencies (for both Jupyter Notebooks and Scripts):**

- Create a file named `requirements.txt` in your project directory. List all the Python packages you need for your project in this file, one per line (e.g., `numpy`, `pandas`, `matplotlib`).
- In the terminal, run the following command to install the dependencies from the `requirements.txt` file:

   ```bash
   pip install -r requirements.txt
   ```

**5. Using Jupyter Notebook (Optional):**

- If you plan to use Jupyter Notebooks, install the `ipykernel` package within the activated virtual environment:

   ```bash
   pip install ipykernel
   ```

- Create a Jupyter Notebook file (`.ipynb`) in your project directory.
- To launch Jupyter Notebook within the activated virtual environment, run the following command (replace `PATH_TO_YOUR_NOTEBOOK` with the actual path to your notebook file):

   ```bash
   jupyter notebook PATH_TO_YOUR_NOTEBOOK.ipynb
   ```

**6. Using Python Scripts:**

- To run Python scripts from the command line, make sure the virtual environment is activated (refer to step 3).
- Navigate to your project directory in the terminal.
- Run your Python script using the `python` command (e.g., `python my_script.py`).

**7. Deactivating the Virtual Environment (Optional):**

- Once you're finished working in the virtual environment, you can deactivate it by running the following command:

   ```bash
   deactivate  # For all operating systems
   ```

**Best Practices:**

- It's strongly recommended to create a separate virtual environment for each project to isolate dependencies and prevent conflicts between projects.
- Activate the virtual environment whenever you work on a specific project to ensure you're using the correct dependencies.

**Additional Notes:**

- The `jupyter kernelspec uninstall env` command is not typically used in this context. It's more relevant for managing Jupyter kernels associated with specific environments. If you encounter issues with Jupyter kernels, refer to the official Jupyter documentation for troubleshooting steps.


### 2. Python Sentiment Analysis Project with NLTK and 🤗 Transformers. Classify Amazon Reviews!! by Rob Mulla (nlp-tutorial)
- [YouTube Link](https://www.youtube.com/watch?v=QpzMWQvxXWk)
    1. Notes
- [Hugging Face Models](https://huggingface.co/models)
    1. Notes

### 3. Power Bi Project End-to-end | Sales Dashboard | Beginners | Complete Project | Resume - 2024 by DataWolfs (powerbi-sales)
- [YouTube Link](https://www.youtube.com/watch?v=7IJ3fKB8nrw)
    1. Notes
- [Documentation](https://www.tensorflow.org/api_docs/python/tf/all_symbols)
    1. Notes

### 4. 🚖 Uber Data Analytics | End-To-End Data Engineering Project by Darshil Parmar (uber-analytics)
- [YouTube Link](https://www.youtube.com/watch?v=WpQECq5Hx9g)
    1. Notes
- [Documentation](https://www.tensorflow.org/api_docs/python/tf/all_symbols)
    1. Notes

## Contribution Guidelines 🤝

This repository is for personal use, but I'm open to suggestions and contributions that align with my learning objectives. If you have any resources or materials that you think would be valuable to add, feel free to reach out to me.

## Feedback and Suggestions 📣

I welcome any feedback or suggestions for improving this repository. If you have ideas for additional resources or ways to enhance existing content, please let me know.

## Disclaimer ⚠️

This repository is for my personal use and reference only. While I strive to ensure the accuracy and relevance of the content, I cannot guarantee its completeness or suitability for any specific purpose. Use your discretion when applying concepts learned from these materials.

---

Feel free to explore the contents and use them as a reference for your own learning journey! If you find the materials helpful, consider starring this repository to show your support.⭐✨
