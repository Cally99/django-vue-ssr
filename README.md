## Django Nuxt SSR

[live-app](https://django-nuxt-ssr.herokuapp.com/)* | 
[backend repo](https://github.com/SHxKM/django-vue-ssr) (this one) | 
[frontend repo](https://github.com/SHxKM/django-nuxt-ssr-front)

\* hosted on a free Heroku dyno that sleeps after 30 minutes of inactivity - 
could load slower than it's supposed to (or even crash) when it first "wakes up". 
Subsequent refreshes are much faster.

### TL;DR

A simple (now realtime) to-do app built with: Django REST framework, Django Channels, Nuxt.js, and Tailwind.

### About 

Django To Do With Vue v2 is an expirement in utilizing technologies and practices in web development that I 
haven't used before. This project is over-engineered on the one hand, 
and not really production-ready on the other (you can help with that). 
My goal wasn't to build a todo app per se, but to expirement with all the "cutting-edge" stuff out there.

It can serve as a general template, but is not to be relied upon to utilize best practices in produciton.

### Stack

- backend:
    - Django
    - Django REST framework
    - Django Channels
- frontend:
    - Vue
    - Nuxt.js
    - Tailwind CSS

### Heroku

Deployment should be straightforward, given the `.env` files are correctly filled in both repositories.
 The backend Heroku app uses the `python` buildpack, and the frontend one depends on the `nodejs` one.


(After many failed attempts to deploy the codebase as a single repository, I've
 finally came to the conclusion that it's not only wrong, but also quite impossible.) 