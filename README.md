# Getting Started

This is a sandbox for a front end programming test.

```
git clone https://github.com/vicero/frontend-programming-test.git
cd frontend-programming-test
npm install
npm run dev
```

Note that on some machines you need to run `npm run dev -- --host 0.0.0.0` if you are unable to connect to the dev host.

# Programming Test

To complete this test, create a web app that can search GitHub repositories.

## Github API

The search API is documented [here](https://docs.github.com/en/rest/search?apiVersion=2022-11-28#search-repositories).

Authentication is not required to query this endpoint.  However, unauthenticated
requests are rate-limited to 60 per hour.  Please consider this when building your
web app.

You can also use `curl` to experiment with the endpoint:

```
curl -i https://api.github.com/search/repositories\?q\=vite
```

## Front End

Feel free to use any React component libraries you are comfortable with.

Implementing a strong UX is great, but may not be possible during the time we have.
Please share any thoughts you have on what you would do if you did have time.

What would this look like if you were adding it to a commercial tool?