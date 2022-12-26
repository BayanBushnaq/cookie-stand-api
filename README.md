# api-quick-start

Template Project for starting up CRUD API with Django Rest Framework

## Customization Steps

- DO NOT migrate yet
- add additional dependencies as needed
  - Re-export requirements.txt as needed
- change `cookie_stands` folder to the app name of your choice
- Search through entire code base for `Thing`,`cookie_stands` and `cookie_stands` to modify code to use your resource
  - `project/settings.py`
  - `project/urls.py`
  - App's files
    - `views.py`
    - `urls.py`
    - `admin.py`
    - `serializers.py`
    - `permissions.py`
- Update ThingModel with fields you need
  - Make sure to update other modules that would be affected by Model customizations. E.g. serializers, tests, etc.
- Rename `project/.env.sample` to `.env` and update as needed
- Run makemigrations and migrate commands
- Run `collectstatic` if needed.
- Optional: Update `api_tester.py`


- ## Deploy link on heruku:
![deploy link](https://cookie-stands-project.herokuapp.com/)

- ## admin path:
![admin path](https://cookie-stands-project.herokuapp.com/admin/login/?next=/admin/)

- ## List path:
![list path](https://cookie-stands-project.herokuapp.com/api/v1/cookie_stands/)

- | Role | UserName | Paasword |
  |------|----------|----------|
  |superuser | admin    | admin12345 |
  |staff | Ihab     | 1234ihab |
  |staff | Bayan    | bushnaq1234 |
  |user  | mohammad | mh123456 |
