# Streamlit Docker image

## How to use

No need to clone the GitHub repo. Just create a new folder with your app (named `streamlit_app.py`) and a `Dockerfile` with:

```Dockerfile
FROM samdobson/streamlit
WORKDIR /usr/src/app
COPY . .
```

Then you can build your image with `docker build -t acct:rep .`
