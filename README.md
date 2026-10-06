# Crew AI Crash Course

This repository is a hands-on introduction to building multi-agent AI systems with CrewAI. It contains a practical Jupyter notebook demo for customer support automation and a starter CrewAI project that can be extended for your own workflows.

## Repository structure

- `_Customer Support Automation.ipynb` — notebook-based example showing a customer support automation workflow.
- `my_project/` — a CrewAI starter project scaffold.
- `my_project/src/my_project/` — project source code and agent/task definitions.
- `my_project/knowledge/` — knowledge files used by the project.

## What this project demonstrates

- Building a multi-agent CrewAI workflow
- Defining agents and tasks in YAML/config files
- Running a small AI-powered automation flow
- Extending the sample project for custom use cases

## Prerequisites

- Python 3.10 to 3.13
- An OpenAI API key
- `uv` package manager for dependency handling

## Getting started

### 1. Clone the repo

```bash
git clone https://github.com/Lahu-Dhotre/crew-ai-crash-course.git
cd crew-ai-crash-course
```

### 2. Set up the CrewAI project

```bash
cd my_project
pip install uv
crewai install
```

### 3. Configure environment variables

Create a `.env` file in `my_project/` and add your API key:

```bash
OPENAI_API_KEY=your_api_key_here
```

### 4. Run the project

From the `my_project/` directory:

```bash
crewai run
```

This starts the crew and executes the tasks defined in the project configuration.

## Notebook usage

Open the notebook:

```bash
jupyter notebook "_Customer Support Automation.ipynb"
```

Use the notebook to explore the customer support automation example and adapt it to your own scenario.

## Project layout

```text
crew-ai-crash-course/
├── _Customer Support Automation.ipynb
├── .gitignore
├── README.md
└── my_project/
    ├── README.md
    ├── pyproject.toml
    ├── .gitignore
    ├── knowledge/
    └── src/
        └── my_project/
```

## Notes

This repository is designed as a learning and experimentation repo. The default sample project is a template, so you can customize the agent definitions, task logic, and workflow behavior to match your own use case.

## License

This project is provided for educational purposes and does not include an explicit license file unless added later.
