# Super30 FastAPI GET API Task

## Project objective

This beginner project shows how to create static and dynamic GET APIs with FastAPI. It demonstrates route functions, path parameters, type hints, and JSON responses.

## Project files

- `main.py` contains the FastAPI application and endpoints.
- `requirements.txt` contains the required Python packages.
- `README.md` contains the project instructions.

## Installation

1. Open a terminal in the project folder.
2. Create a virtual environment:

   ```bash
   python -m venv venv
   ```

3. Activate it on Windows:

   ```powershell
   venv\Scripts\activate
   ```

4. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

## Run the server

```bash
uvicorn main:app --reload
```

Open <http://127.0.0.1:8000> in a browser.

Interactive Swagger documentation: <http://127.0.0.1:8000/docs>

ReDoc documentation: <http://127.0.0.1:8000/redoc>

## Available GET endpoints

| Endpoint | Purpose |
|---|---|
| `/` | Welcome message |
| `/student` | Student information |
| `/course` | Course information |
| `/skills` | Technical skills |
| `/add/{num1}/{num2}` | Add two numbers |
| `/multiply/{num1}/{num2}` | Multiply two numbers |
| `/square/{number}` | Find a number's square |
| `/check/{number}` | Check whether a number is even or odd |
| `/age/{age}` | Display an age-based message |
| `/table/{number}` | Generate a multiplication table |
| `/profile/{name}/{age}` | Display a dynamic profile |
| `/number/{number}` | Analyze a number |

## Example URLs

- <http://127.0.0.1:8000/add/10/20>
- <http://127.0.0.1:8000/multiply/5/8>
- <http://127.0.0.1:8000/square/9>
- <http://127.0.0.1:8000/check/17>
- <http://127.0.0.1:8000/age/25>
- <http://127.0.0.1:8000/table/7>
- <http://127.0.0.1:8000/profile/Sudhanshu/37>
- <http://127.0.0.1:8000/number/25>

## Author

Student name: Sudhanshu
