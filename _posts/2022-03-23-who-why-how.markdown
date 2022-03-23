---
layout: post
title: "Who? Why? How?"
date: 2022-03-23
categories: jekyll docker github github-pages
---

## Who?

As you might've read on the homepage and/or on the [about](/about) page; my name is Arthur and I am in the final year of studying Software Engineering at the Amsterdam University of Applied Sciences. To find out more about me I suggest you read the about page, but in short; I am currently focussing on the JavaScript and Go languages.

## Why?

I have already learned a lot during college, but as we all know, the IT industry is a fast paced one and we developers continously need to update our skillset with the latest cutting-edge languages, frameworks and toolsets to stay relevant. This website serves as a kind of showcase of which technologies I have come familiar with so far and what my experience was like with these technologies.

## How?

I am currently following a [course](https://www.udemy.com/course/docker-mastery/) on Docker and Kubernetes by Bret Fisher. Althought I initially tried setting up Github Pages through Github itself, I actually ended up setting it up using Docker by using the Docker Images provided by Bret Fisher. The two images can be found [here](https://hub.docker.com/r/bretfisher/jekyll) and [here](https://hub.docker.com/r/bretfisher/jekyll-serve). Why did I do it like this? Well, multiple reasons:
- Setting up Github Pages without a local environment wasn't a good idea (for me, at least) since I had to push everything to Github before being able to see the changes.
- I didn't feel like installing Jekyll, Ruby, Gems, etc locally just to run this simple website. 
- It was just a few days before setting up this website that I followed the lecture where Bret talks about these Jekyll Images (they are actually part of a lecture about Docker compose) and I figured it's a nice way to put something I have learned during the course out in practice. Now everytime I want to edit this website locally, I have to interact with Docker, which is a nice way to keep the knowledge fresh in my memory.