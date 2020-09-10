# Microblog
Blog app based on Miguel Grinberg's Flask Tutorial
https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world


##### Languages
The app can be used in English and Spanish. Change your browser language settings or ...

Translations are in .po files and Python produces .mo files.
Update your translations with these 3 commands:
1. pybabel extract -F babel.cfg -k _l -o messages.pot .
2. pybabel update -i messages.pot -d app/translations
3. pybabel compile -d app/translations
