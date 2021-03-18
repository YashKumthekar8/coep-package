# coep-package

## For Updating the package

#### 1. Pull this Repository, Navigate into the package\coep_package folder and modify the package.
#### 2. Commit the changes
#### 3. ```cd``` into the parent directory of coep_package
#### 4. Run command ```py setup.py sdist```. After running this command you will find a dist folder in the same directory (Make sure you delete previous dist folder before running the mentioned command)
#### 5. Run command ```twine upload --repository-url https://upload.pypi.org/legacy/ dist/*```. Then command prompt will ask for credentails of your PyPI account. Enter them.
#### 6. A url will be provided on the command prompt. Visit that url and make sure latest version is uploaded properly on PyPI.
#### 7. Git new branch commit