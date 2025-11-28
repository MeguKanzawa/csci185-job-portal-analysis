# CSCI 185 - Job Portal Analysis 
## Final Project

## Project Description
In this app, given a job title, it parses Indeed.com and identifies recommended skillsets for the job title in the current job market.

## Installation

## Prerequisites

Ensure you have the following installed on your system:

* **Python** (version **3.12** preferred)

1. **Clone the repository:**

    ```bash
    git clone [https://github.com/MeguKanzawa/csci185-job-portal-analysis.git](https://github.com/MeguKanzawa/csci185-job-portal-analysis.git)
    cd csci185-job-portal-analysis
    ```

2.  **Create and activate a virtual environment.**
    * **Note**: Ensure you are not pushing `venv` (do not edit the `.gitignore`).

    * **macOS/Linux**
        ```bash
        python3.12 -m venv venv
        source venv/bin/activate
        ```
    * **Windows**
        ```bash
        py -3.12 -m venv venv
        .\venv\Scripts\activate
        ```

3.  **Install Dependencies:**

    ```bash
    pip install -r requirements.txt

---

## Usage

1.  **Select the Kernel:** Select the newly created `venv` as your Python kernel in your Jupyter environment.
2.  **Run the Notebook:** Run the cells in `parse_indeed.ipynb`.
