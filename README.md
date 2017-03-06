# Get up and running

Before you start, make sure you've completed the steps in the README on `master` first.

1. Log into your EC2 instance
2. Run `git checkout .` to throw away any previous changes
3. Run `git checkout external-db`
3. Update the `.env` file with your RDS connection details
4. Run `docker-compose up -d`
