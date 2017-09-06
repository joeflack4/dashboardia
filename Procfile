# Help: https://stackoverflow.com/questions/16416172/how-can-i-modify-procfile-to-run-gunicorn-process-in-a-non-standard-folder-on-he
web: gunicorn --pythonpath server dashboardia:app

# None of these seem to work. Issue seems to be git submodule.
# web: gunicorn --pythonpath server dashboardia
# web: gunicorn --pythonpath ./server dashboardia:app
# web: gunicorn --pythonpath ./server dashboardia
# web: gunicorn --pythonpath ./server dashboardia.wsgi:app
# web: gunicorn --pythonpath ./server dashboardia.wsgi
# web: gunicorn --pythonpath server dashboardia.wsgi:app
# web: gunicorn --pythonpath server dashboardia.wsgi
