

This is a practice project created with [Build Websites with Hubo](https://pragprog.com/titles/bhhugo/build-websites-with-hugo/).


Command line

Craete a new site

```bash
hugo new site <SITE_NAME> 
```

Create post

```bash
## Example creating an about page
hugo new <SINGLE_PAGE_NAME>.md
```

Create site in the `public` directory

```bash
hugo --cleanDestinationDir --minify

## --cleanDestinationDir removes previous content in public
## --minify deletes unnecessary spaces and blank lines. It saves space.
```
