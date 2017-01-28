# COMP9033 - Data Analytics: Lab notebooks

Lab notebooks for the module [*COMP9033 - Data Analytics*](http://courses.cit.ie/index.cfm/page/module/moduleId/11079).

## Usage

Lab work is provided in the form of [Jupyter Notebooks](https://jupyter.org/). To run the notebooks, you will need Python, IPython, Jupyter Notebook and the following Python packages:

- numpy
- scipy
- pandas
- matplotlib
- scikit-learn

To start the notebook server, run the following command:

    jupyter notebook

### Docker

The lab notebooks can also be run with the [*Jupyter Data Science Notebook*](https://github.com/jupyter/docker-stacks/tree/master/datascience-notebook) Docker image. To start the notebook, run the following command:

    docker run -it --rm -p 127.0.0.1:8888:8888 -v /path/to/labs:/home/jovyan/work jupyter/datascience-notebook

For more information, see the [notebook documentation](https://github.com/jupyter/docker-stacks/tree/master/datascience-notebook).

## License

The lab notebooks are made available under the [GNU General Public License (version 3)](../LICENSE).
