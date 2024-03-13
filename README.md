**Step 1:** Generate [Spotify Client ID & Secret Key](https://developer.spotify.com/dashboard/login)

After creating the credentials to use Spotify API, provide the Client ID & Secret inside `web-app/config.ini` under `[DEV]` section.

**Step 2:** Install dependencies

To run this repo, simply create a pip environment and install requirements:
```
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```

## Usage 
In order to run the web app locally, provide the following command:
```
python3 app.py
```

This will start a Flask web application in debug mode that runs on `port 5000` by default. Navigate to the following address on your browser to try it out:

```
http://localhost:5000/
```
