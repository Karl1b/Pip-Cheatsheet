## Pip-Cheatsheet
Quick Guide and cheatsheet for pip

Pip is a virtual enviroment that is used to keep track of different versions of dependencies. 

Create a new virtual enviroment (second venv is the name):
```console
python -m venv venv
```

Activate the enviroment:
```console
 source venv/bin/activate
```

Deactivate the enviroment:
```console
deactivate
```

Search for a package:
```console
pip search query
```
Install a dependency:
```console
pip install nameofdependency
```

Install a specific version:
```console
pip install nameofdependency==version
```
Upgrade a dependency:
```console
pip install --upgrade nameofdependency

```
Uninstall a dependency
```console
pip uninstall nameofdependency
```

Install from a list of requierements:
```console
pip install -r requierements.txt
```

Lists out all current dependencies to requierements.txt:
```console
pip freeze > requierements.txt
```

Delete the virtualenviroment:
```console
rm -rf venv
```







