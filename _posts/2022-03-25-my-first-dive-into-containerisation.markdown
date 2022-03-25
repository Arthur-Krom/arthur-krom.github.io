---
layout: post
title: "My first steps with Docker"
date: 2022-03-25
categories: docker container image containerisation
---

Hi! Welcome to the first blog post where I talk about what I've recently learned. As you might've read elsewhere on this website, I am currently learning about Docker by following a [course on Udemy](https://www.udemy.com/course/docker-mastery/) and by applying the matter on my own projects.

I did hear about Docker before I decided to learn it. It was usually some small talk with other developers who told me how amazing Docker was. Initially I didn't feel the need to pick this skill up, but since I started looking at developer vacancies I have realised how essential Docker is and that I should start learning it now.

## What is Docker?

Docker is an application that allows you to efficiently configure/manage/deploy 'mini' virtual machines (VM). One of the benefits of Docker is that there is no more need to install and configure particular software (versions) such as: Apache, PHP, Nginx, MySQL, etc on the host OS which can be cumbersome. Docker images describe everything that is needed in these mini VMs.

## Image

An image is essentially a blueprint of what a container should consist of. Similair to classes and instances in programming. To make this 'class' Docker uses a file called a Dockerfile. This file consist of layers.  Usually (always?) the base layer of the image is a a Linux OS such as Alpine or Debian. The next layers describe which commands (such as installing packages) need to be executed, which ports need to be exposed, etc.


## Container

A container is an instance of an existing image.
