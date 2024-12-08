# plagiarism-checker-python

This repository contains the source code for a Python software that uses cosine similarity to identify plagiarism in text documents.

# How is it work?

If you're wondering how plagiarism detection works with textual data, it's not as hard as you may imagine.

Since computers are known to be good with numbers, the raw textual data is converted into vectors, which are arrays of numbers. From there, we use our fundamental understanding of vectors to calculate how similar two text documents are.

A simple example of how to accomplish it can be found in this repository.

# Get Start
You may need to install dependencies as shown below before you can start experimenting with the source code;

pip3 install -r requirements.txt

# Running the App

You must have text documents with the.txt extension in your project directory in order to run this code. The script will automatically load all documents with that extension when you execute it, and it will then calculate how similar they are, as you can see below;

$->cd Plagiarism-checker-Python
$->python app.py
('requirements.txt', 'trinadh.txt', np.float64(0.0))
('saith.txt', 'trinadh.txt', np.float64(0.09428205706431231))
('ramu.txt', 'trinadh.txt', np.float64(0.059249637743117624))
('ramu.txt', 'saith.txt', np.float64(0.04738069735929998))
('ramu.txt', 'requirements.txt', np.float64(0.0))
('requirements.txt', 'saith.txt', np.float64(0.0))


# A Python Library?
Consider Pysimilar if you would want to compare strings and documents using a Python library rather than spending time creating the vectorizers yourself.

# Issues
In case you have any difficulties or issues while trying to run the script you can raise an issue.

# Pull Requests
If you have something to add, I welcome pull requests on improvement; your helpful contribution will be merged as soon as possible.
