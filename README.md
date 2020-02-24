# run postgres and hasura container

```bash
docker-compose up -d
```

Now you can see Hasura's GraphQL explorer as well as Postgres database interface at http://localhost:8080/

# svelte app

Install the dependencies...

```bash
cd svelte-app
npm install
```

...then start [Rollup](https://rollupjs.org):

```bash
npm run dev
```

Navigate to [localhost:5000](http://localhost:5000). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.