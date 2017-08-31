# Blog
##A custom Django plugin to handle blog content

Blog is a simple Django app/plugin to handle news/articles content. 

## Suport
- Django Framework
- Django CMS

Quick start
-----------
## Use it as a Django third party application
1. Add "gallery" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'blog',
    ]

2. Include the blog URLconf in your project urls.py like this::

    url(r'^blog/', include('blog.urls')),

3. Run `python manage.py migrate blog` to create the blog models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to create a post (you'll need the Admin app enabled).

5. Visit http://127.0.0.1:8000/blog/ to vie the list of galleries you just created.

## Use it as a Django CMS plugin
TODO: Complete instructions

pip install --upgrade git+http://git@github.com/GoWebyCMS/blog.git

## Todos
#### Support docker - docker-compose up -build --no-cache
