# GrooveLife

This is the backend for the GrooveLife Music Streaming platform. You can find the frontend at [GrooveFront](https://github.com/shalearkane/GrooveFront)
## How to run the backend
1. Create a new Python environment `.env`
2. Install requirements by `pip install -r requirements.txt`
3. Setup PostgreSQL and create a database named `GrooveLife`
4. Run migrations first using `python manage.py migrate`. If this runs correctly, that means the database is working.
5. Run `python manage.py runserver`

## How to run the frontend
1. Open the bash terminal
2. Install the packages `yarn install`
3. Run the frontend `yarn run`
