# The Web Dev Index

This is a personal project of mine. I plan on building up my knowledge on the fundamentals
of web development, and I thought that making some notes plus related projects would be an
engaging way of doing so.

## Areas

### Internet infrastructure

The communication between server and client in web development: internet protocols, the DNS,
proxies, etc.

- [ ] Sockets
- [ ] TCP/IP
- [ ] TLS/SSL, certificates
- [ ] HTTP(S)
- [ ] DNS
- [ ] URL
- [ ] Web browsers
- [ ] Reverse proxies


### General web app functionality

Tasks that most web applications must implement one way or another. Managing
static files, media, parsing files from requests, etc. Things that aren't excessively
tied to implementation details.

- [ ] Data parsing
- [ ] File parsing
- [ ] Static files
- [ ] User authentication
- [ ] HTML templating
- [ ] Email and SMTP
- [ ] Media storage
- [ ] Caching
- [ ] Interntionalization and localization
- [ ] Task queues


### Data persistence

All web apps need to persist some data. This usually involves some kind of database.
The idea here is to understand some of the basics of databases, how to interact with
one and how do ORMs work.

- [ ] Fundamentals of databases
- [ ] Relational databases
- [ ] Object Relational Mappers (ORMs)


### Web security

Common security issues and defenses against them. List originally taken from
[MDN web docs: HTTP Security](https://developer.mozilla.org/en-US/docs/Web/HTTP). Another
interesting resource from Mozilla is their [web security guidelines](https://infosec.mozilla.org/guidelines/web_security).

- [ ] Content Security Policy (CSP)
- [ ] HTTP Strict Transport Security (HSTS)
- [ ] Cookie security
- [ ] X-Content-Type-Options
- [ ] X-Frame-Options
- [ ] X-XSS-Protection
- [ ] Cross Site Request Forgery (CSRF)


## Website

One half of the project is going to be about creating beautiful reference notes. The main
objective is to have a quick way of remembering how any of the topics that I research work.
This is in contrast to indepth notes, which I will also be taking, but will be more of a
secondary thing.

I plan on making the website with [Hugo](https://gohugo.io/), which is a technology
that I'm curious about, but I might change this decision later.

The website is located on the `site/` directory in this same repository.


### Glossary

Since the main goal of this is creating a knowledgebase for quick references, a glossary
is a great idea. The idea would be that important concepts could be searched in
a quick yet understandable definition be provided.
