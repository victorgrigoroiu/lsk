# LaTex Starter kit

## Start here [LaTexBase](https://latexbase.com)

## Latex Online: [Overleaf](https://www.overleaf.com)

## Latex Tips & Tricks

* change how latex displays the chaptertitle (to avoid changing the table of contents, table lists, etc. Please place this after those LaTex constructs are created)
```
\usepackage{titlesec} % required package

% special settings
\titleformat{\chapter}[display]
  {\normalfont\bfseries}{}{0pt}{\Huge{\thechapter. }}
```
* change indentation of the paragraphs
```
\usepackage[parfill]{parskip} % just import the package
```

## Install [MikTex](https://miktex.org/)

* [Download](https://miktex.org/download)
* [Documentation(html)](https://docs.miktex.org/2.9/manual/)
* [Documentation(pdf)](https://ftp.fau.de/ctan/systems/win32/miktex/doc/2.9/miktex.pdf)

## Editor('s)

### [Atom](https://atom.io/)

List of good atom plug-ins:
* file-icons
* hightlight-selected
* language-latex
* latex
* linter-latex (disabled for the time)
* linter
* linter-ui-default
* prettier-atom
* pdf-view
* minimap
* some sort of spell check, [this](https://atom.io/packages/spell-check) ?

### [Visual Studi Code](https://code.visualstudio.com/)

## LaTex "IDE"

[TexMaker](http://www.xm1math.net/texmaker/index.html)

## IGNORE Versioning ( ... [git](https://git-scm.com/) )

### Basic git commmands

| Command | Description |
|---------|-------------|
|`git status`| desc is wip ....|
|`git add .`| desc is wip ....|
|`git commit -m "some message"`| desc is wip ....|
|`git commit -a -m "some other message"`| desc is wip ....|
|`git stash -save "some funky name"`| desc is wip ....|
|`git stash apply/pop`| desc is wip ....|
|`ggit checkout -- file`| desc is wip ....|

## Place holder text

* [lorem ipsum](https://loremipsum.io/)
* [bacon ipsum](https://baconipsum.com/)

## Resource List

* [LaTex Core Documentation](https://www.latex-project.org/help/documentation/#source-code-documentation)
* [LATEX2ε for class and package writers](https://www.latex-project.org/help/documentation/clsguide.pdf)
* [LaTex for Authors Document](https://www.latex-project.org/help/documentation/usrguide.pdf)
* [LaTex font selection](https://www.latex-project.org/help/documentation/fntguide.pdf)
* [The Not So ShortIntroduction to LATEX2](https://tobi.oetiker.ch/lshort/lshort.pdf)
* [MiKTeX Manual](https://ctan.mirror.norbert-ruehl.de/systems/win32/miktex/doc/2.9/miktex.pdf)
* [Using LATEX to Write a PhD Thesis](https://www.dickimaw-books.com/latex/thesis/thesis-report.pdf)
* [Writing a thesis with LATEX](https://tug.org/pracjourn/2008-1/mori/mori.pdf)
* [ShareLatex Tutorial Videos](https://www.youtube.com/user/ShareLaTeX/videos)
* [Notepad++](https://notepad-plus-plus.org/download/v7.6.3.html)

#### [Bär](https://www.youtube.com/watch?v=2-Q5Q_fVW-o&t=23168s)
