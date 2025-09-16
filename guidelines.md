
# Create venv
python -m venv venv_imageclasification

# Activate (Windows, vscode)
.\venv_imageclasification\Scripts\activate
# Activate (Windows, bash)
source ./venv_imageclasification/Scripts/activate


# Upgrade pip
pip install --upgrade pip

# Install the kernel, to attach it to jupyter 
pip install ipykernel

# Make the installed kerenle use your custome venv
<!-- python -m ipykernel install --name=venv_imageclasification -->
python -m ipykernel install --user --name=venv_imageclasification --display-name "Python (VenvImageClassification)"


# Check envs:
jupyter kernelspec list


# Start jupyter lab, or jupyter notebook
jupyter lab
jupyter notebook

# Deleting envs:
jupyter kernelspec uninstall imageclasification