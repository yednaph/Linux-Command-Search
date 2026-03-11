<b> Some example usage of `conda` command</b>

To list environments: `conda env list`

To initialise an environment: `conda create --name <environment_name>`

To initialise an environment with <b>python3.10</b>: `conda create --name <environment_name> python=3.10`

To install from a file: `conda install --file <requirements.txt>`

To clone an environment: `conda create --clone <old_environment_name> --name <new_environment_name>`

To activate a virtual environment: `conda activate <environment_name>`

To deactivate a virtual environment: `conda deactivate`

To remove an environment: `conda env remove --name <environment_name>` or conda env remove --prefix <path/to/env>`

To list all packages in an environment: `conda list --name <environment_name>`

To list packages in an activated environment: `conda list`
