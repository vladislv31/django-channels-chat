# Django Channels Chat

Simple Chat Application using websockets.
Developed according to [Channels Tutorial](https://channels.readthedocs.io/en/stable/tutorial/index.html)

## Tech Stack

- Frontend: HTML/CSS/Bootstrap
- Backend: Django, Channels

## Quick Start

Firstly, you need to run Redis in Docker:

- `docker run -p 6379:6379 -d redis:5`

Then install requirements and run app:

- `poetry install`
- `poetry shell`
- `python manage.py runserver`

## Tests

Requiremets:

- Chrome Web Browser
- chromedriver (you shound install it according with your chrome web browser version and add it to PATH)

To run:

- `python manage.py test core.tests`

### Useful Links

- [Django](https://www.djangoproject.com/)
- [Channels](https://channels.readthedocs.io/en/stable/index.html)
- [chromedriver](https://chromedriver.chromium.org/)
