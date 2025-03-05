![RedisNuts](./images/redisnuts-logo.png)

## RedisNuts

A simple in-memory database that imitates "Redis" and its serialization protocol to manipulate data. I built this project following this awesome [tutorial](https://www.build-redis-from-scratch.dev/en/introduction).

PS: GOTTEM

# This project features
- In-memory database
- RESP parser and serializer
- A command handler (with commands similar to Redis like SET and GET)
- AOF file for data persistence

# Running Locally
To run this project, first you need to have a Redis Client installed. [Here](https://redis.io/docs/latest/operate/oss_and_stack/install/install-stack/) you see how to install redis in your machine.

Next, you need to stop the current redis server (if you have one running).

After all that we can run the project:

- Run the server
```bash
go run main.go
```

- Run the client
```bash
redis-cli
```

![I use nvim btw](https://buttonwall.neocities.org/vim-vialle-love-anim.gif)
![Use linux NOW!](https://buttonwall.neocities.org/nclinux.gif)
