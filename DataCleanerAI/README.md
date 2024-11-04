
# DataCleanerAI

DataCleanerAI is an interactive Python library designed to analyze, clean, and adapt to user preferences for data cleaning tasks, particularly suited for large financial datasets.

## Features

- **Automatic Analysis**: Detects missing values, outliers, and type inconsistencies.
- **Interactive Prompting**: Prompts users for cleaning actions based on identified issues.
- **Learning Memory**: Remembers user preferences and adapts to similar datasets in the future.
- **ML-Based Outlier Detection**: Uses Isolation Forest for outlier detection in numeric columns.
- **Reset and Retrain Options**: Clear memory and start fresh when needed.

## Installation

```bash
pip install .
```

## Usage

```python
import DataCleanerAI as dca

# Clean a dataset interactively
cleaned_df = dca.clean_data('financial_data.csv')

# Reset memory
dca.reset_data_cleaner_memory()
```

## License
MIT License
    