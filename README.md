# depoly web onrender.com
Record the deployment of the web onrender.com<br>
Consultation of reference websites is very helpful.<br>
And success with the deployment of the website finally.<br>
First deploy December 4, 2023 at 3:23 PM --> Deploy twentysixth December 12, 2023 at 12:33 PM<br><br>
Ref:<br>
1.Onrender Guide: https://render.com/docs/deploy-django.<br>
Step by step could complete almost all necessary items that deploy the web.<br><br>
2.Django: https://docs.djangoproject.com/en/4.2/ref/settings/#static-files<br>
Search the setting.py about static-files related items, such as "STORAGES".<br><br>
3.Django static files and Templates: https://learndjango.com/tutorials/django-static-files-and-templates<br>
Final step -- python manage.py collectstatic, pip install whitenoise, and other settings at setting.py.<br><br>
4.Django favicon: https://learndjango.com/tutorials/django-favicon-tutorial<br>
The website logo file path and setting.<br><br>
5.requirements.txt: https://zhuanlan.zhihu.com/p/69058584<br>
pip install -r requirement.txt, pip freeze > requirements.txt<br><br>
6.gunicorn: https://community.render.com/t/bash-gunicorn-command-not-found/1485/5 <br>
The gunicorn add in requiremwnrs.txt<br><br>
7.poetry: https://www.ixiqin.com/2023/06/26/deploying-django-4-2-on-render-com/<br>
pip install poetry<br><br>
8.Whitenoise: https://whitenoise.readthedocs.io/en/stable/django.html<br>
https://hatemegalaxy.blogspot.com/2017/08/django-whitenoise-django-using.html<br>
Collect the static files using the Whitenoise is easy to complete.<br><br>
9.some tiny adjusts: https://stackoverflow.com/questions/24857158/commanderror-you-must-set-settings-allowed-hosts-if-debug-is-false <br>
CommandError: You must set settings.ALLOWED_HOSTS if DEBUG is False. ALLOWED_HOSTS = ['localhost', '127.0.0.1', 'www.mysite.com']<br><br>
if Build cache doesn’t pick up changes in build scripts,use Clear build cache and deplo.<br><br>
!image[https://github.com/peaceian/depolywebonrendercom/blob/main/onrendersetting.png]
