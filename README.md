# awesome-django-articles

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Django](https://img.shields.io/badge/Django-green.svg)](https://www.djangoproject.com/)

--

## Table of Contents

 - [About Django](#about-django)
 - [API Development](#api-development)
 - [Architecture](#architecture)
 - [Authentication & Permissions](#authentication--permissions)
 - [Background Tasks](#background-tasks)
 - [Caching](#caching)
 - [Contributing](#contributing)
 - [Debugging](#debugging)
 - [Dependency Management](#dependency-management)
 - [Deployment](#deployment)
 - [Django Admin](#django-admin)
 - [Django ORM / Database](#django-orm--database)
 - [Encryption](#encryption)
 - [File Uploads](#file-uploads)
 - [Frontend Integration](#frontend-integration)
 - [HTMX](#htmx)
 - [Job Hunting](#job-hunting)
 - [Learning Django](#learning-django)
 - [Logging](#logging)
 - [Models](#models)
 - [Multitenancy](#multitenancy)
 - [Performance / Scaling](#performance--scaling)
 - [Profiling](#profiling)
 - [Request / Response](#request--response)
 - [Security](#security)
 - [Serverless](#serverless)
 - [Settings](#settings)
 - [Signals](#signals)
 - [Single-File Django Projects](#single-file-django-projects)
 - [Testing](#testing)
 - [Time Zones](#time-zones)
 - [Type Hints](#type-hints)
 - [Views](#views)
 - [Websockets](#websockets)

--

### About Django

 - [Django Build To Last](https://www.better-simple.com/django/2023/03/30/built-to-last/)
 - [Shedding light on Django versioning](https://fly.io/django-beats/shedding-light-on-django-versioning/)
 - [New goodies in Django 5.0](https://fly.io/django-beats/new-goodies-in-django-50/)

### API Development

 - [Faster API development with django-dataclasses](https://medium.com/roivant-technology/faster-api-development-with-django-dataclasses-5d33c366f23c) by Alec Clowes
 - [Model validation in Django REST Framework](https://www.kye.id.au/blog/posts/django-rest-framework-model-validation) by Kye Russell

### Architecture

 - [Against service layers in Django](https://www.b-list.org/weblog/2020/mar/16/no-service/) by James Bennett
 - [Clean Architecture in Django](https://medium.com/21buttons-tech/clean-architecture-in-django-d326a4ab86a9) by Jordi Fierro
 - [Django for Startup Founders: A better software architecture for SaaS startups and consumer apps](https://alexkrupp.typepad.com/sensemaking/2021/06/django-for-startup-founders-a-better-software-architecture-for-saas-startups-and-consumer-apps.html) by Alex Krupp
 - [More on service layers in Django](https://www.b-list.org/weblog/2020/mar/23/still-no-service/) by James Bennett
 - [Structuring large/complex Django projects, and using a services layer in Django projects](https://forum.djangoproject.com/t/structuring-large-complex-django-projects-and-using-a-services-layer-in-django-projects/1487/1) by Adam Johnson
 - [The Single Folder Django Project Layout](https://noumenal.es/notes/django/single-folder-layout/) by Carlton Gibson
 - [Thoughts on Django application architecture approaches](https://bradleykirton.com/2024/01/14/thoughts-on-django-application-architecture-approaches/) by Bradley Kirton

### Authentication & Permissions

 - [Django Roles, Groups, and Permissions Introduction](https://medium.com/djangotube/django-roles-groups-and-permissions-introduction-a54d1070544) by Hemanth S P
 - [Fine Tuning Django User Permissions](https://dandavies99.github.io/posts/2021/11/django-permissions/) by Daniel W Davies
 - [How to Serve Protected Content With Django (Without Bogging Down Your Application Server)](https://wellfire.co/learn/nginx-django-x-accel-redirects/)
 - [How to restrict access with Django Permissions](https://coderbook.com/@marcus/how-to-restrict-access-with-django-permissions/) by Marcus Lind
 - [Permissions in Django](https://testdriven.io/blog/django-permissions/) by Oluwole Majiyagbe

### Background Tasks

 - [Looking at Django task runners and queues](https://www.loopwerk.io/articles/2025/django-task-queues/) by Kevin Renskers
 - [A Deep Dive into Celery Task Resilience, Beyond Basic Retries](https://blog.gitguardian.com/celery-tasks-retries-errors/) by Mathias Millet
 - [ Using Async Functions in Celery with Django Connection Pooling](https://mrdonbrown.blogspot.com/2025/10/using-async-functions-in-celery-with.html) by Don Brown
 - [Django 6.0 Tasks: a framework without a worker](https://www.loopwerk.io/articles/2026/django-tasks-review/) by Kevin Renskers

### Django Admin

 - [Customizing the Django Admin](https://testdriven.io/blog/customize-django-admin/) by Nik Tomazic
 - [How to turn Django Admin into a lightweight dashboard](https://hakibenita.medium.com/how-to-turn-django-admin-into-a-lightweight-dashboard-a0e0bbf609ad) by Haki Benita
 - [10 tips for making the Django Admin more secure](https://opensource.com/article/18/1/10-tips-making-django-admin-more-secure) by Jeff Triplett & Lacey Williams Henschel
 - [Why is the Django Admin “Ugly”?](https://www.coderedcorp.com/blog/why-is-the-django-admin-ugly/) by Vince Salvino

### Django ORM / Database

 - [5 ways to get all Django objects with a related object](https://johnnymetz.com/posts/five-ways-to-get-django-objects-with-a-related-object/) by Johnny Metz
 - [A Django PAGNI: efficient bulk properties](https://lukeplant.me.uk/blog/posts/django-pagni-efficient-bulk-properties/) by Luke Plant
 - [Avoiding Duplicate Objects in Django Querysets](https://johnnymetz.com/posts/avoiding-duplicate-objects-in-django-querysets/) by Johnny Metz
 - [Conditional aggregation in Django 2.0](https://www.peterbe.com/plog/conditional-aggregation-in-django-2.0) by Peter Bengtsson
 - [Database concurrency in Django the right way](https://www.vinta.com.br/blog/database-concurrency-in-django-the-right-way) by Vinta Software
 - [Database generated columns⁽²⁾: Django & PostgreSQL](https://www.paulox.net/2023/11/24/database-generated-columns-part-2-django-and-postgresql/) by Paolo Melchiorre
 - [Database generated columns⁽³⁾: GeoDjango & PostGIS](https://www.paulox.net/2023/12/11/database-generated-columns-part-3-geodjango-and-postgis/) by Paolo Melchiorre
 - [Django migrations and your database](https://www.better-simple.com/django/2023/06/03/django-migrations-and-your-database/) by Tim Schilling
 - [Django + Postgres: The Hunt for Long Running Queries](https://paul-gilmartin89.medium.com/django-postgres-hunting-for-long-running-queries-8b141af984ab) by Paul Gilmartin
 - [Django ORM Standalone⁽¹⁾: Querying an existing database](https://www.paulox.net/2026/02/20/django-orm-standalone-database-inspectdb-query/) by Paolo Melchiorre
 - [Django Time-Based Lookups: A Performance Trap](https://johnnymetz.com/posts/django-time-based-lookups-performance/) by Johnny Metz
 - [Don’t Let Old Migrations Haunt Your Codebase](https://lincolnloop.com/blog/dont-let-old-migrations-haunt-your-codebase/) by Martin Mahner
 - [Integrating Django with PostgreSQL Materialized Views](https://medium.com/@abdu11a/integrating-django-with-postgresql-materialized-view-2c7c30d44a59) by Abdulla Hashim
 - [Optimize Django Query Performance by combining Select Related and Prefetch Related](https://johnnymetz.com/posts/combine-select-related-prefetch-related/) by Johnny Metz
 - [Storing and retrieving tree structures in relational databases using Python (Django)](https://medium.com/@spybugg/storing-and-retrieving-tree-structures-in-relational-databases-using-python-django-7480f40c24b) by Deepak Singh
 - [The Fast Way to Test Django transaction.on_commit() Callbacks](https://adamj.eu/tech/2020/05/20/the-fast-way-to-test-django-transaction-on-commit-callbacks/) by Adam Johnson
 - [Transaction Types in Django Tests](https://jeancochrane.com/blog/django-test-transactions) by Jean Cochrane
 - [Squashing Django Migrations the Easy Way](https://jacklinke.com/squashing-django-migrations-the-easy-way) by Jack Linke
 - [Database optimization isn’t always obvious](https://kenwhitesell.github.io/2025/01/01/Database-optimization-is-not-alway-obvious.html) by Ken Whitesell
 - [Django’s select_for_update with Examples and Tests](https://medium.com/@alexandre.laplante/djangos-select-for-update-with-examples-and-tests-caff09414766) by Alexandre Laplante

### Caching

 - [Django Caching 101: Understanding the Basics and Beyond](https://dev.to/pragativerma18/django-caching-101-understanding-the-basics-and-beyond-49p) by Pragati Verma

### Contributing

 - [Looking to get involved? Start here!](https://forum.djangoproject.com/t/looking-to-get-involved-start-here/18014) by Carlton Gibson
 - [Getting Started Contributing to Django](https://www.better-simple.com/django/2024/12/25/getting-started-contributing-django/) by Tim Schilling
 - [A Complete Guide to Contribute to Django for the First Time](https://zachliugis.github.io/django/2016/02/11/a-complete-guide-to-contribute-to-django-for-the-first-time) by Zach Liu
 - [How to find a ticket on Django's trac](https://smithdc.uk/blog/2023/how_to_find_a_ticket_on_django_trac/) by David Smith
 - [DSF Working Groups](https://github.com/django/dsf-working-groups/blob/main/README.md) by Django Software Foundation

### Debugging

 - [How to auto reload & debug Django and Django Celery workers running in Docker](https://blog.derlin.ch/auto-reload-plus-debug-django-and-django-celery-workers) by Lucy Linder
 - [Debugging a Containerized Django App in VS Code](https://testdriven.io/blog/django-debugging-vs-code/) by J-O Eriksson

### Dependency Management

 - [Django Dependency Management with pip-compile and pip-tools](https://learndjango.com/tutorials/django-dependency-management-pip-compile-and-pip-t) by Will Vincent

### Deployment

 - [An Efficient Multi-Stage Build for Python Django in Docker](https://blog.ploetzli.ch/2020/efficient-multi-stage-build-django-docker/) by Henryk Plötz
 - [Deploying Django Application on AWS with Terraform. Setting up Celery and SQS](https://dev.to/daiquiri_team/deploying-django-application-on-aws-with-terraform-setting-up-celery-and-sqs-38ik) by Yevhen Bondar
 - [Deploying a Django App to Render](https://testdriven.io/blog/django-render/) by Nik Tomazic
 - [Deploying completely serverless Django with Zappa and Aurora Serverless](https://www.agiliq.com/blog/2019/01/complete-serverless-django/) by Anmol Akhilesh
 - [Smooth Database Changes in Blue-Green Deployments](https://fly.io/django-beats/smooth-database-changes-in-blue-green-deployments/) by Mariusz Felisiak
 - [Stable Django deployments without downtime](https://kuttler.eu/en/post/django-deployments-without-downtime/) by Nicolas Kuttler

### Encryption

 - [Exploring approaches to field-level encryption in Python for Django applications](https://www.piiano.com/blog/field-level-encryption-in-python-for-django-applications) by Imri Goldberg

### File Uploads

 - [3 steps to upload files properly with Django (and HTMX) 📁](https://www.photondesigner.com/articles/upload-files-properly-django-htmx) by Tom Dekan
 - [Serving Private Files with Django and S3](https://lincolnloop.com/blog/serving-private-files-with-django-and-s3/) by Richard Terry

### Frontend Integration

 - [Django Tailwind: How to configure Django and TailwindCSS from scratch in a new project](https://learndjango.com/tutorials/django-tailwind) by Learn Django
 - [Setting Up Server Side Rendering with React, Redux, and Django](https://medium.com/meural-product-development/setting-up-server-side-rendering-with-react-redux-and-django-4d6f4d2fd705) by Alexander Richey
 - [Tutorial: Django REST with React (and a sprinkle of testing)](https://www.valentinog.com/blog/drf/) by Valentino Gagliardi

### HTMX

 - [Add instant database search with Django and HTMX 🕵️](https://www.photondesigner.com/articles/database-search-django-htmx) by Tom Dekan
 - [Ajax-Enabled Checkbox and Select with Django and HTMX](https://jacklinke.com/ajax-enabled-checkbox-and-select-with-django-and-htmx) by Jack Linke
 - [Django Formsets Tutorial - Build dynamic forms with Htmx](https://justdjango.com/blog/dynamic-forms-in-django-htmx) by Matthew Freire
 - [Django and HTMX](https://dev.to/kummerer94/django-and-htmx-i5c) by Alexander Kammerer
 - [Django, HTMX and Alpine.JS: A Match Made In Heaven](https://dev.to/nicholas_moen/what-i-learned-while-using-django-with-htmx-and-alpine-js-24jg) by Nicholas Moen
 - [Django, HTMX and Alpine.js: Modern websites, JavaScript optional](https://www.saaspegasus.com/guides/modern-javascript-for-django-developers/htmx-alpine/) by Cory Zue
 - [How to create a Django form (using HTMX) in 90 seconds 🐎](https://www.photondesigner.com/articles/submit-async-django-form-with-htmx) by Tom Dekan
 - [Rapid Prototyping with Django, htmx, and Tailwind CSS](https://testdriven.io/blog/django-htmx-tailwind/) by Amal Shaji
 - [How to show a modal in Django + HTMX](https://joshkaramuth.com/blog/django-htmx-modal/) by Josh Karamuth
 - [Show Django flash messages as toasts with Htmx](https://joshkaramuth.com/blog/django-messages-toast-htmx/) by Josh Karamuth

### Job Hunting

 - [Questions to ask a Django company](https://www.better-simple.com/career/2022/12/31/questions-to-ask-a-django-company/) by Tim Schilling

### Learning Django

 - [Beginners should use Django, not Flask](https://www.bitecode.dev/p/beginners-should-use-django-not-flask) by Bite Code!
 - [Build an NFT rarity tool with Django](https://justdjango.com/blog/nft-rarity-tool) by Matthew Freire
 - [Some notes on starting to use Django](https://jvns.ca/blog/2026/01/27/some-notes-on-starting-to-use-django/) by Julia Evans

### Logging

 - [Structlog with Django is Awesome!](https://loop0.sh/posts/structlog-with-django-is-awesome/) by Bruno Ribeiro

### Models

 - [Django models, encapsulation and data integrity](https://www.dabapps.com/insights/django-models-and-encapsulation/) by Tom Christie

### Multitenancy

 - [Multitenancy: juggling customer data in Django](https://www.vinta.com.br/blog/multitenancy-juggling-customer-data-django) by Filipe Ximenes

### Performance / Scaling

 - [19X faster response time](https://lincolnloop.com/insights/optimizing-response-time-19x-faster/) by Yann Malet
 - [Enhance Your Data Queries with Materialized Views in PostgreSQL and Django](https://blog.muehlemann-popp.ch/enhance-your-data-queries-with-materialized-views-in-postgresql-and-django-9e6804b4f332) by Silvan Mühlemann
 - [How to Optimize Django ORM Queries](https://gearheart.io/blog/how-optimize-django-orm-queries/) by Alexey Demianenko
 - [How to avoid a count query in Django if you can](https://www.peterbe.com/plog/how-to-avoid-a-count-query-in-django-if-you-can) by Peter Bengtsson
 - [How to optimize PostgreSQL queries from Django using pgMustard](https://adamj.eu/tech/2022/06/21/optimize-postgresql-queries-from-django-using-pgmustard/) by Adam Johnson
 - [Solving Performance Problems in the Django ORM](https://hansonkd.medium.com/performance-problems-in-the-django-orm-1f62b3d04785) by Kyle Hanson
 - [Supercharge Your Django App: 7 Sneaky Tricks to Crush Slow Database Queries](https://johnnymetz.com/posts/slow-django-database-queries/) by Johnny Metz
 - [μDjango (micro Django) 🧬](https://www.paulox.net/2023/10/26/udjango_micro_django/) by Paolo Melchiorre
- [Using Materialized Views to Implement Efficient Reports in Django](https://www.fusionbox.com/blog/detail/using-materialized-views-to-implement-efficient-reports-in-django/643/) by Gavin Wahl
 - [Lessons from scale: Django](https://medium.com/sanket-saurav/lessons-from-scale-django-124f7b16ae0c) by Sanket Saurav
 - [Tips for Building High-Quality Django Apps at Scale](https://medium.com/@DoorDash/tips-for-building-high-quality-django-apps-at-scale-a5a25917b2b5) by DoorDash Engineering
 - [The Practical Guide to Scaling Django](https://slimsaas.com/blog/django-scaling-performance/) by Andrew

### Profiling

 - [Django: How to profile and improve startup time](https://adamj.eu/tech/2023/03/02/django-profile-and-improve-import-time/) by Adam Johnson
 - [Django: profile memory usage with Memray](https://adamj.eu/tech/2026/01/29/django-profile-memray/) by Adam Johnson

### Request / Response

 - [Django Streaming HTTP Responses](https://blog.pecar.me/django-streaming-responses) by Anže Pečar
 - [How Does Django's StreamingHttpResponse Work, Exactly?](https://andrewbrookins.com/django/how-does-djangos-streaminghttpresponse-work-exactly/) by Andrew Brookins

### Security

 - [Django Security Best Practices: A Comprehensive Guide for Software Engineers](https://corgea.com/Learn/django-security-best-practices-a-comprehensive-guid-for-software-engineers) by Ahmad Sadeddin

### Serverless

 - [Django Views as Serverless Functions on Fly Machines](https://fly.io/django-beats/django-views-as-serverless-functions-on-fly-machines/) by Kátia Nakamura

### Settings

 - [Checking Django Settings](https://dev.to/adamghill/checking-django-settings-12g4) by Adam Hill
 - [Django Settings In the Cloud](https://engineering.instawork.com/django-settings-in-the-cloud-aa3fc547a2b4) by Oleg Pesok
 - [Making Sense Of Settings](https://www.mattlayman.com/understand-django/settings/) by Matt Layman

### Signals

 - [Common Pitfalls Using Django Signals](https://engineering.instawork.com/common-pitfalls-using-django-signals-7b0654d843b) by Oleg Pesok

### Single-File Django Projects

 - [Django from first principles](https://www.mostlypython.com/django-from-first-principles/) by Eric Matthes
 - [μDjango (micro Django) 🧬](https://www.paulox.net/2023/10/26/udjango_micro_django/) by Paolo Melchiorre

### Testing

 - [Blazing fast tests in Django](https://dizballanze.com/django-blazing-fast-tests/) by Yuri Shikanov
 - [Django Password Hashing: Speed Up Your Tests by 70%](https://dschaefer.substack.com/p/django-password-hashing-speed-up) by Dave Schaefer
 - [Django Test Fixture: setUp, setUpClass and setUpTestData](https://medium.com/an-engineer-a-reader-a-guy/django-test-fixture-setup-setupclass-and-setuptestdata-72b6d944cdef) by Nhat Cuong / Nathan
 - [Django: Parametrized tests for all model admin classes](https://adamj.eu/tech/2023/03/17/django-parameterized-tests-model-admin-classes/) by Adam Johnson
 - [Django's test runner is underrated](https://www.loopwerk.io/articles/2026/django-tests-underrated/) by Kevin Renskers
 - [Optimizing your Django tests](https://olzhasar.com/posts/optimizing-your-django-tests/) by Olzhas Arystanov
 - [Simplified Django Tests With Pytest and Pytest FactoryBoy](https://schegel.net/posts/simplied-django-tests-with-pytest-and-pytest-factoryboy/) by Rocio Aramberri
 - [Test factory functions in Django](https://lukeplant.me.uk/blog/posts/test-factory-functions-in-django/) by Luke Plant
 - [Testing: exceptions and caches](https://nedbatchelder.com/blog/202601/testing_exceptions_and_caches) by Ned Batchelder  <!-- codespell:ignore ned -->
 - [Using tox to Test a Django App Across Multiple Django Versions](https://www.djangotricks.com/blog/2026/02/using-tox-to-test-a-django-app-across-multiple-django-versions/)
 - [Avoiding Mocks: Testing LLM Applications with LangChain in Django](https://lincolnloop.com/insights/avoiding-mocks-testing-llm-applications-with-langchain-in-django/) by Marc Gibbons

### Time Zones

 - [Time Zones in Pytz & Django](http://tommikaikkonen.github.io/timezones/) by Tommi Kaikkonen

### Type Hints

 - [Typing Your Django Project in 2026](https://blog.pecar.me/typing-your-django-project-in-2026/) by Anže Pečar

### Views

 - [Django Views — The Right Way](https://spookylukey.github.io/django-views-the-right-way/) by Luke Plant
 - [The View Pattern](https://spookylukey.github.io/django-views-the-right-way/the-pattern.html) by Luke Plant
 - [Thin Views](https://spookylukey.github.io/django-views-the-right-way/thin-views.html) by Luke Plant
 - [An Introduction to Django Views](https://blog.jetbrains.com/pycharm/2025/01/django-views/) by Evgenia Verbina

### Websockets

 - [A minimal Websockets setup with Django in production](https://www.untangled.dev/2020/08/02/django-websockets-minimal-setup/) by J.V. Zammit
 - [Finally, Real-Time Django Is Here: Get Started with Django Channels](https://blog.heroku.com/in_deep_with_django_channels_the_future_of_real_time_apps_in_django) by Jacob Kaplan-Moss

 ----

### Sources

This awesome list is built thanks to:

 - [Django News Newsletter](https://django-news.com/?utm_source=awesome-django-articles)
 - [Django Forum](https://forum.djangoproject.com/new)
 - [Python Weekly Newsletter](https://www.pythonweekly.com/?utm_source=awesome-django-articles)
 - [My Github Feed!](https://github.com)
 - [Lobste.rs](https://lobste.rs/?utm_source=awesome-django-articles)
 - Several RSS feeds I'm subscribed to.
 - Friends / team mates at work.
 - [The internet (?)](https://duckduckgo.com/?va=g&t=ha&q=django&ia=web)
