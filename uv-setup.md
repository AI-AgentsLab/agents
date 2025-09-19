

Example : mkdir projects

check if git is installed or not
> git --version

# UV installation step :

1. https://docs.astral.sh/uv/

2. wsl installation 
> curl -LsSf https://astral.sh/uv/install.sh | sh

3. restart the wsl terminal window

4. version
> uv --version

----------------------------------


> uv sync --- we are not going to use it for now



# Setup Python Environment with uv

We’ll create a dedicated workspace for your project.

```
# Create project folder
mkdir cad-ai-agents && cd cad-ai-agents

# Create Python virtual environment (latest version)
uv venv --python 3.12

# Activate environment
source .venv/bin/activate

# To Deactivate UX environment , just type 
> deactivate

```


# to run something in uv use

> uv run python-file



# Setup your environment



