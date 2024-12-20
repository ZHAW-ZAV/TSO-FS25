# Admin notes

### Google Colab environments
Installing small packages with few dependencies is possible in Google Colab.
```python
!pip install package_name
```

However, it can take quite some time to install packages in Google Colab and needs to be repeated every time you restart the runtime. Additionally, the `traffic` package returns an error if installed with the command above.

Alternatively, you can create a new environment in Google Colab by following the instructions in `setup_tso_env.ipynb`. This will create a virtual environment on your Google Drive and install the necessary packages.

Once you set up the environment, you can include the code from `use_env.ipynb` in your notebooks to activate the environment. This way, you can use the environment in all your notebooks without having to install the packages every time. The environment can be shared and used by the students.