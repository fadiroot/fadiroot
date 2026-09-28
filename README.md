<h1 align="center">Fadi Romdhan</h1>
<p align="center"><b>Full-Stack &amp; AI Agent Engineer</b> · TypeScript / NestJS / Node.js · Python / FastAPI · React</p>
<p align="center">
  <a href="https://www.npmjs.com/package/nestjs-kafka-transport"><img alt="nestjs-kafka-transport on npm" src="https://img.shields.io/npm/v/nestjs-kafka-transport?label=nestjs-kafka-transport&color=cb3837"></a>
  <a href="https://github.com/fadiroot?tab=repositories"><img alt="repositories" src="https://img.shields.io/badge/repos-41-blue"></a>
  <img alt="location" src="https://img.shields.io/badge/Tunisia-UTC%2B1-green">
</p>

## About me

I build backend systems and AI services that have to work in production: REST and event-driven microservices in **NestJS/Node.js**, AI services in **Python/FastAPI** on **Azure AI Foundry**, and the React front ends that sit on top. I currently build internal and AI services for the **Saudi Ministry of Municipalities and Housing (MOMAH)**, where adoption by non-technical teams matters as much as the code.

I contribute to the open-source projects I depend on. My approach is simple: read the code around a feature I use, find the case one code path handles and its sibling forgot, write the test that fails on `main`, fix it, and send a small PR. Maintainers merge those fast.

## Open source

**Author of [`nestjs-kafka-transport`](https://github.com/fadiroot/nestjs-kafka-transport)** — a drop-in Kafka transport for `@nestjs/microservices` built on `@platformatic/kafka`, wire-compatible with the built-in kafkajs transport so services can migrate one at a time. Request-reply, retries with backoff, at-least-once commits, typed options; tested against Kafka 3.9/4.0 on Node 22/24.

**Merged contributions**

| Project | Change |
|---|---|
| [nestjs/nest](https://github.com/nestjs/nest/pull/17866) | Redis transport: reply on the request channel when wildcards are enabled |
| [nestjs/nest](https://github.com/nestjs/nest/pull/17867) | Fastify adapter: treat `application/json; charset=utf-8` as JSON |
| [nestjs/nest-cli](https://github.com/nestjs/nest-cli/pull/3595) | webpack: resolve the tsconfig path absolutely |
| [nestjs/nest-cli](https://github.com/nestjs/nest-cli/pull/3596) | SWC watch mode: fork the type checker with the application's plugins |
| [Automattic/mongoose](https://github.com/Automattic/mongoose/pull/16526) | `bulkWrite` `updateMany`: stop mutating the caller's update object |
| [punkpeye/fastmcp](https://github.com/punkpeye/fastmcp/pull/389) | Keep `canAccess` tools visible to sessions without auth after a runtime change |
| [punkpeye/fastmcp](https://github.com/punkpeye/fastmcp/pull/390) | `prompts/get`: answer `-32602` when a required argument is missing |
| [punkpeye/fastmcp](https://github.com/punkpeye/fastmcp/pull/391) | Re-pin the Stripe benchmark spec (CI) |
| [urfave/cli](https://github.com/urfave/cli/pull/2444) | Restore `Unwrap` on the error returned by `Exit` |

**Under review:** NestJS (media-type versioning), Docker CLI (`volume create` cluster options), Fiber (compress: repeated `Accept-Encoding` lines), MCP Go SDK (custom methods over SSE), NestJS Swagger, urfave/cli, Zulip (playgrounds validation, webhook event filtering), Medusa (`BigNumber`, `promiseAll`, refundable totals), PentAGI, InstaDeep Jumanji. Full list: [pull requests by me](https://github.com/pulls?q=is%3Apr+author%3Afadiroot+-user%3Afadiroot).

## Stack

`TypeScript` `Node.js` `NestJS` `Express` `Fastify` `React` · `Python` `FastAPI` · `PostgreSQL` `MongoDB` `Redis` `Kafka` `RabbitMQ` · `Docker` `GitHub Actions` `Azure AI Foundry` `AWS` · `MCP servers & AI agents` · some `Go`

## Contact

- Email: fadiromdhan3@gmail.com
- npm: [fadiromdhan](https://www.npmjs.com/~fadiromdhan)
- Open to remote full-time roles and contract work (Tunisia, UTC+1).

<p align="center">
  <img alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=fadiroot&show_icons=true&hide_border=true&count_private=true&theme=default" height="150">
  <img alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=fadiroot&layout=compact&hide_border=true" height="150">
</p>
