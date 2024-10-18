# Audio Speech To Sign Language Converter

A Web Application which takes in live audio speech recording as input, converts it into text and displays the relevant Indian Sign Language animations.

> - Front-end using HTML,CSS,JavaScript.
> - Speech recognition using JavaScript Web speech API.
> - Text Preprocessing using Natural Language Toolkit(NLTK).
> - A 3D animation of a character created
>   using Blender 3D tool.

Project Demo Video: https://youtu.be/YiHhD0QGrno

## Prerequisites

> - Python >= 3.7
> - Browser supports Web Speech API
> - Download all required packages for python script A2SL/views.py

## Installation Guide:

These instructions will get you download the project and running on your local machine for development and testing purposes.

### Instructions

1. Open the Downloads folder and then open the terminal.
2. From the terminal, run the python file using the command "python manage.py runserver ####" (#### optional port number).
3. From the terminal, it shows localhost address (looks like this "server at http://127.0.0.1:8000/") run on browser.
4. Sign up and start exploring.
5. Click on mic button to record speech.
6. Speech is going to processed and respective animated outputs are shown accordingly and it also support entered text manually.
### Setup by vinay
It looks like you've uploaded several files related to a Python project, possibly a Django or web-based application based on the presence of `manage.py` and `setup.py`. Here are the general steps to successfully run this kind of project:

1. **Set up the environment:**
   - Ensure you have Python installed. You can check by running `python --version` in your terminal.
   - Set up a virtual environment by running:
     ```bash
     python -m venv venv
     ```
     Activate the environment:
     - On Windows: `venv\Scripts\activate`
     - On macOS/Linux: `source venv/bin/activate`

2. **Install dependencies:**
   - If there is a `requirements.txt` or if dependencies are defined in `setup.py`, install them by running:
     ```bash
     pip install -r requirements.txt
     ```

3. **Run database migrations (for Django projects):**
   - If this is a Django project, you'll need to apply migrations:
     ```bash
     python manage.py migrate
     ```

4. **Start the development server:**
   - For Django, start the development server with:
     ```bash
     python manage.py runserver
     ```

5. **Check the `README.md`:**
   - Look for specific instructions in the `README.md` file that you uploaded, as it may contain additional steps or setup instructions specific to this project.

Would you like me to review the contents of `README.md` or `setup.py` to check for any project-specific instructions?
