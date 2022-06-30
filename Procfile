web: gunicorn app:app --workers 1 --worker-class uvicorn.workers.UvicornWorker --bind 0.0.0.0:8443 --timeout 600
web: bundle exec thin start -p http://0.0.0.0:8443
