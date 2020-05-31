
# Pneumonia recognition in x-ray images
## Project by Ana Carolina Gontijo Graça for the Machine Learning - UFMG 2019.1 course

# The data set:
The data set used was obtained in Kaggle, in the link below:
    https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

  The "chest-xray-pneumonia/chest_xray/" folder must be in the current diretory where you run the notebook locally.

# Execution time:
  As it is a deep-learning project, its execution is really slow for a normal computer. If the program takes too long to run locally, uncomment lines 6, 7 and 8 from the python notebook's first cell and running in google colab with GPU acceleration the execution time is reduced considerably. It's important to notice that the images loading part will be slower in google colab, but the trainings will be faster. It's also important to notice that uncommenting the specified lines will activate the use of Google Drive as a data source, and so it will be necessary to uploads the data to that drive.





# Python/Flask tutorial sample for Visual Studio Code

* This sample contains the completed program from the tutorial, make sure to visit the link: [Using Flask in Visual Studio Code](https://code.visualstudio.com/docs/python/tutorial-flask). Intermediate steps are not included.
* It also contains the Dockerfile and uwsgi.ini files necessary to build a container with a production server. The resulting image works both locally and when deployed to Azure App Service. See [Deploy Python using Docker containers](https://code.visualstudio.com/docs/python/tutorial-deploy-containers).

## Navigation

The `startup.py` file, for its part, is specifically for deploying to Azure App Service on Linux without containers. Because the app code is in its own *module* in the `hello_app` folder (which has an `__init__.py`), trying to start the Gunicorn server within App Service on Linux produces an "Attempted relative import in non-package" error. The `startup.py` file, therefore, is just a shim to import the app object from the `hello_app` module, which then allows you to use startup:app in the Gunicorn command line (see `startup.txt`).

## Contributing

Contributions to the sample are welcome. When submitting changes, also consider submitting matching changes to the tutorial, the source file for which is [tutorial-flask.md](https://github.com/Microsoft/vscode-docs/blob/master/docs/python/tutorial-flask.md).

Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot automatically determines whether you need to provide a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

## Additional details

* This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
* For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
* Contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
