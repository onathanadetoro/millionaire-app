# simoncode-app

# Who Wants To Be A Millionaire?

A Streamlit version of the Who Wants To Be A Millionaire quiz game.

## How to run

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Start the app:

   ```bash
   streamlit run millionaire_app.py
   ```

3. Streamlit will open it in your browser (usually `http://localhost:8501`).

## Running via localtunnel (e.g. from Colab)

If you're running this somewhere without direct browser access (like Colab)
and want a public link, use `requirements_localtunnel.txt` alongside a tunnel:

```bash
pip install -r requirements.txt
pip install -r requirements_localtunnel.txt

streamlit run millionaire_app.py &
npx localtunnel --port 8501
```

localtunnel will print a public URL you can open in your browser.
