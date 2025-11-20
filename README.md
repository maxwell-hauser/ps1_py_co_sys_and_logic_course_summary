# Computer Systems and Logic - Interactive Examples

This directory contains runnable Python scripts that demonstrate the key concepts from each chapter of the Computer Systems and Logic course.

## Root Directory Structure

Folders:
- **py_01_signal_and_num_sys_gh/**
- **py_02_analog_signals_gh/**
- **py_03_digital_signals_gh/**
- **py_04_number_systems_gh/**
- **py_05_conversions_gh/**
- **py_06_complements_gh/**
- **py_07_signed_magnitude_gh/**
- **py_08_binary_addition_subtraction_gh/**
- **py_09_floating_point_representation_gh/**
- **py_10_binary_coded_decimals_gh/**
- **py_11_coding_schemas_gh/**
- **py_12_parity_bits_gh/**
- **py_13_clock_signals_gh/**
- **py_14_transmission_types_gh/**
- **py_15_transmission_methods_gh/**
- **py_16_course_summary_and_exercises_gh/**

Files:
- **run_examples.py** (main interactive launcher)
- **README.md** (this file)
- **.github/** (root CI/CD workflows)
- **.github_workflow_template.yml** (workflow template)
- **.github_release_template.yml** (release workflow template)
- **.gitignore**
- **scripts/** (automation scripts)
    - add_workflows.ps1
    - update_repos.ps1
    - rename_chapter_files.ps1
    - git_init_and_push.ps1
    - test_all_chapters.ps1

## Quick Start

### Option 1: Interactive Menu (Recommended)

Run the main menu script to browse and select chapters:

```bash
python run_examples.py
```

This provides an interactive menu where you can:
- Select individual chapters to run
- Run all chapters sequentially
- Navigate easily between examples

### Option 2: Run Individual Chapters

Run any chapter directly:

```bash
python py_01_signal_and_num_sys_gh/py_01_signal_and_num_sys_gh.py
python py_05_conversions_gh/py_05_conversions_gh.py
python py_12_parity_bits_gh/py_12_parity_bits_gh.py
# ... etc
```

## Requirements

- Python 3.6 or higher
- No external dependencies required (uses only Python standard library)

## Features

Each chapter script includes:
- **Clear examples** demonstrating key concepts
- **Visual representations** where applicable
- **Step-by-step explanations** of calculations
- **Real-world applications** and use cases
- **Summary of key concepts** at the end

## Learning Path

For best learning experience, follow the chapters in order:

1. **Fundamentals (Ch 1-5)**: Signals, number systems, and conversions
2. **Binary Arithmetic (Ch 6-8)**: Complements, signed numbers, and arithmetic
3. **Data Representation (Ch 9-11)**: Floating point, BCD, and character encoding
4. **Communication (Ch 12-15)**: Error detection, timing, and transmission methods

## Examples

### Running Chapter 5 (Conversions):
```bash
$ python py_05_conversions_gh.py

============================================================
CHAPTER 5: Number System Conversions
============================================================

--- Example 1: Decimal to Binary (Division Method) ---
Convert (35)_10 to binary:
  35 ÷ 2 = 17 remainder 1
  17 ÷ 2 = 8 remainder 1
  8 ÷ 2 = 4 remainder 0
  4 ÷ 2 = 2 remainder 0
  2 ÷ 2 = 1 remainder 0
  1 ÷ 2 = 0 remainder 1
Reading remainders bottom-to-top: (100011)_2
...
```

### Using Interactive Menu:
```bash
$ python run_examples.py

======================================================================
          COMPUTER SYSTEMS AND LOGIC
               Interactive Examples
======================================================================

Select a chapter to run:

   1. Chapter 1   - Signals and Number Systems
   2. Chapter 2   - Analog Signals
   3. Chapter 3   - Digital Signals
   ...
  16. Run ALL chapters sequentially
   0. Exit

Enter your choice: 5
```

## Customization

Each script is self-contained and can be modified to:
- Add your own examples
- Change visualization styles
- Experiment with different values
- Add additional test cases

## Corresponding Course Materials

These examples complement the markdown files in each project directory:
- `py_01_signal_and_num_sys_gh/py_01_signal_and_num_sys_gh.md`
- `py_02_analog_signals_gh/py_02_analog_signals_gh.md`
- `py_03_digital_signals_gh/py_03_digital_signals_gh.md`
- `py_04_number_systems_gh/py_04_number_systems_gh.md`
- `py_05_conversions_gh/py_05_conversions_gh.md`
- `py_06_complements_gh/py_06_complements_gh.md`
- `py_07_signed_magnitude_gh/py_07_signed_magnitude_gh.md`
- `py_08_binary_addition_subtraction_gh/py_08_binary_addition_subtraction_gh.md`
- `py_09_floating_point_representation_gh/py_09_floating_point_representation_gh.md`
- `py_10_binary_coded_decimals_gh/py_10_binary_coded_decimals_gh.md`
- `py_11_coding_schemas_gh/py_11_coding_schemas_gh.md`
- `py_12_parity_bits_gh/py_12_parity_bits_gh.md`
- `py_13_clock_signals_gh/py_13_clock_signals_gh.md`
- `py_14_transmission_types_gh/py_14_transmission_types_gh.md`
- `py_15_transmission_methods_gh/py_15_transmission_methods_gh.md`
- `py_16_course_summary_and_exercises_gh/py_16_course_summary_and_exercises_gh.md`

Each project is maintained in its own GitHub repository at:
- https://github.com/maxwell-hauser/py_01_signal_and_num_sys
- https://github.com/maxwell-hauser/py_02_analog_signals
- https://github.com/maxwell-hauser/py_03_digital_signals
- https://github.com/maxwell-hauser/py_04_number_systems
- https://github.com/maxwell-hauser/py_05_conversions
- https://github.com/maxwell-hauser/py_06_complements
- https://github.com/maxwell-hauser/py_07_signed_magnitude
- https://github.com/maxwell-hauser/py_08_binary_addition_subtraction
- https://github.com/maxwell-hauser/py_09_floating_point_representation
- https://github.com/maxwell-hauser/py_10_binary_coded_decimals
- https://github.com/maxwell-hauser/py_11_coding_schemas
- https://github.com/maxwell-hauser/py_12_parity_bits
- https://github.com/maxwell-hauser/py_13_clock_signals
- https://github.com/maxwell-hauser/py_14_transmission_types
- https://github.com/maxwell-hauser/py_15_transmission_methods
- https://github.com/maxwell-hauser/py_16_course_summary_and_exercises

## Contributing

Feel free to:
- Add more examples
- Improve visualizations
- Fix bugs or typos
- Enhance documentation

## Authorship
Authored by Maxwell Hauser on November 19, 2025

## License
MIT License

---

**Happy Learning!**

For questions or issues, refer to the main course materials in the parent directories.
