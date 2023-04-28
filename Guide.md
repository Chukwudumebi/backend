Steps in setting up the backend

On Windows
Create a backend folder
Create a virtual moment with: python -m venv name-of-environment
Activate the FastAPI environment with: name-of-environment-\Scripts\activate.bat
If necessary upgrade pip with: pip install --upgrade pip
Install fast api with : pip install fastapi
Install uvicorn[standard] with: pip install uvicorn[standard]
Start the app with: uvicorn main: app --reload



On Mac OS
Create a backend folder
Create a virtual moment with: python3 -m venv name-of-environment
Activate the FastAPI environment with: source name-of-environment-\Scripts\activate.bat
If necessary upgrade pip with: pip install --upgrade pip
Install fast api with : pip install fastapi
Install uvicorn with: pip install uvicorn
Install websockets: pip install websockets or pip install wsproto
Start the app with: uvicorn main: app --reload