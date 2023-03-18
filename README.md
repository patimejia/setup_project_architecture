# Project File Structure Generator

This is a Python script that generates an example file structure for a Python project, organized according to best practices and guidelines.

## Usage

To use this script, simply run it with Python:

```
python generate_file_structure.py
```

This will create a new directory called `project_name` with the following structure:

```
project_name/
    src/
        __init__.py
        main.py
        submodules/
            __init__.py
            submodule1.py
            submodule2.py
    tests/
        __init__.py
        test_main.py
        test_submodules/
            __init__.py
            test_submodule1.py
            test_submodule2.py
    data/
        __init__.py
        input/
            input_file1.txt
            input_file2.csv
        output/
            output_file1.txt
    docs/
        conf.py
        index.rst
        api/
            __init__.rst
            main.rst
            submodules/
                __init__.rst
                submodule1.rst
                submodule2.rst
        _static/
            style.css
    scripts/
        script1.py
        script2.py
    setup.py
    requirements.txt
    .gitignore
    LICENSE
    README.md
```

## Customization

You can customize the file structure generated by this script by modifying the variables defined at the top of the file:

```python
PROJECT_NAME = 'my_project'
SCRIPTS = ['script1.py', 'script2.py']
# ...
```

You can change the project name, add or remove scripts, and modify other aspects of the file structure to suit your needs.

## Contributing

Contributions to this repository are welcome and encouraged! If you have suggestions for improving the file structure or the code organization, please submit a pull request. Let's keep improving our best practices and methods for organizing code and file directories in Python projects!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
