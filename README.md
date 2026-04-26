for existing project use uv
===================================
> uv inti .
> uv venv
> .venv\Scripts\activate
> uv add -r requirements.txt
source .venv/bin/activate

Download spacy model:
👉 This downloads the small English model.
        python -m spacy download en_core_web_sm
    Verify installation:
        python -m spacy validate