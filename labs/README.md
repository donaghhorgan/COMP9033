# Lab notebooks and data

Lab notebooks and data for the module [*COMP9033 - Data Analytics*](http://tel.cit.ie/msc-in-cloud-computing).

## Usage

Lab work is provided in the form of [Jupyter Notebooks](https://jupyter.org/). Notebooks can be run either directly or through Docker.

### Direct use

To run notebooks 01-09, you will need Python, IPython, Jupyter Notebook and the following Python packages:

- numpy
- scipy
- pandas
- matplotlib
- scikit-learn

To start the notebook server, run the following command:

    jupyter notebook

For notebooks 10-12, you will also need access to a local pyspark kernel or, alternatively, you can use Docker (see below).

### Docker

Lab notebooks 01-09 can also be run with the [*Jupyter Data Science Notebook*](https://github.com/jupyter/docker-stacks/tree/master/datascience-notebook) Docker image. To start the notebook, run the following command:

    docker run -it --rm -p 127.0.0.1:8888:8888 -v /path/to/labs:/home/jovyan/work jupyter/datascience-notebook

For more information, see the [notebook documentation](https://github.com/jupyter/docker-stacks/tree/master/datascience-notebook).

Labs 10-12 can be run with the [*Jupyter PySpark Notebook*](https://github.com/jupyter/docker-stacks/tree/master/pyspark-notebook) Docker image. To start the notebook, run the following command:

    docker run -it --rm -p 127.0.0.1:8888:8888 -v /path/to/labs:/home/jovyan/work jupyter/pyspark-notebook

For more information, see the [notebook documentation](https://github.com/jupyter/docker-stacks/tree/master/pyspark-notebook).

## License

The lab notebooks are made available under the [GNU General Public License (version 3)](../LICENSE).
