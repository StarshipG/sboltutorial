# SBOL Tutorial
![](https://readthedocs.org/projects/pip/badge/?version=latest)
####SBOL tutorial(s) on [readTheDocs.org](http://rtd.org)


The final tutorial page can be found here: http://sboltutorial.readthedocs.org

It is set up such that any modifications to the github repository will automatically trigger recompilation of the html on readthedocs.org. 

For local compiling, you need [Sphinx](http://sphinx-doc.org/). Once this is in place:

```sh
cd docs
make html
```

This will create a new HTML tree in `docs/_build` which you can browse by
pointing your web browser to `index.html`


### Syntax

Doc files can either be in reStructuredText (.rst) or markdown (.md) format. reStructuredText has many more formatting options and is the only format for creating table of contents. However, markdown is somewhat easier to read / edit so it should perhaps be used for "end documents".

Further reading:

  * [ReadTheDocs getting started](http://docs.readthedocs.org/en/latest/getting_started.html)


### Contribute!

Fork this repository, add / edit the documentation and send back a pull request.

## License

released under the Apache 2.0 [license](./LICENSE).