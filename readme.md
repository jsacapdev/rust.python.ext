# Using rust in python

A simple example of using rust to create a module that can be consumed in python. Simplicity of python and performance of rust. All from [this](https://www.infoworld.com/article/3687744/how-to-write-python-extensions-in-rust-with-pyo3.html) article.

Create a virtual environment: 

`virtualenv venv`

Install `maturin` into it:

`pip install maturin`

Build the rust module:

`maturin dev -r`

Watch it get installed into the virtual environment:

`pip list`

Use it in your python.

Tidy.
