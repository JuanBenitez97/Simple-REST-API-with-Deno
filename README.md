# Simple REST API with Deno

[Deno](https://deno.land/) is a simple, modern and secure runtime for JavaScript and TypeScript that uses V8 and is built in Rust, [Oak](https://github.com/oakserver/oak) is a middleware framework for Deno's net server, this is inspired by the popular Node.js middleware [Koa](https://github.com/koajs/koa).


With this API you can:
* Add new dogs
* List dogs
* Get details about a specific dog
* Remove a dog from the list
* Update a dog age

To run the server you just need to install deno and run the command: `deno run --allow-env --allow-net app.ts`

Endpoits:
* `GET /dogs`
* `GET /dogs/:name`
* `POST /dogs`
* `PUT /dogs/:name`
* `DELETE /dogs/:name`
