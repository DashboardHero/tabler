The same Tabler admin you know and love - easier to customize and work with. A functional Single Page Application that you can ship today.
React, Angular and Vue are great technologies, but too complex for a project the size of an admin dashboard. 
This version of Tabler comes with components, folder-based routing and the same MIT license.

![Tabler admin view](https://raw.githubusercontent.com/tabler/tabler/dev/static/tabler-preview.png)

---

# Overview

React components are great - but React has a learning curve of at least 2 months. Often, developers need to showcase their work or launch an MVP in what little spare time they have.

Svelte components are just javascript, HTML(with some templating) and CSS. Things you know and understand. Moreover, you can go through the Svelte documentation in 30 minutes, and start working productively on your amazing admin dashboard the next 30.


## Components

Instead of working directly with HTML, work with components.

Instead of this:
![Tabler admin html code](https://i.ibb.co/DCc5yRd/Screen-Shot-2020-01-28-at-10-10-16-AM.jpg)

Work with this:
```
<TopBar/>
<Nav />
<InnerPage title="Dashboard"/>
<div class="row row-deck">
   <div class="col-sm-6 col-lg-3">
   <Card data = { data.getSalesCardData() } />
   </div>
</div>
...
```
## Folder-based routing(with multiple routes, for easy to understand public - Login/Register - layouts)

```
src/routes/Dashboard
src/routes/FormElements
src/routes/Base
src/routes/Charts
src/routes/Charts/ApexCharts
```
You get the idea. No router setup needed.

## Environment variables

You might want to have a dev and prod environment. Tabler components makes it easy, with a rollup plugin.

## Single component rendering

Work on and debug one component at a time. Divide et impera!

## Easy deployment

The build process outputs a static website, that you can deploy to surge, now, Firebase Hosting or your favourite web hosting provider. Easy, fast and reliable!




