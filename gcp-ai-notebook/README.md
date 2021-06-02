# Jupyter Container for GCP AI Notebook

It's based on jupyter base docker images, customized to run on GCP AI notebook platform.

It exposes notebook server on port 8080 to comply GCP AI notebook custom container [requirement](https://cloud.google.com/notebooks/docs/custom-container).

It uses jupyter lab by default and password and token authentication are disabled as AI Notebook platform handles authentication in GCP side.