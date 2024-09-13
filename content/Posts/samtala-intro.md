---
author: "zuri-zel"
title: "samtala: exploring decentralized communication"
date: "2024-09-13"
description: "a project to explore p2p decentralized and distributed systems"
tags: ["distributed systems", "p2p", "samtala"]
---

in the landscape of digital communication, there's always room for exploration and innovation.
i've always been curious and always want to learn new things just for the sake of learning, but most of the time
those stay just as ideas, readings, conversations. a lot of just in case information waiting to be used.
today i'm happy to share the beggining of a project that im really excited for that will allow me to put a lot of the
just in case information i've accumulated over the years into something that is interesting and motivating for me.
welcome to samtala, my part-time exploration into the world of decentralized distributed systems.

> disclaimer, this is an early exploration and most concepts come from memory or light superficial research. the document may have subtle(and blatant) errors. please if you find any go to the suggest changes link and suggest changes or open an issue/discussion in the github repo.

## the spark: a quest for alternative communication platforms

it was a few weeks back that i saw a post in x where Andrew Kelley(zig creator) was leaving the zig discord server after the app showed him some unwanted and unrelated ads.
he decided to move to irc, while principled it shows that there are not really many options for modern, decentralized, user owned, communication tools.

as a tinkerer im always eager to learn something new, and this was the oportunity to not only learn but apply. could i create a modern, decentralized alternative? and more importantly, could this be the perfect excuse to dive deep both into zig and distributed systems?
those were the questions that marked the beggining of samtala.

## what is samtala?

samtala(means discourse in swedish) is my exploration project into descentralized comms.

the initial vision for samtala is to create a p2p communication platfor that prioritizes user privacy and control. this is an evolving project: the tech stack, architecture and even the core concept may change over time as i delve deeper into development and research of it. also given the nature of side/part-time projects progress may be slow and updates sparse.

## goals: learning, explore, and maybe a chat app

while i'm presenting ambitious ideas for what samtala could become, i'm approaching the project with a learner mindset. my primary goals are:

1. deed dive into zig: i wanna use this project as a practical way to truly learn and understand the zig programming language.
2. explore distributed systems: gain hands-on experience with the underlying problem space of distributed systems, concepts and challenges.
3. experiment with decentralization: investigate how decentralized architectures can be used and applied to day to day communications.
4. learn about modern encryption: understand and implement rudimentary end to end encryption, solving the auth problem in a distributed way and tackle other security related issues.
5. improve my ui development skills: challenge myself to create a client for this project that is a gui and that is somewhat appealing.
6. document the journey: share this proccess document the advances and pitfalls i may find.

if along the way, samtala manages to evolve into a functional decentralized communication app that would be a fantastic outcome. but the main goal remains at learning and exploring, and that is the true heart of this project.


## the multiple fascets of developing samtala

one of the most exciting things this project offers me is the broad scope it has, as it manages to merge several interesting areas that pick my curiosity.
as a solo dev i'll be pushing myself to learn and apply concepts from lots of areas of cs. here a list:

### distributed systems

- conflict-free-replica-data-types for managing distributed state
- consensus algos like raft or viewstamped replications for the most important actions on the cluster
- gossip protocol to diseminate information
- distributed hash tables for peer discovery

### networking and protocols

- design custom udp based messaging protocol
- nat traversal techniques(turn/stun/ice and explore what wireguard/tailscale is doing)
- webrtc to add video and audio on top of this p2p network

### encription and security

- e2e encryption mechanism
- decentralized identity systems
- zero knowledge proofs

### systems programming with zig

- low level memory management
- concurrency patterns with no colored functions
- cross-platform develpment

### database systems

- log-structured merge trees
- time-based data retention
- efficient indexing and data retrieval for chat history

### user interface design

- develop a cross platform gui client.
- create a nice ux for a complex backed that abstracts it into somethin entizing for final users

## the path fordward: build, learn, iterate

the current focus as of now is to build a basic prototype that can demonstrate the core concepts:

- simple p2p messaging
- rudimentary chat rooms: create a simple system so people can create discover and join chat rooms
- basic encryption: implement an initial node to node encryption system
- minimal viable ui: basic ui to send and receive messages (any suggestion on what multiplatform lib to use here is welcome if possible native to zig or go)
- peer discovery: once in a chat room the system should discover which other nodes belong to it
- local data storage: implement local storage for message history

## an open invitation to accompany me

while samtala is my personal project, i think that having peers overseeing and getting interest into it is a nice addition.
i'll be documentin my journey, sharing the issues, challenges, and breakthroughs along the way. if any of the previous topics caught your eye i invite you to follow along.


here is how you can be part of if:
- follow the blog: all updates about it will appear here
- check out the repo: currently completely empty but hopefully soon will start to take some form
- share your insighs, opinions and knowledge: if you have experience on any of the previous areas i would love to hear your thoughs and suggestions.

## conclusion: embrace the unknown

as i start the journey with samtala, i look forward to the learnings ahead.
will this grow into something more than just a side project? to early to say, probably not, but i hope it can.

thanks for taking the time to read this post and for your interest in samtala.
stay tuned for more updates as this journey is just beggining.
