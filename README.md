# samxiao.com

There's nothing terribly exciting here, source code for [my personal site] made with [Hugo]!

[my personal site]: https://samxiao.com
[Hugo]: https://gohugo.io/

## Getting started

Install Hugo:

```ps
go install github.com/gohugoio/hugo@latest
```

Once installed, you can run the project via

```shell
npm run dev
```

## Adding a new page

Pages can be added via the Hugo New command

```shell
hugo new posts/my-new-blog-post.md
```

## Serving via home server

Run

```shell
npm run build
```

to build the website. A full website is built and output to `./public` folder. Copy the entire contents of the `./public` folder to the root folder in your web server.

## Updating the Theme

Run

```shell
hugo mod get -u
```

## To lint check

```shell
npm run lint
```

To fix

```shell
npm run lint:fix
```
