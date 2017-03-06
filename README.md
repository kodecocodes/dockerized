# Get up and running

Before you start, make sure your EC2 instance has both `git` and `docker` installed.

1. Log into your EC2 instance
2. Run `git clone https://github.com/raywenderlich/dockerized.git`
3. Update the `.env` file
4. Run `docker-compose start -d db` to start PostgreSQL and let it complete it's first-launch initialization
5. Run `docker-compose up -d` to spin up the webapp

From then on you can simply use `docker compose up` and `docker compose down` to manage the state of the containers.
