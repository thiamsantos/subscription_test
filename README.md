# SubscriptionTest

```sh
$ asdf install
$ mix deps.get
# start redis
$ docker-compose up -d redis
# start the server
$ iex -S mix phx.server
```

```
iex> Absinthe.Subscription.publish(SubscriptionTestWeb.Endpoint, %{name: "Mary"}, user_created: "users")
```
