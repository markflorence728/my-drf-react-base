# my-drf-react-base
Django REST framework / React Base

# Help for structuring Django/Django Rest Framework/React project.

## Development

* Install Python dependencies: `pipenv install`
* Install Javascript dependencies: `npm i`
* Make the bundle: `npm run dev`
* Migrate: `pipenv run python ./project/manage.py migrate`
* Populate the database: `pipenv run python ./project/manage.py loaddata leads`
* Run locally: `pipenv run python ./project/manage.py runserver`
* Head over http://127.0.0.1:8000/

## Test

* Unit: `cd project && pipenv run python manage.py test`
* E2E: `npm run e2e`
* Coverage: `cd project && pipenv run coverage run manage.py test`

## Production

* Make the bundle: `npm run build`
* ... TODO

## TODO

* Authentication
* React routing
* Production
