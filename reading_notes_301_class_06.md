[Home](https://pgmorales76.github.io/reading_notes_301/)

# Class 06 Reading Notes

## Why This Topic Matters

### Interacting with a team is what developers do every day. Learning what makes a great team (and what makes an individual a great team member) is necessary to performing any project, large or small

### Understanding how the basic, underlying, web technologies (`HTTP`) work, enables the developer to understand the technologies built on top (APIs) of those earlier technologies, and make development easier

## *To what extent did psychological safety impact your previous work experience?*

### Most of my, recent, professional experience has been in a construction site setting. I can’t think of an environment where psychological safety is the least of their concerns

### Now, to play devil’s advocate, for a moment, I think the reason for that is because physical safety is of paramount importance. Physical injury is more costly on a construction site, than if someone’s feelings get hurt. That’s the way the business is, for better or worse

### To the extent where working in a team is the environment in which you operate, there may be some give-and-take as to the details of the work being done

## *How does this article inform your approach to working with others moving forward?*

### When possible, I'll employ the three key factors that contribute to psychologically safe teams

> Members speaking in the same proportion, a phenomenon researchers refer to as ‘‘equality in distribution of conversational turn-taking’’; high ‘‘average social sensitivity’’ — a fancy way of saying they were skilled at intuiting how others felt based on their tone of voice, their expressions and other nonverbal cues; and making sure teams had clear goals and creating a culture of dependability.

[What Google Learned From Its Quest to Build the Perfect Team](https://www.google.com/amp/mobile.nytimes.com/2016/02/28/magazine/what-google-learned-from-its-quest-to-build-the-perfect-team.amp.html)

## *Who is Roy Fielding?*

>He helped write the first web servers, that sent documents across the internet… and then he did a ton of research explaining why the web works the way it does. His name is on the specification for the protocol that is used to get pages from servers to your browser. [A Conversation about REST with my brother](https://gist.github.com/brookr/5977550)

## *Why don’t the techniques that we use in this class work well when we need to be able to talk to all of the machines in the world?*

> . . . [machines] weren't designed to be used like that. When Fielding and his colleagues started building the web, being able to talk to any machine anywhere in the world was a primary concern. But most of the techniques developers later used to get computers to talk to each other didn't have those requirements. You just needed to talk to a small group of machines . . . We need to be able to talk to all machines about all the stuff that's on all the other machines. So we need some way of having one machine tell another machine about a resource that might be on yet another machine. [A Conversation about REST with my brother](https://gist.github.com/brookr/5977550)

## *What is the HTTP protocol that Fielding and his friends created?*

> The protocol I mentioned, that [Fielding] helped write, HTTP, it's capable of all sorts of neat stuff that people ignore for some reason . . . That first part tells the browser what protocol to use. That stuff you type in there is one of the most important breakthroughs in the history of computing . . . [HTTP] is capable of describing the location of something anywhere in the world from anywhere in the world. It's the foundation of the web. You can think of it like GPS coordinates for knowledge and information.
>
> The HyperText Transfer Protocol (HTTP) is the underlying network protocol that enables transfer of hypermedia documents on the Web, typically between a browser and a server so that humans can read them. The current version of the HTTP specification is called HTTP/2.
>
> As part of a URI, the "http" within "<http://example.com/>" is called a "scheme". Resources using the "http" schema are typically transported over unencrypted connections using the HTTP protocol. The "https" scheme (as in "<https://developer.mozilla.org>") indicates that a resource is transported using the HTTP protocol, but over a secure TLS channel. [A Conversation about REST with my brother](https://gist.github.com/brookr/5977550)

### Here's MDN's definition

> HTTP is textual (all communication is done in plain text) and stateless (no communication is aware of previous communications). This property makes it ideal for humans to read documents (websites) on the world wide web. However, HTTP can also be used as a basis for REST web services from server to server or AJAX requests within websites to make them more dynamic. [HTTP from MDN](https://developer.mozilla.org/en-US/docs/Glossary/HTTP)

## *What does a `GET` do?*

> The **HTTP `GET` method** requests a representation of the specified resource. Requests using `GET` should only be used to request data (they shouldn't include data). [`GET` on MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET).

## *What does a `POST` do?*

> The **HTTP `POST` method** sends data to the server. The type of the body of the request is indicated by the `Content-Type` header.
>
> The difference between `PUT` and `POST` is that `PUT` is idempotent: calling it once or several times successively has the same effect (that is no side effect), where successive identical POST may have additional effects, like passing an order several times. [`POST` on MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/POST)

## *What does `PUT` do?*

> The **HTTP `PUT` request method** creates a new resource or replaces a representation of the target resource with the request payload.
>
> The difference between `PUT` and `POST` is that `PUT` is idempotent: calling it once or several times successively has the same effect (that is no side effect), whereas successive identical POST requests may have additional effects, akin to placing an order several times. [`PUT` on MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/PUT).

## *What does `PATCH` do?*

> The **HTTP `PATCH` request method** applies partial modifications to a resource.
>
> `PATCH` is somewhat analogous to the "update" concept found in CRUD (in general, HTTP is different than CRUD, and the two should not be confused).
>
> A `PATCH` request is considered a set of instructions on how to modify a resource. Contrast this with `PUT`; which is a complete representation of a resource. [`PATCH` on MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/PATCH).

[How I explained REST to my brother](https://gist.github.com/brookr/5977550)

## Things I Want to Know More About

### It seems a bit cliché to have one team of “all-stars” and a team of “regular Joe’s”, with the latter having more success. I mean, it seems like a story out of a lame movie. Why did Google choose the teams the way they did? Why not make the teams more similar, than dissimilar?

### I find it difficult to believe that having a team of competent people is worse than having a team who “gets along”

### Who are the people who do work on something like `HTTP`? Are they software developers, or do only computer scientists/engineers work on something like `HTTP`?

### How do I explain REST to my brother, when I don't have a brother?
