# Pretix Development Environment

Ticketing software that cares about your event — all the way.

### Requirements:

- Docker
- docker-copmpose

### Start it up

- `Change you settings in config/pretix.cfg

- Pretix docs: https://docs.pretix.eu

run:

```bash
docker-compose up -d
```

### Recommended:

- https://docs.pretix.eu/en/latest/admin/installation/docker_smallscale.html#next-steps
- https://docs.pretix.eu/en/latest/development/setup.html

### Acessing Pretix Dashboard

- Dashboard: `http://localhost/control/`
- User: `admin@localhost`
- Password: `admin`

1. Create an organizer
2. Create an event
3. Start presales
