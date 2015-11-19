---
layout: post
title:  "Working on a fresh new UX"
categories: django-erp website restyle UX
---

With this post we want to show you a **preview** of what we are working on recently: a fresh new **UX (User eXperience)** for **django ERP**.

This is the natural *next step* on the road to modernize the entire **django ERP** public image (after [logo and official website restyling]). However, we really want to stress the concept that this restructuring is not just a matter of fashion: it will touch all the aspects of the system usability and the interaction feel the user will experiment during his work on **django ERP**.

Quoting from *Wikipedia*:

> User eXperience (UX) is about how a person feels about using a system. User experience highlights the experiential, affective, meaningful and valuable aspects of human-computer interaction (HCI) and product ownership, but it also covers a person’s perceptions of the practical aspects such as utility, ease of use and efficiency of the system. User experience is subjective in nature, because it is about an individual’s performance, feelings and thoughts about the system. User experience is dynamic, because it changes over time as the circumstances change.

At this point a good question should be: **why we need to refactor the *UX*?**

## The problem

To understand the reasons behind this decision, first take a look at the current state of **UX** on the *develop* branch:

**Login Page**
![django ERP old login page]({{ site.baseurl }}/media/djangoerp-old-ui0.png)

**Dashboard Page**
![django ERP old dashboard page]({{ site.baseurl }}/media/djangoerp-old-ui1.png)

The big problems with this layout are:

  1. It doesn't take advantage from modern [CSS3] and [Javascript] technologies for front-end logic.
  2. it's not **responsive**.
  3. It requires a quite large codebase.

Take advantage from modern technologies like **CSS3**, **HTML5** and **Javascript** is also a crucial point in order to enhance user satisfaction by improving the usability, reactivity, accessibility and pleasure provided in the interaction between the user and the software.

This is also the first claim of **django ERP** vision: [*be based on recent technologies*]({{ site.baseurl }}/#modern/).

Be responsive is a *must-have* nowadays for *modern web-based user interfaces*: everyone owns a smartphone and every smartphone is connected in some way to the Net. Many of us also own a tablet, or a netbook, or a phablet and so on. The obvious conclusion is that, if we do want to let the users to utilize **django ERP** on their portable devices - and we do -, we absolutely need a responsive UX.

This issue is strictly related to the second claim of **django ERP** vision: [*be accessible from any device*]({{ site.baseurl }}/#accessible/).

Finally, reducing the codebase could substantially speed up the loading time and improve the code maintainability and quality.

Ok, we need a responsive interface, we need an interface based on modern technologies and we don't want to rewrite it from scracth: how could we do?

Easy: take a look around and enter in the fantastic world of **front-end frameworks**. After trying it for the official **django ERP** website, we chose to adopt [Semantic UI] also for the software *UX*.

As its official website claims:

> [...] it is designed completely with em making responsive sizing a breeze. Design variations built into elements allow you to make the choice how content adjusts for tablet and mobile.

## The new look and feel

And here we are: finally **it's time to take a look** at the *work-in-progress* of our goal to bring a modern, elegant and usable UX to **django ERP**:

**Login Page**
![django ERP new login page]({{ site.baseurl }}/media/djangoerp-new-semantic-ui-preview0.png)

**Dashboard Page**
![django ERP new dashboard page]({{ site.baseurl }}/media/djangoerp-new-semantic-ui-preview1.png)

**Extended Mode Example**
![django ERP new extended mode example]({{ site.baseurl }}/media/djangoerp-new-semantic-ui-preview2.png)

**Modal Example**
![django ERP new modal example]({{ site.baseurl }}/media/djangoerp-new-semantic-ui-preview3.png)

As you can see the new default theme looks very **modern** and **sleek**, with **softer colours**, a **better organizad interface** in which all the **relevant elements are always visible and accesible** by the user. Of course, **this is just a preview**, so many **things could still change** before the release.

One of the most important change is the complete redesign of the **top navigation**:

![django ERP new navigation]({{ site.baseurl }}/media/djangoerp-new-top-bar.png)

On the left you can see a darker area which contains the header of the sidebar where the main navigation resides. It also includes the **django ERP brand** (which acts like a button to open the common **About** page with information on the current release of the software), the **Search** button, the **Quick Calendar** button and the **toggle** for the new **Extended Mode**.

On the right of the darker area, you can see the **Home** button, the **Breadcrumb** bar and the **User area**. The **User area** itself is composed by the **Bookmarks** tool, the **Notifications** inbox, the **User Profile** control and the **Logout** button.

In general, the **top navigation** requires now less pixels in height, so more **screen space** is available for **business-level information**, which are, at the end, the heart of an **ERP** software. The new **Extended Mode**, where the **sidebar** is hidden and its **header** is compacted to its minimal width, also grants the **maximum horizontal screen space** when needed (on desktop):

![django ERP new extended mode]({{ site.baseurl }}/media/djangoerp-new-extended-mode.png)

## Designed for all

If you've read the previous section, you have now an idea of what is going on with the **django ERP UX** on the classic *desktop side*.

But what really pushes forward the new UX is its ability to work also on **any mobile device** without loosing main functionalities, as you can see in the following screenshots:

**Login on Mobile**
![django ERP new mobile login example]({{ site.baseurl }}/media/djangoerp-new-semantic-ui-preview4.png)

**Modal on Mobile**
![django ERP new mobile modal example]({{ site.baseurl }}/media/djangoerp-new-semantic-ui-preview5.png)

**Sidebar on Mobile**
![django ERP new mobile sidebar example]({{ site.baseurl }}/media/djangoerp-new-semantic-ui-preview6.png)

The main differences between **mobile** and **desktop** versions are the **user area** moves to the bottom of the screen and the **sidebar** disappears and could be opened using the **Menu** button on the top navigation bar (which replaces the **Extended Mode** button, useless on mobile).

Many other tweaks to the UX are used in order **to maximize available space** on **small screens** and to **optimize readability and interaction** for **touch screens**.

## Follow the change

We are working **hard** to let the new UX land on the *develop branch* as soon as possible, before the **[0.1.0 release]**.

If you are interested in watching its development, you can follow the [zuck/django-erp feature-semantic-ui-theme] branch on *GitHub*.

If you would like to contribute, please read the [How to contribute] page on the [official Wiki].

**We always welcome any help and contribution!**

***--- django ERP Team***


[Semantic UI]: http://semantic-ui.com/
[logo and official website restyling]: {{ site.baseurl }}/blog/2015/09/26/logo-website-restyling/
[CSS3]: http://www.w3schools.com/css/css3_intro.asp
[Javascript]: http://www.w3schools.com/js/
[zuck/django-erp feature-semantic-ui-theme]: https://github.com/zuck/django-erp/tree/feature-semantic-ui-theme
[0.1.0 release]: https://github.com/django-erp/django-erp/wiki/Roadmap#010
[How to contribute]: https://github.com/django-erp/django-erp/wiki/How-to-contribute
[official Wiki]: https://github.com/django-erp/django-erp/wiki
