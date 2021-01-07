# QWIC Engineering Styleguides

We externalized (for now) the styleguides that we are going to use for our projects.

1. [Javascript styleguide](https://github.com/airbnb/javascript)
2. [Typescript styleguide](https://github.com/unional/typescript-guidelines)
3. [Dart styleguide](https://dart.dev/guides/language/effective-dart/style)
4. [Flutter styleguide](https://github.com/flutter/flutter/wiki/Style-guide-for-Flutter-repo#prefer-single-quotes-for-strings)
5. Github styleguide:

PR titles
```
JIRA-321 Refacter consumer service due to performance issues
```

Commits should have this structure:
```
<Jira task number> <short description>

(optional line) [ci skip]

<longer description>
```
Important points:
* Short description should have max 50 characters
* Longer description can span multiple lines
* Only add `[ci skip]` if you don't want to trigger a CircleCI build
* Keep the spacing as shown to facilitate readability on tighter pages
  
Example of commit that I don't want to trigger CI build: 
```
SE-123 Updated readme

[ci skip]

Added styleguide documentation for qwic engineering team.
This is extra line makes the description longer.
```

Reference to git commit styleguide [here](https://chris.beams.io/posts/git-commit/)

## About us
QWIC is a Dutch e-bike manufacturer with HQ in Amsterdam. If you want to learn more visit https://qwic.nl
