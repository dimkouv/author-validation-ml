# author-validation-ml
A machine learning model that identifies whether or not the claimed author of some content is the original.

# use-case

Assuming that an account is compromised and an unauthorized user is writing content from it, we should be able
to identify him because of his different writing style.

# dev-setup

If you want to work on this notebook first install the dependencies

```bash
# install them directly
pip3 install -r requirements.pip --user

# or use a virtual environment
virtualenv -p python3 venv
source venv/bin/activate
pip3 install -r requirements.pip
```

Now download datasets from kaggle https://www.kaggle.com/nickreinerink/reddit-rcryptocurrency and
extract them under `~/Datasets/reddit-rcryptocurrency` (or wherever you want and set the location inside the notebook).

