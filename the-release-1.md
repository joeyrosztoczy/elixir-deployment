---
description: 'So you want to deploy your application, huh? You''ve come to the right place.'
---

# The Release: Distillery

That's what I call ambition, hot shot. It's time to get out of our happy local sandbox, and move our application to... well... _somewhere_ else.

It wants to be free.

It doesn't matter where we're going exactly, but let's call it the cloud. We want to wrap our perfect application up nice and cleanly and have it work on other machine\(s\) that aren't our laptop. And it better work just as great as it does right now while we're staring at it and developing it.

To do that, we need to build an Erlang/OTP release.

Why do we need a release? There are quite a variety of reasons:

1. Releases are self-contained packages that run your entire Elixir application. The same release can be deployed to any like-kind machine, anywhere, and you won't need to worry about dependency fetching, installation, etc.
2. Releases are slimmed down to vital components. Your app will be even more performant packaged into a production release than it appears running on dev servers locally.
3. Releases contain vital Erlang/OTP tasks and configuration that will unlock their full power - including hot-swapping code to upgrade systems with intense uptime requirements.

Not a BEAM or Erlang expert? Me either. Even if I was, I wouldn't want to spend all day building releases from scratch. But don't worry, the awesome Elixir community has your back. Creating releases is drastically simplified in Elixir, thanks to Bitwalker's library [Distillery](https://github.com/bitwalker/distillery).

In the Releases with Distillery Guide, we'll walk through getting up and running with Distillery, configuring your application for release, advanced configuration options, and how to hot-swap code in a live deployment.

Section Objectives:

1. **NOT\_STARTED -** Getting started with Distillery.
2. **NOT\_STARTED -** Configuration best practices.
3. **NOT\_STARTED -** Building our release.
4. **NOT\_STARTED -** Advanced release options.

\*Information on hot-swapping code in releases can be found under the advanced instrumentation guide.

