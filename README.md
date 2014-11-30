# Pyget

A lightweight nuget server written in Python, intended for deployment to Heroku.

## Usage

For local testing, start with `foreman run python app.py`.

Configure with environment variables, stored in `.env`, for example:

```
# required
NUGET_API_KEY=somethingsecret
S3_BUCKET=bucket
S3_KEY=bla
S3_SECRET=61a
DATABASE_URL=postgres://localhost/pyget

# optional
DEBUG=True
FLASK_PORT=80
```

## NuGet on OS X

Download and install the MDK from here: http://www.mono-project.com/download/

Type `nuget` into terminal.
