## Getting started .... using Python

In this example, we are going to open an SBOL file containing the
expression casette for a single protein:
           [http://sbolstandard.org/examples/example_minimal.sbol.rdf]

We are going to use 
[pySBOL](http://sbolstandard.org/software/libsbol/python-pysbol/) 
to extract the sequence of the full construct. We will then piece
together a new construct which replaces the ribosomal binding site between
promoter and protein-coding sequence. We then save the new construct in a new
SBOL record.

### Install dependencies

You will need [Python](http://python.org) (v. 2.7 or 3.x.) and
[pySBOL](http://sbolstandard.org/software/libsbol/python-pysbol/).

Detailed installation instructions can be found [here](). With python and [pip](https://pypi.python.org/pypi/pip) installed, the following should work:

**Note** take out the virtualenv stuff; `pip install pySBOL` is the minimal
          requirement

  ```bash
  sudo pip install virtualenv // if you haven't set up virtualenv before
  mkdir sboltesting; cd sboltesting
  virtualenv venv
  pip install pySBOL
  ```
You can now any time switch on your sbol development environment with:

  ```sh
  source venv/bin/activate
  ```

and leave it with:
    
  ```sh
  deactivate
  ```

### Import and use SBOL files

1. Load an SBOL file into Python

2. Extract the full DNA sequence from SBOL

3. List the sub-components of a DNA construct

4. Extract the sequence and annotation of a sub-component


### Export SBOL

5. Create a new construct from two old and one new sub-components

6. Export the new Component (everything)

7. Export the new Component (only what has changed)
