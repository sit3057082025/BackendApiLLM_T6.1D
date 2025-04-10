Instructions:
1. First clone the repo or download to your local folder.
2. Run terminal in the project folder.
   - Make sure python is installed.
   - Create Virtual environment using this in terminal: python -m venv venv
   - venv folder will be created.
   - now activate virtual environment
     - For MAC: source venv/bin/activate
     - For Windows PS: .\venv\Scripts\Activate.ps1
3. Now install the libraries
   - pip install Flask
     (source: https://flask.palletsprojects.com/en/stable/installation/)
   - pip install requests
     (source: https://pypi.org/project/requests/)
   - pip install transformers
     (source: https://pypi.org/project/transformers/)
   - pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu126
     (source: https://pytorch.org/get-started/locally/)
4. Settings with HuggingFace
   - Signup for Huggingface Account here: https://huggingface.co/
   - Create access token from here: https://huggingface.co/settings/tokens
   - Get Model "google/gemma-3-1b-it" from https://huggingface.co/google/gemma-3-1b-it.
   Acknowledge licence.
5. To run the code: python main.py (or other file names)

Outputs:
Check on browser: [127.0.0.1:5000](http://127.0.0.1:5000/getQuiz?topic=movies)
Should get something like this:
<img src="img_1.png" width="300" alt="Description">

