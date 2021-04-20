# Basic microfrontends architecture

Using Webpack Module Federation to create a simple microfrontends architecture with 3 modules:

- Container (Vanilla JS)
- Products (Vanilla JS)
- Cart (Vanilla JS)

To run it, run each of this command in a different shell:
```
npm --prefix ./container install && npm --prefix ./container start
npm --prefix ./products install && npm --prefix ./products start
npm --prefix ./cart install && npm --prefix ./cart start
```

The whole application will run on:
```
http://localhost:8080
```

The 2 microfrontends sub-projects will also run in isolation on:
```
http://localhost:8081 (Products)
http://localhost:8082 (Cart)
```


