---
description: Jumping on the hype train.
---

# Building w/ Containers: Docker

Releases are a beautiful, beautiful thing. But no release is perfect. There are a couple hiccups to look out for. A major, universally-applicable hiccup when building Erlang/OTP releases is the fact that the release is generally dependent on both the operating system and hardware its build on.

What this means for us is that if we build a release straight-up on a Macbook Pro, or Surface Book, and deploy it to a linux-based server in the cloud we're going to be in trouble. Likewise if we build on linux and push it to the worlds only Mac server rack, we'll be SOL.

Enter the container. By building our release inside of a container, we can build the release against the same OS that our remote machines in the cloud have.

There's a second "gotcha". Unfortunately most applications require code beyond than pure Elixir/Erlang. If you want a web interface, you probably need JavaScript. Maybe a sprinkle of css. A picture or font or two.

Erlang/OTP releases are concerned with Erlang and OTP. But here again containers can save the day. We'll script our non-elixir build processes into the container image build so that we don't have to worry about all those little things every time we want to ship a sweet update to production.

In the Building Containers with Docker guide, we'll cover all of the above and more.

