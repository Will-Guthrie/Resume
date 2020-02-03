# Resume

Open source template basically used 1:1 from Allan Wang (who in turn is based off Deedy). 

Link to his version [here](https://github.com/AllanWang/AllanWang-Resume).

## Dependencies

The template will only compile with *XeTeX*.
It also supports magic comments for [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop) (VS-Code)

## Components

### Header

The header is bundled up with a series of name definitions like so:

```latex
\firstname{First}
\lastname{Last}
\phone{(xxx) xxx-xxxx}
\email{me@website.ca}
\website{website.ca}
\github{GithubUsername}
\header
```

### Projects

Project headers are formatted through three arguments:

The name, the organization, and the date.

```latex
\project{Kotlin Android Utils}{Open Source}{Jun 2017 - Present}
```

### Text Styles

The cls bundles some formatted text styles, including

```latex
\section{Main}
\subsection{Sub}
\descript{Description}
\content{Content}
```

### Links

As an Android developer, I've added some helper functions for linking projects. Namely:

```latex
\githublink{name}{repo}{text}
\mygithub{repo}[text (repo name be default)]
\playstorelink{package}{text}
```

Links are typically formatted as lowercase to avoid conflicts with the upper case text styles.



