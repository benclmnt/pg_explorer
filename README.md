# pg_explorer

A super simple SQL exploration interface accessible through web.

![screenshot](sql_explorer.webp)

To run `EXPORT DATABASE_URL=<your db url> go run main.go` and open `localhost:8080`. 
Your db url will look like `postgresql://admin:admin@localhost:5432/app?sslmode=disable`

Deploy inside your internal network with `tailscale serve 8080`. 
