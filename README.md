# The Art of Micro Frontends

<a href="https://www.packtpub.com/product/the-art-of-microfrontends/9781800563568"><img src="https://static.packt-cdn.com/products/9781800563568/cover/smaller" alt="The Art of Micro Frontends" height="256px" align="right"></a>

This is the code repository for [The Art of Micro Frontends](https://www.packtpub.com/product/the-art-of-microfrontends/9781800563568), published by Packt.

**Build websites using compositional UIs that grow naturally as your application scales**

## What is this book about?
Micro frontend is a web architecture for frontend development borrowed from the idea of microservices in software development, where each module of the frontend is developed and shipped in isolation to avoid complexity and a single point of failure for your frontend.
Complete with hands-on tutorials, projects, and self-assessment questions, this easy-to-follow guide will take you through the patterns available for implementing a micro frontend solution. You’ll learn about micro frontends in general, the different architecture styles and their areas of use, how to prepare teams for the change to micro frontends, as well as how to adjust the UI design for scalability. Starting with the simplest variants of micro frontend architectures, the book progresses from static approaches to fully dynamic solutions that allow maximum scalability with faster release cycles. In the concluding chapters, you'll reinforce the knowledge you’ve gained by working on different case studies relating to micro frontends.
By the end of this book, you'll be able to decide if and how micro frontends should be implemented to achieve scalability for your user interface (UI).

This book covers the following exciting features:
* Understand how to choose the right micro frontend architecture
* Design screens for compositional UIs
* Create a great developer experience for micro frontend solutions
* Achieve enhanced user experiences with micro frontends
* Introduce governance and boundary checks for managing distributed frontends
* Build scalable modular web applications from scratch or by migrating an existing monolith

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1800563566) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
if (test expression)
{
  Statement upon condition is true
}
```
## Cloning the Repository

This repository contains all repositories with sample codes. These repositories have been included as Git modules. In order to check them out at clone you should add the `--recurse-submodules` flag:

```sh
git clone --recurse-submodules https://github.com/PacktPublishing/The-Art-of-Microfrontends.git
```

## Updating the Repository

Once the submodules are checked out the code is stuck at this point in time. Therefore, just like the repository itself, the submodules need to be pulled.

To do everything in a single command you can just use `--recurse-submodules` with `git pull`:

```sh
git pull --recurse-submodules
```

## Using the Code

Each directory containing a sample repository has a README file with instructions on what is necessary and how to run the code.

For the samples of chapter 7 (Server-side composition) and chapter 11 (Siteless UIs) the code has been split across multiple repositories. This was done to illustrate the distributed nature of microfrontends in general, and in particular of the given approaches.

The recommendation here would be to start with the gateway (chapter 7) and app shell (chapter 11) before running the MF repositories. In case of chapter 11 you'll also need to run the feed server.

Pretty much all samples have been created exclusively using web technologies such as HTML and JavaScript. For the edge-side composition example (chapter 8) a *Dockerfile* running an nginx server was added.

If you'll encounter any problem or have some improvement in mind then don't hesitate to open an [issue on GitHub](https://github.com/PacktPublishing/The-Art-of-Microfrontends/issues).

## Available Samples

* Chapter 5 - Types of Microfrontends
  * [Direct build integration](https://github.com/ArtOfMicrofrontends/05-pipeline)
  * [Looser coupling via lookup table](https://github.com/ArtOfMicrofrontends/05-server-discover)
* Chapter 6 - The Web Approach
  * [Pattern example](https://github.com/ArtOfMicrofrontends/06-web-approach)
* Chapter 7 - Server-Side Composition
  * [Gateway to orchstrate MFs](https://github.com/ArtOfMicrofrontends/07-gateway)
  * [Red MF bringing product page](https://github.com/ArtOfMicrofrontends/07-red)
  * [Blue MF bringing purchase ability](https://github.com/ArtOfMicrofrontends/07-blue)
  * [Green MF bringing recommendations](https://github.com/ArtOfMicrofrontends/07-green)
* Chapter 8 - Edge-Side Composition
  * [Pattern example](https://github.com/ArtOfMicrofrontends/08-edge-side-composition)
* Chapter 9 - Client-Side Compositionv
  * [Pattern example](https://github.com/ArtOfMicrofrontends/09-client-side-composition)
* Chapter 10 - SPA Composition
  * [Pattern example](https://github.com/ArtOfMicrofrontends/10-spa-composition)
* Chapter 11 - Siteless UIs
  * [App Shell to orchestrate MFs](https://github.com/ArtOfMicrofrontends/11-app-shell)
  * [Feed server to dynamically provision MFs](https://github.com/ArtOfMicrofrontends/11-service-feed)
  * [Balance MF bringing the balance sheet](https://github.com/ArtOfMicrofrontends/11-frontend-balance)
  * [Settings MF bringing the settings dialog](https://github.com/ArtOfMicrofrontends/11-frontend-settings)
  * [Tax MF offering an extension for the balance sheet](https://github.com/ArtOfMicrofrontends/11-frontend-tax)

**Following is what you need for this book:**
This book is for software/solution architects or (mostly lead) developers as well as web developers and frontend engineers. Beginner-level knowledge of HTML and CSS along with a solid understanding of JavaScript programming and its ecosystem, including Node.js and NPM, is assumed.

With the following software and hardware list you can run all code files present in the book (Chapter 1-16).

### Software and Hardware List

| Chapter  | Software required                   | OS required                        |
| -------- | ------------------------------------| -----------------------------------|
| 1 to 16      | Node.js 12                     | Windows, Mac OS X, and Linux (Any) |
| 1 to 16        | NPM 6            | Windows, Mac OS X, and Linux (Any) |
| 1 to 16        | ECMAScript 2015 (6) or above          | Windows, Mac OS X, and Linux (Any) |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://static.packt-cdn.com/downloads/9781800563568_ColorImages.pdf).

## Code in Action

Click on the following link to see the Code in Action:

[YouTube](https://www.youtube.com/playlist?list=PLeLcvrwLe185OWoZT0hfN5zesgVangK5M)

## Errata

* Page 160 (Pragraph 3,Line 18): **URL has to monitored** _should be_ **URL has to be monitored**


### Related products <Other books you may enjoy>
* Svelte 3 Up and Running [[Packt]](https://www.packtpub.com/product/svelte-3-up-and-running/9781839213625) [[Amazon]](https://www.amazon.com/dp/1839213620)

* Vue.js 3 By Example [[Packt]](https://www.packtpub.com/product/vue-js-3-by-example/9781838826345) [[Amazon]](https://www.amazon.com/dp/1838826343)

## Get to Know the Author
**Florian Rappl**
is a solution architect working on distributed web applications for digital transformation and IoT projects. His main interest lies in the implementation of micro frontends and their impact on teams and business models.
As the lead architect he helped to create outstanding web applications for many industry leading companies. He regularly gives lectures on software design patterns and web development. Florian won multiple prizes for his work over the years and is recognized as a Microsoft MVP for development technologies.
He started his career in software engineering before studying physics and helping to build an energy-efficient supercomputer. Florian currently lives in Munich, Germany, with his wife and two daughters.
