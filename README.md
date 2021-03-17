# The Rashid Project

## About

### What is the Rashid project?

The Rashid project is a collection of program specifications and open source implementations of those specifications in various languages and environments.

## Naming Conventions

### Specifications

Specificiations should follow the format:

```
spec-[spec name]
```

e.g

```
spec-hello-world-cli
```

### Implementations

Implementations of a spec in a certain language without any major framework dependencies should follow the format:

```
[spec name]-[language name]
```

e.g.

```
hello-world-cli-php
```

Implementations of a spec in a certain language with a major framework dependency should follow the format:

```
[spec name]-[language name]-[dependency name]
```

e.g.

```
hello-world-cli-php-laravel
```

In some cases, implementations might contain two languages and/or major framework dependencies, for instance, a web application with a server side stack and a client side stack. In these cases the two languages and/or frameworks should be listed in order of fundamental importance to the implementation, for example server-side first, client-side second.

```
[spec name]-[server side language name]-[server side dependency name]-[client side language name]-[client side dependency name]
```

e.g.

```
hello-world-web-php-laravel-js-vue
```
