# webmaster-qualifier

## Need to Install
- **Git** (for cloning the repository and managing pull requests)
- **Python**

## 1. Clone the Repo

Press `Ctrl+Shift+P` and type `Git: Clone`.
 Paste in the GitHub repository URL:  
   `https://github.com/emilydma08/webmaster-qualifier.git`

## 2. Install Flask and Dependencies

Type into the terminal:
- python -m venv venv
- source venv/bin/activate (Or if on windows, do: venv\Scripts\activate)
- pip install -r requirements.txt
- python app.py

## 3. To run flask in the future

1. **Activate the virtual environment**:
    Before running the app, ensure the virtual environment is activated:

   - **On Windows**:
    venv\Scripts\activate
     ```

   - **On Mac/Linux**:
    source venv/bin/activate

2. **flask run**
    - The website will be available at http://127.0.0.1:5000/ in the browser
    - If you make changes, you have to save, stop the server by doing CTRL + C, then do flask run again