# depolywebonrendercom
Record the deployment of the web onrender.com<br>
Consultation of reference websites is very helpful.<br>
And success with the deployment of the website finally.<br>
Ref:<br>
1.Onrender Guide: https://render.com/docs/deploy-django.<br>
Step by step could complete almost all necessary items that deploy the web.<br><br>
2.Whitenoise: https://whitenoise.readthedocs.io/en/stable/django.html<br>
https://hatemegalaxy.blogspot.com/2017/08/django-whitenoise-django-using.html<br>
Collect the static files using the Whitenoise is easy to complete.<br><br>
3.Django: https://docs.djangoproject.com/en/4.2/ref/settings/#static-files<br>
Search the setting.py about static-files related items, such as "STORAGES".<br><br>
4.Django static files and Templates: https://learndjango.com/tutorials/django-static-files-and-templates<br>
Final step -- python manage.py collectstatic, pip install whitenoise, and other settings at setting.py.<br><br>
5.Django favicon: https://learndjango.com/tutorials/django-favicon-tutorial<br>
if Build cache doesn’t pick up changes in build scripts,use Clear build cache and deplo.<br><br>
