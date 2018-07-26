# PhoenixHelloworld

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Install Node.js dependencies with `cd assets && npm install`
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](http://www.phoenixframework.org/docs/deployment).

## Docker

To build:

    $ docker build . -t casmacc/phoenix_helloworld

To run: 

    $ docker run -p 4000:4000 casmacc/phoenix_helloworld

To run with `nginx_proxy`

    $ docker run -p 4000:4000 -e VIRTUAL_HOST=phoenix.yourdomain casmacc/phoenix_helloworld

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: http://phoenixframework.org/docs/overview
  * Docs: https://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix
