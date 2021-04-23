# Základné informácie o projekte:

# Návod ako spustiť projekt:

- - vytvorite priečinok pre projekt
- vytvorite súbor main.py a vložiť nasledovný obsah
- spustite príkazový riadok a prejsť do vytvoreného priečinku cez príkaz cd
- prejdite do jednotky (drive) G: cd /D G:
- prejdite o priečinok vyššie: cd ..
- prejdite do priečinka foo: cd foo
- spustite nasledovné príkazy

     py -3 -m venv venv
     venv\Scripts\activate
     pip install Flask
     python -m pip install --upgrade Pillow

     set FLASK_APP=main.py
     flask run![127 0 0 1_5000_](https://user-images.githubusercontent.com/80895765/115829486-59069380-a40f-11eb-828a-c3f391863e48.png)
