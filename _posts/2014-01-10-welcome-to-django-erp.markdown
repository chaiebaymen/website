---
layout: post
title:  "Welcome to django ERP!"
categories: django-erp update
---

Welcome to the new website of **django ERP** project!

## A brief introduction
### First of all: what *django ERP* is?

Well, as its name says, **django ERP** is an *open-source*, *user-oriented*, **ERP system** based on [Django Framework] [Django].

Its story **begins in 2006**, when its founder, **Emanuele Bertoldi**, decided to develop an ERP system for small and medium companies based on [Python]. At that time, most of ERP solutions were based on old technologies and paradigms, with ugly **UIs** and complex workflows, so the *vision* was to create a solution with an elegant UI and some basic but effective applications to help the users in big problems, leaving the rest to the everyday office suites.

At that time, the project took the name of [Prometeo ERP] and was just a desktop-based solution based on [wxWidgets]. After one year, more or less, the original author decided to rewrite the entire codebase from scratch basing the entire project over a solid *web framework*... **That day, [Django] officially entered in the game.**

### And then? What's next?

After a couple of years with [Prometeo ERP] project, some curcial issues reveal big design-problems in the general software architecture making really hard to maintain and extend the framework. Also, new technologies and programming paradigms became prominent in the market. Finally, some backward incompatibilities with new versions of [Django] make really urgent to take a crucial decision:

> Put more efforts on **Prometeo ERP** codebase or rewrite all from scratch, again?

Well, if you're visiting this site, you already know the **answer**.

## A new hope

### What? Again?

At this point, many experienced software architects/engineers may start to think: another **rewrite-addicted**? Why start again from scratch? Do you know it is usually a bad idea? Do you know it is usually better to simply refactor your code instead of rewrite it from scratch?

Well, our defense could simply be: yes, we know, and this is *usually* true.

### But...

We decided to fork a **new brand project**, based on [Prometeo ERP] experience, taking advantages of new technologies (**i.e.** *[HTML5]*, *[Django]>1.5.x*, *[jQuery]*, etc.), using a new development platform ([GitHub]) and switching to a new license model ([MIT] [MIT License]).

The new brand it's not just a matter of name, **it's a new project identity and philosophy**.

### The brand

The new name, **django ERP**, emphasizes the importance of [Django] framework and its main role in the project architecture, while the tagline ***"free your business"*** keeps a link with its ancestor ([Prometeo ERP]).

The logo is an optical illusion: what do you see? An **hand-cursor** (*technology*, *web*) or a **swan** (*elegance*, *freedom*)?

![django ERP logo]({{ site.baseurl }}/static/logo.png)

The **vision** is all here: *technology, accessibility, elegance and freedom*.

### The philosophy

The new **django ERP** philosophy is based on **four keys points**:

 1. It should be **modern**, in terms of *technologies* and *paradigms*.
 2. It should be **accessible**, in terms of *responsive layout* and *content accessibility*.
 3. It should be **elegant**, in terms of *UI*, *UX* and *design*.
 4. It should be **open**, in terms of *source code policy* and *functional extensibility*.
 
Regarding the source code, the following programming paradigms will be used:

 1. [**Test driven development**] [TDD] (TDD): maybe your business is not mission-critical like a space shuttle launch, but for us, like you, ***it is***. So we use the same methodology used to launch a space shuttle: test, test and test again your code. **Our plan is to cover every line of our core technology by a test case**.
 
 2. [**Keep it simple, stupid**] [KISS] (KISS): if the software should be extensible, should also be easy to understand. This principle cover each aspect of **django ERP**, from *source code architecture*, to *UI layout*. **Our plan is to make the software simple to understand and simple to modify**.
 
 3. [**Release early, release often**] [Release early]: what's the point to develop an awesome piece of software if users have to wait for a long time in order to use it? Our opinion is the risk of loosing opportunities is too high. Furthermore, to make an awesome **ERP solution** we need **feedback from users**. Early. **Our plan is to release for each new big feature (a new *app*, a new *system-wide function*, etc.)**.
 
 4. **Limit your dependencies**: we know that reinvent the wheel every time is time-consuming and error-prone. But we also dislike the opposite: too many dependencies make the software hard to manage and maintain. And so? **Our plan is to be very careful about adding new dependencies to the system. We want an easy install process and upgrade policy**.
 
With these points in mind, we hope to successfully create an high-quality piece of software for all the users (people or companies) looking for a modern and scalable **ERP solution**.

### A free project

But now, the best part comes: this is a **free** and **open-source** project, released under the [MIT license], which means **you don't need to pay any fee** to use it!

It also means that your needs are not just a **customization**: they could be part of the **core** from the beginning. **We're open to any discussion, suggestion and contribution**.

So, what are you waiting for? [**Be the first!**] [How to contribute]

## Roadmap

In order to be informed about the current state of the project and future plans, please visit the [official roadmap].

To know more about **django ERP** releases, please read the [official release policy].

## How to contribute

If you want to contribute, please follow the instructions reported [here] [How to contribute].

**Thank you!**

***--- django ERP Team***

[Django]: https://www.djangoproject.com
[Python]: http://www.python.org
[Prometeo ERP]: https://code.google.com/p/prometeo-erp
[wxWidgets]: http://www.wxwidgets.org
[GitHub]: https://github.com/djangoERPTeam/django-erp
[HTML5]: http://www.w3schools.com/html/html5_intro.asp
[jQuery]: http://jquery.com
[MIT License]: http://en.wikipedia.org/wiki/MIT_License
[TDD]: http://en.wikipedia.org/wiki/Test-driven_development
[KISS]: http://en.wikipedia.org/wiki/KISS_principle
[Release early]: http://en.wikipedia.org/wiki/Release_early,_release_often
[official roadmap]: https://github.com/djangoERPTeam/django-erp/wiki/Roadmap
[official release policy]: https://github.com/djangoERPTeam/django-erp/wiki/Release-policy
[How to contribute]: https://github.com/djangoERPTeam/django-erp/wiki/How-to-contribute
