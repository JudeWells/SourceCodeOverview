# SourceCodeSummary

SourceCodeSummary is a Python script that generates comprehensive summaries of Python projects for Large Language Models (LLMs). It provides a concise summary of the project structure, source code, dependencies, and data files, making it easier for LLMs to understand and analyze the codebase.

## Features

- Generates a hierarchical representation of the project structure, including directories and files
- Includes the complete source code for each Python file
- Provides a summary of data files (CSV and TXT) with truncated content
- Excludes compiled files, standard files, and virtual environment directories
- Customizable options for maximum lines to include from data files

## Installation

1. Clone the repository:

```bash
git clone https://github.com/judewells/SourceCodeSummary.git
```

## Usage

To generate a summary of a Python project, run the following command:

```bash
python summary.py <input_path> <output_path>
```

- `<input_path>`: Path to the directory containing the Python project you want to summarize.
- `<output_path>`: Path to the output file where the summary will be saved.

For example:

```bash
python summary.py /path/to/python/project /path/to/output/summary.txt
```

The script will generate a summary of the Python project and save it to the specified output file.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).



---
