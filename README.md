# Arpan's 11ty blog

A personal blog built using [Eleventy](https://github.com/11ty/eleventy) static site generator. Based on [Eleventy-base-blog](https://github.com/11ty/eleventy-base-blog).

## How to Run on Local

```
npx eleventy
```

Or build and host locally for local development
```
npx eleventy --serve
```

Or build automatically when a template changes:
```
npx eleventy --watch
```

Or in debug mode:
```
DEBUG=* npx eleventy
```

## Build your own

### 1. Clone this Repository

```
git clone https://github.com/11ty/eleventy-base-blog.git my-blog-name
```

### 2. Navigate to the directory

```
cd my-blog-name
```

Specifically have a look at `.eleventy.js` to see if you want to configure any Eleventy options differently.


### 3. Install dependencies

```
npm install
```

### 4. Edit _data/metadata.json
