# DjangoCMS

This version was created in a Windows 8.1 machine and contains the elements to create a site with DjangoCMS, to install you need to clone the repository using:

```
git clone https://github.com/kinnevo/DjangoCMS.git
```

You have a virtual environment for Windows in the directory cms
to activate execute:

```
.\Scripts\activate
```

Then run:

```
install -r requirements -- to add all the elements required to run this instance python
```

You may need
```
manage.py migrate
```

To activate DgangoCMS:
```
python manage.py runserver
```

