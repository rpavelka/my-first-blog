DjangoGirls tutoriál: řešení Nicol Daňkové
==========================================

Mnoho díků patří Nicol Daňkové za zpřístupnění její verze hotového základního tutoriálu.
Toto je "fork" [její práce](https://github.com/ndankova/my-first-blog).

Já jsem dále upravil její stránku, tak aby fungovala i na novější verzi Djanga a přidal tento text.

Jak si zprovoznit stránku u sebe na <http://localhost:8000>? Pokud máte jiný počítač, než který jste používaly na workshopu,
nejprve [nainstalujte vše potřebné dle tutoriálu](https://tutorial.djangogirls.org/en/installation/). Dále aktivujte své
virtuální prostředí a pak v příkazové řádce zadejte následující:

```
git clone git@github.com:rpavelka/my-first-blog.git
cd my-first-blog
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver 0.0.0.0:8000
```

Dále už je navštivte v prohlížeči <0.0.0.0:8000>.

Zdroje:

<https://tutorial.djangogirls.org>
<https://djangogirls.gitbooks.io/django-girls-tutorial-extensions/>
