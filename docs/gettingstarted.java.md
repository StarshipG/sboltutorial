## Getting started .... using Java

In this example, we are going to open an SBOL file containing the
expression casette for a single protein:
           [http://sbolstandard.org/examples/example_minimal.sbol.rdf]

We are going to use 
[libSBOLj](http://sbolstandard.org/software/libsbol/java/) 
to extract the sequence of the full construct. We will then piece
together a new construct which replaces the ribosomal binding site between
promoter and protein-coding sequence. We then save the new construct in a new
SBOL record.

### Install dependencies

You will need [Java](http://java.org) (v. 2.7 or 3.x.) and
[libSBOLj](http://sbolstandard.org/software/libsbol/java/).

Detailed installation instructions can be found [here](). With basic development
tools installed, the following should work:

  ```bash
  insert installation command(s)
  ```

### Import and use SBOL files

1. Load an SBOL file

2. Extract the full DNA sequence from SBOL

3. List the sub-components of a DNA construct

4. Extract the sequence and annotation of a sub-component


### Export SBOL

5. Create a new construct from two old and one new sub-components

6. Export the new Component (everything)

7. Export the new Component (only what has changed)
