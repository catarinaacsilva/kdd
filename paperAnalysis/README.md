# Data Mining: Paper analysis

This project tries to replicate the work done in the following paper: "Attack and anomaly detection in IoT sensors in IoT sites using machine learning approaches".
The objective of the paper is to detect attacks and anomaly detection in the Internet of Things (IoT).

Furthermore, the work contains several improvements:
1. deal with the unbalanced dataset (**bonus00.ipynb**)
2. try different approaches to encode categorial values (**bonus01.ipynb**)
3. apply the previous improvemtns plus feature selection (**bonus02.ipynb**)

## Requirements

The work was done in Jupiter Notebook and Python 3.
The remaining requirements will be installed within the virtual environment.

## How to run

Create and activate a virtual environment

```
python3 -m venv venv
source venv/bin/activate
```

Install the requirements within the virtual environment

```
pip install -r requirements.txt
```

Start the jupiter notebook

```
jupyter notebook --no-browser
```

After the notebook started, copy the url and open it in a browser.

## Notebook description

1. **main.ipynb** - replication of the work on the paper
2. **bonus00.ipynb** - deal with the unbalanced dataset
3. **bonus01.ipynb** - try different approaches to encode categorial values
4. **bonus02.ipynb** - apply the previous improvemtns plus feature selection

## Authors

* **Catarina Silva** - [catarinaacsilva](https://github.com/catarinaacsilva)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
