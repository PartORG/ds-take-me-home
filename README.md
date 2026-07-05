# Take me home Challenge

Collection of take me home challenges from various companies. Each file in this repository describes a take me home challenge, as given by the issue-ing company. Some are more or less reasonable.

Please make sure you do not distribute this repository or the datasets as they do come from real companies.

## Features

- **Comprehensive Challenge Collection**: A curated set of challenges from different companies to help learners and professionals improve their data science and analytics skills.
- **Real-world Data**: Challenges are based on real-world datasets, providing practical experience in handling and analyzing data.
- **Detailed Deliverables**: Each challenge includes detailed deliverables such as notebooks with EDA/Modelling, code, visualizations, conclusions, and documented data questions/tasks.

## How It Works

The repository is structured to provide a clear workflow for participants:

1. **Read the Challenge Description**: Each challenge file (e.g., `data_scientist_triad.md`) contains a detailed description of the task.
2. **Connect to Data Source**: Participants need to connect to the `ds-sql-playground` database using the provided credentials to access the necessary datasets.
3. **Complete the Challenge**: Participants are expected to complete the challenge within the allocated time, ensuring all deliverables are met.
4. **Submit Your Work**: The completed work should be submitted according to the company's guidelines.

## Technology Stack

| Technology | Purpose |
|------------|---------|
| SQL        | For querying and analyzing data in the `ds-sql-playground` database. |
| Python     | For data manipulation, analysis, and visualization using libraries like Pandas, NumPy, Matplotlib, and Seaborn. |
| Jupyter Notebook | For creating and presenting the deliverables, including EDA/Modelling, code, visualizations, and conclusions. |

## Requirements

- **Python**: Ensure Python is installed on your system.
- **Jupyter Notebook**: Install Jupyter Notebook using `pip install notebook`.
- **Database Access**: Access to the `ds-sql-playground` database with the provided credentials.

## Installation

To get started, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/PartORG/ds-take-me-home.git
   cd ds-take-me-home
   ```

2. Install required Python packages:
   ```sh
   pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary
   ```

3. Connect to the `ds-sql-playground` database using your credentials.

## Configuration

No specific configuration is required for this repository. Ensure you have the necessary credentials and access rights to connect to the database.

## Quick Start

1. Open a Jupyter Notebook:
   ```sh
   jupyter notebook
   ```

2. Navigate to the challenge directory (e.g., `data_scientist_triad.ipynb`).

3. Follow the instructions in the notebook to complete the challenge.

## Usage

To work on a specific challenge, follow these steps:

1. Open the corresponding Jupyter Notebook file.
2. Connect to the database using the provided credentials.
3. Perform EDA and modeling as described in the challenge.
4. Document your findings and conclusions in the notebook.

## Project Structure

```
ds-take-me-home/
├── .github/workflows/
│   ├── add_issue_to_done.yml
│   ├── add_issue_todo.yml
│   ├── add_pr_in_progress.yml
│   └── add_pr_to_done.yml
├── .gitignore
├── README.md
├── alcemy_coding_challenge.md
├── data_analyst_artsy.md
├── data_science_prognostica_de.md
├── data_scientist_triad.md
├── dlt_solutions_engineering.md
├── dlt_working_student.md
├── dlt_working_student_teaching.md
├── images/
│   └── alcemy.png
└── product_analyst_amboss.md
```

- **.github/workflows/**: Contains GitHub Actions workflows for managing issues and pull requests.
- **README.md**: This file.
- **alcemy_coding_challenge.md**, **data_analyst_artsy.md**, etc.: Each file contains a detailed description of a take me home challenge.

## Development

No specific development workflow is required for this repository. Contributions are welcome in the form of bug reports, feature requests, and pull requests.

## Testing

This repository does not include automated tests.

## Limitations

- Challenges may require specific knowledge or tools that are not covered by this repository.
- The quality and relevance of challenges depend on the companies providing them.

## License

This project is open-source and available under the [MIT License](LICENSE).