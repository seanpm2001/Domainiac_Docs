
***

# Domainiac Docs

## Domain listing

This document is a vital piece of documentation for Domainiac. It goes over the domain listing database. For the file structure that the project uses, see [`File-Structure`](/Docs/File-Structure/)

### URLL format

If you are unfamiliar with the URLL format, you can read more about it [:octocat: `here`](https://github.com/seanpm2001/URLL-Specification/) it takes less than 15 minutes to master the language.

### The URLL database

There is a database on all websites using each TLD (just the major parts of the site, not every webpage) in URLL format. For sites that use more than 1,000 subdomains, include the most common ones only. There is a 1000 subdomain limit per website.

The database is sorted by the type of website, into several categories. Each category is split into its own separarte file.

```shell
/Education/Education.com.urll
/Entertainment/Entertainment.com.urll
/Flash/Flash.com.urll //// Adobe Flash websites
/Streaming/Streaming.com.urll
```

These are not the only categories. There is a limit of 995 categories per domain, due to GitHub truncating files at 1001 entries in a directory. 5 files are reserved for configuration.

### Other inclusions

#### Onion sites

Onion sites are included.

#### www, https, and others

For these entries, `www` is not required, but `http` `https` `ftp` and others are.

### Exclusions

#### Illegal websites

Unfortunately, not all websites can be listed here, as much as I want them to be, as there is this really annoying thing called copyright. Sites such as `thepiratebay` and `wikileaks` unfortunately cannot be listed, because that would pose a legal risk to this project.

#### Malicious websites

Websites that are known to use malicious methods cannot be listed either. However, sites with DRM can be listed, but must have a DRM warning next to them, like so:

```c
youtube.com //// This site uses DRM
```

#### Sexual websites

Due to GitHubs terms of service, I also cannot list websites that have a focus on pornography.

#### The Reddit situation

Reddit subreddits are not considered unique domains, and are not included separately. Sites that do things similarly to this are also included into this scope.

***

**File version:** `1 (2023, Monday, May 8th at 7:08 pm PST)`

***
