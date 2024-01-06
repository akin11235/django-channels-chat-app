# django-channels-chat-app

<p>This is based on a tutorial from testdriven.io.</p>
<p>To use the app:</p>

<p>1. Create and activate a virtual environment</p>
   <pre>$ python 3 -m venv env && source env/bin/activate</pre>

<p>2. Install Requirements</p>
   <pre>(env)$ pip install -r requirements.txt</pre>

<p>3. Apply migrations</p>
   <pre>(env)$ python manage.py migrate</pre>

<p>4. Start a Redis server for backing storage</p>
   <pre>(env)$ docker run -p 6379:6379 -d redis:5</pre>

<p>5. Run the server</p>
   <pre>(env)$ python manage.py runserver</pre>

<p>6. Create authenticated users to chat. To test create superuser</p>
   <pre>(env)$ python manage.py createsuperuser</pre>

<p>7. Log in to admin at http://localhost:8000/admin/</p>

<p>8. Navigate to http://localhost:8000/chat/</p>
