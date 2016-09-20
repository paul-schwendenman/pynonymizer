Relies on Python packages `flask` and `flask-restful`. These can be install with pip.

To run: `python anonymizer-restful-app.py` or `python3 anonymizer-restful-app.py` will start the server.

Then curl:

`curl -i -H "Content-Type: application/json" -X POST http://localhost:5000/api/v1.0/anonymize -d '{"url": "https://github.com/github/testrepo.git", "description": "hello"}'`

NOTE: you will need an additional credentials file to run this. Please contact the creator directly if interested.
