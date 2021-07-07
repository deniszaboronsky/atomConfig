# Set up
The following code will set up Atom as a Python IDE with effective linting, PEP8 detection and autocomplete. This works best with a vanilla python install, and since Atom is fully open source means there is no risk of license misuse for python dev.

Pip install required first:
```
pip install flake8
pip install autopep8
pip install jedi
```

Then install atom and clone the repo and then run the following with the correct address for the `package.list`, if you change directory to the location the below code will work.

```
apm install --packages-file package.list
```
