# HealBharat_Task3_Micro_Saas_Tools

# Micro SaaS Tools

This is a Micro SaaS Tools web application built with Python Flask backend and Jinja2 frontend templates. It includes user authentication, admin dashboard, user dashboard, and multiple tools like resume builder, invoice generator, certificate generator, and QR code generator.

## Features

- User signup, login, and profile management
- Admin dashboard to manage users and view stats
- User dashboard to access tools and upload/download files
- Tools: Resume builder, Invoice generator, Certificate generator, QR code generator
- File upload and download support
- Responsive and modern UI design
- Deployment ready for Render and Vercel

## Requirements

- Python 3.8+
- SQLite (default) or PostgreSQL
- Virtual environment recommended

## Setup and Run Locally

1. Clone the repository or copy the project files to your local machine.

2. Create and activate a virtual environment:

```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Set environment variables (optional):

- `FLASK_APP=app.py`
- `FLASK_ENV=development`
- `SECRET_KEY` (set your own secret key)
- `DATABASE_URL` (if using PostgreSQL or other DB)

5. Run the application:

```bash
flask run
```

6. Open your browser and navigate to `http://localhost:5000`

## Deployment

- Use the provided `render.yaml` for Render deployment.
- Use the provided `vercel.json` for Vercel deployment.

## Testing

- Basic unit tests are included in the `tests/` directory.
- Run tests with:

```bash
pytest
```

## Notes

- Uploaded/generated files are stored in `static/uploads`.
- Customize configuration in `config.py`.

## Troubleshooting

- If you encounter issues installing dependencies, ensure your pip, setuptools, and wheel packages are up to date:

```bash
pip install --upgrade pip setuptools wheel
```

- For image processing errors, ensure Pillow is installed correctly.

---

This README provides all necessary steps to run the project on any device with Python installed.
