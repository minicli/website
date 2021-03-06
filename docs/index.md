<p align="center">
<img src="https://minicli.dev/images/minicli_logo_term_pink.png" align="center" alt="logo" title="Minicli logo" alt="Minicli Logo" width="200">
</p>

<p align="center">
    <a href="//packagist.org/packages/minicli/minicli">
        <img src="https://poser.pugx.org/minicli/minicli/v" alt="Latest Stable Version" title="Latest Stable Version">
    </a>
    <a href="//packagist.org/packages/minicli/minicli">
        <img src="https://poser.pugx.org/minicli/minicli/downloads" alt="Total Downloads" title="Total Downloads">
    </a>
    <a href="//packagist.org/packages/minicli/minicli">
        <img src="https://poser.pugx.org/minicli/minicli/license" alt="License" title="License">
    </a>
    <a href="https://docs.minicli.dev/en/latest/?badge=latest">
        <img src="https://readthedocs.org/projects/minicliphp/badge/?version=latest" alt="Documentation Status" title="Documentation Status">
    </a>
</p>

# Home
Minicli is a minimalist, dependency-free framework for building CLI-centric PHP applications. It provides a structured way to organize your commands, as well as various helpers to facilitate working with command arguments, obtaining input from users, and printing colored output.

![Minicli app example](images/screenshot_app.png)

## Dependency-free: What Does it Mean

What does it mean to be dependency-free? It means that you can build a functional CLI PHP application without dozens of nested user-land dependencies. The basic `minicli/minicli` package has only **testing** dependencies (only installed when you clone Minicli for development), and a couple system requirements:

- PHP >= 7.3
- `ext-readline` for obtaining user input

Apart from that, you'll need [Composer](https://getcomposer.org/) to install and use Minicli.

## Getting Started

There are mainly two ways to get started: you can choose to create a project from scratch, or you can use our application repository template, which sets up a minimal structure with Command Namespaces and Controllers.

Both methods are explained in detail in the [Getting Started Guide](/01-getting_started).
## Building Minicli

!!! note
    Minicli has evolved a lot since that series was initially written, but that was the base for what Minicli is today.

The following tutorials on [dev.to](https://dev.to/erikaheidi) compose a series named "Building Minicli", where we created the first version of `minicli` from scratch:

 - Part 1: [Bootstrapping a CLI PHP Application in Vanilla PHP](https://dev.to/erikaheidi/bootstrapping-a-cli-php-application-in-vanilla-php-4ee) [ [minicli v.0.1.0](https://github.com/erikaheidi/minicli/tree/0.1.0) ]
 - Part 2: [Building minicli: Implementing Command Controllers](https://dev.to/erikaheidi/php-in-the-command-line-implementing-command-controllers-13lh) [ [minicli v.0.1.2](https://github.com/erikaheidi/minicli/tree/0.1.2) ]
 - Part 3: [Building minicli: Autoloading Command Namespaces](https://dev.to/erikaheidi/building-minicli-autoloading-command-namespaces-3ljm) [ [minicli v.0.1.3](https://github.com/erikaheidi/minicli/tree/0.1.3) ]
 - Part 4: [Introducing minicli: a microframework for CLI-centric PHP applications](https://dev.to/erikaheidi/introducing-minicli-a-microframework-for-cli-centric-php-applications-44ik)

## Created with Minicli

- [Dolphin](https://github.com/do-community/dolphin) - a CLI tool for managing DigitalOcean servers with Ansible.
