# The Art of Microfrontends

"The Art of Microfrontends", published by Packt.

Order the book [at Amazon](https://www.amazon.com/dp/1800563566/).

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

For the samples of chapter 7 (server-side composition) and chapter 11 (siteless UIs) the code has been split across multiple repositories. This was done to illustrate the distributed nature of microfrontends in general, and in particular of the given approaches.

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
