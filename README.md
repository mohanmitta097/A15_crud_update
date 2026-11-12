# Student CRUD — Update

Includes create, read and update operations. Click **Edit** beside a student, change the form values, then select **Save changes**.

## Run
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
uvicorn main:app --reload
```
Open http://127.0.0.1:8000. API docs: http://127.0.0.1:8000/docs

## API
- `GET /students`
- `POST /students`
- `PUT /students/{student_id}`

Data is in memory and resets when the server restarts.
