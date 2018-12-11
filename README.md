# [Symfony Con - Lisbon 2018](https://lisbon2018.symfony.com/) talks

- All talks are in **english**.
- Comment and rate talks on [joind.in](https://joind.in/event/symfonycon-lisbon-2018/schedule/list)

## Keynote

[Slides](https://speakerdeck.com/fabpot/symfony-local-web-server-dot-dot-dot-reloaded)  
~~Video~~

By [Fabien Potencier](https://connect.symfony.com/profile/fabpot)  
![github](icon/github.png) [@fabpot](https://github.com/fabpot)  
![twitter](icon/twitter.png) [@fabpot](https://twitter.com/fabpot)

---

## Using the Workflow component for e-commerce

<dl>
  <dt>Description</dt>
  <dd>We got the task to make an order API, from open order, to delivered, with payments in between and after. So there are naturally a lot of states, and a lot of transitions where we needed to calculate the prices correctly and handle credit card transfers. Keeping track of all of this, and when we need to do what, ensuring that an order is always up to date, and that it has the data it needs, and that we send good error messages when a user can not do an action, was a challenge for us until we discovered the workflow component. This is a real happy use case story where I will show you how we did this, and how much more straightforward it was for us to build an otherwise complex system using the workflow component.</dd>
</dl>

[Slides](https://slideshare.net/TobiasNyholm/knowing-your-state-machines-symfonycon-lisbon)  
~~Video~~

By [Tobias Nyholm](https://connect.symfony.com/profile/tobias)  
![github](icon/github.png) [@Nyholm](https://github.com/Nyholm)  
![twitter](icon/twitter.png) [@TobiasNyholm](https://twitter.com/TobiasNyholm)

And [Michelle Sanver](https://connect.symfony.com/profile/michellesanver)  
![github](icon/github.png) [@michellesanver](https://github.com/michellesanver)  
![twitter](icon/twitter.png) [@michellesanver](https://twitter.com/michellesanver)

---

## Behat Best Practices with Symfony

<dl>
  <dt>Description</dt>
  <dd>Behat is widely used as part of a Behaviour Driven Development lifecycle, but it's also widely misused. In this talk Ciaran will explain the BDD process, and show the best practices for using Behat including: writing good scenarios, driving service development from scenarios, fast UI testing, and using Behat and the Symfony2Extension.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Ciaran McNulty](https://connect.symfony.com/profile/ciaranmcnulty)  
![github](icon/github.png) [@ciaranmcnulty](https://github.com/ciaranmcnulty)  
![twitter](icon/twitter.png) [@CiaranMcNulty](https://twitter.com/CiaranMcNulty)

---

## File storage for modern PHP applications.

<dl>
  <dt>Description</dt>
  <dd>Many PHP applications need to store files. There are many different reasons to store file, and not all filesystems are created equally. How can we identify our needs? Which filesystem is best for your use-case? How can we ensure our future needs are not blocked by the code we write today? In this talk we'll explore how filesystem abstraction and general coding guidelines can improve our application's and make them future proof!</dd>
</dl>

~~Slides~~  
~~Video~~

By [Frank de Jonge](https://connect.symfony.com/profile/frenkynet)  
![github](icon/github.png) [@frankdejonge](https://github.com/frankdejonge)  
![twitter](icon/twitter.png) [@frankdejonge](https://twitter.com/frankdejonge)

---

## Symfony Messenger: 6 months already and more to come

<dl>
  <dt>Description</dt>
  <dd>The Messenger component brings asynchronous processing to Symfony: using message bus(es) you are able to decouple your application and route some (or all) of these "messages" to transports such as the built-in AMQP transport. It’s been more than 6 months since we’ve merged the new Messenger component in Symfony. We will explore the different use cases it has been used for so far and how it will continue to involve in order to facilitate even more.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Samuel Roze](https://connect.symfony.com/profile/sroze)  
![github](icon/github.png) [@sroze](https://github.com/sroze)  
![twitter](icon/twitter.png) [@samuelroze](https://twitter.com/samuelroze)

---

## Going crazy with Varnish: Caching pages of logged in users

<dl>
  <dt>Description</dt>
  <dd>You know how HTTP caching works but need more? In this talk we look into ways to cache personalized content. We will look at Edge Side Includes (ESI) to tailor caching rules of fragments, and at the user context concept to differentiate caches not by individual user but by permission groups. A big help to leverage this concept is the FOSHttpCache in combination with either Varnish or the Symfony HttpCache reverse proxy.</dd>
</dl>

[Slides](http://davidbu.ch/slides/2018-12-06-varnish.html)  
~~Video~~

By [David Buchmann](https://connect.symfony.com/profile/dbu)  
![github](icon/github.png) [@dbu](https://github.com/dbu)  
![twitter](icon/twitter.png) [@dbu](https://twitter.com/dbu)

---

## Changing PHP

<dl>
  <dt>Description</dt>
  <dd>PHP releases a new minor version every year. Major versions happen when there are enough changes that justify to do so. Who is making those changes and how does that process work? What is the process to get an RFC to vote and the subsequent merge of the code? How can I make my first contribution? Is there anything I can do even if I don't know C? If you are intrigued by PHP internals, this talk is for you.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Pedro Magalhães](https://connect.symfony.com/profile/pmmaga)  
![github](icon/github.png) [@pmmaga](https://github.com/pmmaga)  
![twitter](icon/twitter.png) [@pmmaga](https://twitter.com/pmmaga)

---

## Using Symfony Forms with Rich Domain Models

<dl>
  <dt>Description</dt>
  <dd>Due to complex web projects we work on, there was a need for deeper integration between content management system and eCommerce solution. As eZ Platform is based on Symfony we searched for a Symfony based ecommerce solution and found Sylius as the best choice. We combined the two systems in one Symfony instance so we can integrate on much deeper level. Learn about our experience with merging and maintaining such a solution.</dd>
</dl>

[Slides](https://speakerdeck.com/el_stoffel/using-symfony-forms-with-rich-domain-models-cafc2b0d-2d86-4314-9d8d-d154a26944bf)
~~Video~~
[RichModelFormsBundle](https://github.com/sensiolabs-de/rich-model-forms-bundle)
[Demo App](https://github.com/sensiolabs-de/rich-model-forms-demo)

By [Christopher Hertel](https://connect.symfony.com/profile/chertel)  
![github](icon/github.png) [@chr-hertel](https://github.com/chr-hertel)  
![twitter](icon/twitter.png) [@el_stoffel](https://twitter.com/el_stoffel)

And [Christian Flothmann](https://connect.symfony.com/profile/xabbuh)  
![github](icon/github.png) [@xabbuh](https://github.com/xabbuh)  
![twitter](icon/twitter.png) [@xabbuh](https://twitter.com/xabbuh)

---

## One year diversity initiative

<dl>
  <dt>Description</dt>
  <dd>Last year in Cluj the diversity initiative was announced by Fabien. This talk aims to give an overview how those efforts were organized, what was done as part of the initiative and what progress was made. Both increasing how welcoming we are to people from all backgrounds as well as community reach out to help grow the Symfony community. Finally we will look at what could be the next steps this initiative.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Lukas Kahwe Smith](https://connect.symfony.com/profile/lsmith)  
![github](icon/github.png) [@lsmith77](https://github.com/lsmith77)  
![twitter](icon/twitter.png) [@lsmith](https://twitter.com/lsmith)

---

## How static PHP analyzer changed the way I look at code

<dl>
  <dt>Description</dt>
  <dd>Let me introduce you to the world of static PHP code analyzers. I'd like to show you which tools exists, how to use them and how they help you to improve your code quality.</dd>
</dl>

[Slides](https://speakerdeck.com/ichhabrecht/how-static-php-analyzer-changed-the-way-i-look-at-code)  
~~Video~~

By [Nicole Cordes](https://connect.symfony.com/profile/ichhabrecht)  
![github](icon/github.png) [@IchHabRecht](https://github.com/IchHabRecht)  
![twitter](icon/twitter.png) [@IchHabRecht](https://twitter.com/IchHabRecht)

---

## Building global web apps with multi-region hosting

<dl>
  <dt>Description</dt>
  <dd>This session will explore various setups and case studies from my attempts at hosting sites used by global audiences. There are many ways this can be achieved with different levels of success, budgets and global-ness. The talk will touch on Terraform, AWS, global DNS resolution and CDNs amongst other things.</dd>
</dl>

[Slides](http://slides.seld.be/?file=2018-12-06+Building+global+web+apps+with+multi-region+hosting.html)  
~~Video~~

By [Jordi Boggiano](https://connect.symfony.com/profile/seldaek)  
![github](icon/github.png) [@Seldaek](https://github.com/Seldaek)  
![twitter](icon/twitter.png) [@seldaek](https://twitter.com/seldaek)

---

## Building Apps for Immutable Servers

<dl>
  <dt>Description</dt>
  <dd>Immutable Servers are not new and they are not that simple to achieve. However, the advantages of having Immutable Servers versus Snowflake Servers are worth it. In this talk, I will explain the differences between Snowflake and Immutable Servers and also what considerations you should have while developing your App. I will also share which tools and strategies you can use to build Immutable Servers.</dd>
</dl>

[Slides](https://speakerdeck.com/dcsg/building-apps-for-immutable-servers)  
~~Video~~

By [Daniel Gomes](https://connect.symfony.com/profile/danielcsgomes)  
![github](icon/github.png) [@dcsg](https://github.com/dcsg)  
![twitter](icon/twitter.png) [@_dcsg](https://twitter.com/_dcsg)

---

## Bulletproof MongoDB

<dl>
  <dt>Description</dt>
  <dd>An all-too-common approach for database error handling is to log the exception, return a 500 reasponse, and move on to the next request. MongoDB and its PHP driver have an array of features that can greatly improve an application's resiliency in the face of unexpected errors. This talk will examine how the driver monitors connections to a cluster and look at how we can tune its behavior to meet an application's unique needs. We'll also demonstrate how PHP applications can take advantage of newer features such as retryable writes and multi-document transactions to guarantee ACID data integrity without having to fall back to PDO and an SQL database.</dd>
</dl>

[Slides](https://speakerdeck.com/jmikola/bulletproof-mongodb)  
~~Video~~

By [Jeremy Mikola](https://connect.symfony.com/profile/jmikola)  
![github](icon/github.png) [@jmikola](https://github.com/jmikola)  
![twitter](icon/twitter.png) [@jmikola](https://twitter.com/jmikola)

---

## Leverage the power of Symfony components within ApiPlatform

<dl>
  <dt>Description</dt>
  <dd>ApiPlatform is great for building API-first software. Even better, it's build on top of Symfony! Did you hear about Symfony's Workflow component? Or the brand new Messenger component? They offer powerful tools! For example, a pizza order can take multiple statuses, each one in transition with another (order, pay, wait, eat). This is a workflow. While waiting for the product, it needs to be cooked! Every time the order is paid, we have to send an instruction to the kitchen. Today, why don't we automatically push that message? Through a real-life use case, I will demonstrate how well these two fit on top of our Symfony-based API!</dd>
</dl>

[Slides](https://soyuka.github.io/leverage-the-power-of-symfony-components-within-apiplatform/)  
~~Video~~  
[Code](https://github.com/soyuka/leverage-the-power-of-symfony-components-within-apiplatform/tree/master/demo)

By [Antoine Bluchet](https://connect.symfony.com/profile/soyuka)  
![github](icon/github.png) [@soyuka](https://github.com/soyuka)  
![twitter](icon/twitter.png) [@s0yuka](https://twitter.com/s0yuka)

---

## The patterns behind Doctrine

<dl>
  <dt>Description</dt>
  <dd>How does Doctrine talk to your database? What are Data Mapper, Unit Of Work, and Identity Map? These are the questions I want to answer in this talk. We will look at how Doctrine ORM implements them and what they are there for. Finally we will look at how they compare to Active Record and what the benefits and drawbacks are to help you choose which one fits your needs best.</dd>
</dl>

[Slides](https://speakerdeck.com/dbrumann/patterns-behind-doctrine-b31c4791-50a4-4d0f-9a57-a8f93af5b356)  
~~Video~~

By [Denis Brumann](https://connect.symfony.com/profile/dbrumann)  
![github](icon/github.png) [@dbrumann](https://github.com/dbrumann)  
![twitter](icon/twitter.png) [@dbrumann](https://twitter.com/dbrumann)

---

## When testing makes no sense

<dl>
  <dt>Description</dt>
  <dd>If you look at the stage of any conference in the PHP world, people are preaching testing,testing,testing ... If you on the other hand look at the community, the percentage of people writing tests is really low. As a person who went from 'How can I ask for more time/money/resources for testing?' through 'ask for forgiveness instead of permission', to person who writes tests a lot, I still believe testing doesn't make sense. No, it doesnt make sense for all and everyone, often enough it makes no sense for me too. This talk will explore that fuzzy line when you have to shift your mind from one side to the other: in both directions.</dd>
</dl>

[Slides](https://slides.com/mirosvrtan/when-testing-makes-no-sense-symfonycon2018/)  
~~Video~~

By [Miro Svrtan](https://connect.symfony.com/profile/msvrtan)  
![github](icon/github.png) [@msvrtan](https://github.com/msvrtan)  
![twitter](icon/twitter.png) [@msvrtan](https://twitter.com/msvrtan)

---

## Microservices gone wrong

<dl>
  <dt>Description</dt>
  <dd>Microservices are the latest architectural trend to take the PHP community by storm. Is it a good pattern? How can you use it effectively? In this talk, we'll explore real world experience building out a large scale application based around microservices: what worked really well, what didn't work at all, and what we learned along the way. Spoiler alert: we got a lot wrong.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Anthony Ferrara](https://connect.symfony.com/profile/ircmaxell)  
![github](icon/github.png) [@ircmaxell](https://github.com/ircmaxell)  
![twitter](icon/twitter.png) [@ircmaxell](https://twitter.com/ircmaxell)

---

## Security: handling user access with Symfony the right way

<dl>
  <dt>Description</dt>
  <dd>We often overlook a central security requirement that any application needs to meet: controlling users' access to data and functionality. Usually, we handle user access through the combination of 3 security mechanisms: authentication, session management and access control. We will take a look at the Symfony's Security component powerful tools and see how to use them to handle user access the right way.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Diana Ungaro Arnos](https://connect.symfony.com/profile/dianaarnos)  
![github](icon/github.png) [@dianaarnos](https://github.com/dianaarnos)  
![twitter](icon/twitter.png) [@dianaarnos](https://twitter.com/dianaarnos)

---

## Webpack Encore: Tips, Tricks, Questions & Best Practices

<dl>
  <dt>Description</dt>
  <dd>With Webpack, your JavaScript & CSS code can have superpowers you've only dreamed up. And with Symfony's Webpack Encore, you can get all of this with almost zero setup time! In this talk, we'll quickly learn the basics of Webpack Encore, then, turn to the lessons we've learned over the past year: answer popular questions and explore common problems people run into when moving to Encore. We'll also dive into a host of lesser-known best practices that you can follow to make sure your frontend coding is as streamlined as possible. A modern frontend build system: all in the time of one talk!</dd>
</dl>

~~Slides~~  
~~Video~~

By [Ryan Weaver](https://connect.symfony.com/profile/weaverryan)  
![github](icon/github.png) [@weaverryan](https://github.com/weaverryan)  
![twitter](icon/twitter.png) [@weaverryan](https://twitter.com/weaverryan)

---

## My first year with event sourcing (in Symfony)

<dl>
  <dt>Description</dt>
  <dd>Over the last couple of years, I have heard of Event sourcing but didn't really know where to start until I did a tutorial at DPC '17. After having some basic information it was time to start a Hackathon and after that something production worty. In this talk I will try to give the best information to get started and to know some of the problems you can face if you begin event-sourcing.</dd>
</dl>

[Slides](https://noti.st/webbaard/t39eUN/my-first-year-with-event-sourcing)  
~~Video~~

By [Tim Huijzers](https://connect.symfony.com/profile/thuijzers)  
![github](icon/github.png) [@webbaard](https://github.com/webbaard)  
![twitter](icon/twitter.png) [@Dragem](https://twitter.com/Dragem)

---

## Symfony 4 internals

<dl>
  <dt>Description</dt>
  <dd>Symfony is a request and response framework. But what about all that magic that happens around your code? Why isn’t autowring slowing things down? And how is it that Symfony components can be so decoupled but sill play so well together? I will show you the Symfony internals and its architecture. This talk will go over the architecture of Symfony. We will follow the request and the response paths throw the framework. We will do some stops at the components that are more awesome than others. This talk is perfect for you who is working with Symfony or Laravel and want to understand what the framework actually is doing for you.</dd>
</dl>

[Slides](https://slideshare.net/TobiasNyholm/symfony4-internals-125268511)  
~~Video~~

By [Tobias Nyholm](https://connect.symfony.com/profile/tobias)  
![github](icon/github.png) [@Nyholm](https://github.com/Nyholm)  
![twitter](icon/twitter.png) [@TobiasNyholm](https://twitter.com/TobiasNyholm)

---

## What’s a typical Symfony 4.2 application like?

<dl>
  <dt>Description</dt>
  <dd>Symfony's configuration system has improved a lot in recent years. Version 4.2 brings a lot of minor improvements that all together give an even better developer experience. Let's step back and look at how we can tackle all of the most common problems using the new approaches! This will include tricks for configuring services as easily as possible, handling different environment configuration and the hugely important topic of environment variables and secrets. Best of all, we'll discuss some strategies to migrate your existing apps so you're never going to be left behind.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Nicolas Grekas](https://connect.symfony.com/profile/nicolas-grekas)  
![github](icon/github.png) [@nicolas-grekas](https://github.com/nicolas-grekas)  
![twitter](icon/twitter.png) [@nicolasgrekas](https://twitter.com/nicolasgrekas)

---

## Modern application built from scratch: API Platform FTW

<dl>
  <dt>Description</dt>
  <dd>Scenario: You had an awesome idea. A brand new business. So you have to test it‘s adherence to market… as soon as possible. How? Fortunately we have Symfony and API Platform. This session will cover main topics to build a real world project on top of REST and GraphQL APIs with modern authentication while delivering clients and documentation. Barely touching PHP code for that.</dd>
</dl>

[Slides](https://slideshare.net/duodraco/modern-application-built-from-scratch-api-platform-ftw-125261397)  
~~Video~~

By [Anderson Casimiro](https://connect.symfony.com/profile/duodraco)  
![github](icon/github.png) [@duodraco](https://github.com/duodraco)  
![twitter](icon/twitter.png) [@duodraco](https://twitter.com/duodraco)

---

## Integrate (Vue)JS components in a Symfony app, add E2E tests with Panther

<dl>
  <dt>Description</dt>
  <dd>Thanks to the new capabilities of the web platform (web components, Progressive Web Apps…) and the rise of modern JS libraries (Vue, React, Angular) almost all modern Symfony applications must leverage the frontend ecosystem. Symfony 4 embed many gems that make it easy to integrate modern JavaScript within the framework, including the first component entirely written in JS: Webpack Encore. In Symfony 4.2, another component that is super convenient for apps containing JS code has been released: Panther, a PHP library compatible with BrowserKit, that drives real web browsers to create end-to-end (E2E) tests with ease. During this talk, I'll show you how to cleanly integrate modern JavaScript code with Symfony and Twig and how to test such applications using Panther. The examples will use VueJS, because it’s probably the easiest JS framework to get started with as a PHP developer, but all the tips and tricks will be applicable with other libraries such as React or Angular.</dd>
</dl>

[Slides](https://slideshare.net/coopTilleuls/progressively-enhance-your-symfony-4-app-using-vue-api-platform-mercure-and-panther)  
~~Video~~  

By [Kévin Dunglas](https://connect.symfony.com/profile/dunglas)  
![github](icon/github.png) [@dunglas](https://github.com/dunglas)  
![twitter](icon/twitter.png) [@dunglas](https://twitter.com/dunglas)

---

## Profiling your Symfony application

<dl>
  <dt>Description</dt>
  <dd>A 1 second delay on an e-commerce site can result in a 7% reduction in your conversion rate; but profiling isn't just important in e-commerce when limited resources are available. Profiling is really important and there are now a host of tools to help you profile your application through means other than naive profiling. In this talk we'll look at how to identify bottlenecks in your application using a variety of tools; and how we can use those profiler results to improve our Symfony applications' performance.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Michael Cullum](https://connect.symfony.com/profile/unknownbliss)  
![github](icon/github.png) [@michaelcullum](https://github.com/michaelcullum)  
![twitter](icon/twitter.png) [@michaelcullumuk](https://twitter.com/michaelcullumuk)

---

## A year of Symfony

<dl>
  <dt>Description</dt>
  <dd>A lot happened! 52 blog posts to help you keep up with all new things, a looooot of pull requests, 2 new versions out… Well I'm sure you missed something. Let's review what happened during last year: basically we'll see and/or discover nice new features that appeared since the last year.</dd>
</dl>

[Slides](https://speakerdeck.com/saro0h/symfonycon-lisbon-a-year-of-symfony)  
~~Video~~

By [Nicolas Grekas](https://connect.symfony.com/profile/nicolas-grekas)  
![github](icon/github.png) [@nicolas-grekas](https://github.com/nicolas-grekas)  
![twitter](icon/twitter.png) [@nicolasgrekas](https://twitter.com/nicolasgrekas)

And [Sarah Khalil](https://connect.symfony.com/profile/saro0h)  
![github](icon/github.png) [@saro0h](https://github.com/saro0h)  
![twitter](icon/twitter.png) [@Saro0h](https://twitter.com/Saro0h)

---

---

---

# Lightning Talks
