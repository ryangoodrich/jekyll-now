---
layout: post
title: GraphQL for Google Functions
---

One of the limitations of Google Functions is the inability to create
_folders_ of functions. For example, url.google.com/foo/bar will not exist,
only url.google.com/foo. This creates a unique problem when developing a 
serverless application. Traditionally I would build a bunch of routes
following the REST application development pattern. Not possible anymore.

Thankfully a few months ago on of my friends mentioned GraphQL to me. I
didn't look into it much at the time, but it popped into my head as a
possible way to solve this _one endpoint_ problem. Turns out... its really
cool.

#### Phase 1: What is GraphQL??

GraphQL is an api query language developed by Facebook to enable the client
to be selective about the information sent and received. This allows the
same backend endpoint to server a mobile phone, desktop application, and
anything in between without the server having any knowledge. Also, it all
works from a single endpoint.

##### Schema

##### Resolver 

#### Phase 2: Getting "Hello World" Working

#### Phase 3: GraphiQL - Visualize

#### Phase 4: CORS
