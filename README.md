# GramSpel

GramSpel is a Python package that provides grammar checking and auto-correction capabilities.

## Installation

You can install GramSpel using pip:

```
pip install gramspel
```


## Usage

```python
from grammar_check import GrammarChecker

checker = GrammarChecker()
checker.set_language('en-GB')

# Grammar checking
grammar_errors = checker.grammar("This is a test sentence with a grammar mistake.")
print(grammar_errors)

# Spelling checking
spelling_errors = checker.spelling("This is a test sentence with a spelling mistake.")
print(spelling_errors)

# Grammar and spelling checking
spelling_grammar_errors = checker.spelling_grammar("This is a test sentence with both spelling and grammar mistakes.")
print(spelling_grammar_errors)

# Auto-correction
corrected_text = checker.auto_correct("Thiss is a test sentence with typoos.")
print(corrected_text)
```

Please refer to the documentation for detailed information on the available methods and their usage.

License
This project is licensed under the MIT License.
