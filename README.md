<div id="top" align="center">
<h1>GH Repo Template</h1>

<p>Template for new Github repos</p>

[Report Issue](https://github.com/Zheng-Bote/repo-template/issues) [Request Feature](https://github.com/Zheng-Bote/repo-template/pulls)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
![GitHub Created At](https://img.shields.io/github/created-at/Zheng-Bote/repo-template)

</div>

<hr>

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

**Table of Contents**

- [Description](#description)
  - [Features](#features)
  - [Status](#status)
    - [Repo](#repo)
    - [Readme](#readme)
    - [Markdown files](#markdown-files)
- [Installation](#installation)
  - [Dependencies](#dependencies)
  - [folder structure](#folder-structure)
  - [Usage/Examples](#usageexamples)
- [API Reference](#api-reference)
  - [Inputs](#inputs)
  - [Outputs](#outputs)
  - [Parameters](#parameters)
- [Documentation](#documentation)
  - [Architecture / Deployment-View](#architecture--deployment-view)
  - [Github Page](#github-page)
  - [Github Wiki](#github-wiki)
  - [Screenshots](#screenshots)
- [Authors and License](#authors-and-license)
  - [License](#license)
    - [MIT License](#mit-license)
    - [Apache License](#apache-license)
  - [Authors](#authors)
    - [Code Contributors](#code-contributors)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

<hr>

# Description

![GHA](https://img.shields.io/badge/Github-Action-black?logo=githubactions)
![Node](https://img.shields.io/badge/Node-20-blue?logo=tsnode)

Repo template with README-template and some Github workflows and Github actions.

### Features

- \[x] MIT license
- \[x] works as designed
- \[ ] no bugs
- \[x] some more or less usefull Github Actions

<p align="right">(<a href="#top">back to top</a>)</p>

## Status

### Repo

![Status](https://img.shields.io/badge/Status-works-green)
![GitHub Release Date](https://img.shields.io/github/release-date/Zheng-Bote/repo-template)

![GitHub Issues](https://img.shields.io/github/issues/Zheng-Bote/repo-template)
![GitHub Pull Requests](https://img.shields.io/github/issues-pr/Zheng-Bote/repo-template)

### Readme

[![Repo - create Repo-Tree in README.md](https://github.com/Zheng-Bote/repo-template/actions/workflows/repo-create_tree_readme.yml/badge.svg)](https://github.com/Zheng-Bote/repo-template/actions/workflows/repo-create_tree_readme.yml)
[![Repo - add Actions In/Out to README](https://github.com/Zheng-Bote/repo-template/actions/workflows/repo-actions_docu.yml/badge.svg)](https://github.com/Zheng-Bote/repo-template/actions/workflows/repo-actions_docu.yml)

[![Repo - update Readme](https://github.com/Zheng-Bote/repo-template/actions/workflows/repo-call_Readme.yml/badge.svg)](https://github.com/Zheng-Bote/repo-template/actions/workflows/repo-call_Readme.yml)

### Markdown files

[![Repo - create TOC of Markdown files](https://github.com/Zheng-Bote/repo-template/actions/workflows/repo-create_doctoc_md.yml/badge.svg)](https://github.com/Zheng-Bote/repo-template/actions/workflows/repo-create_doctoc_md.yml)

create ToC in Markdown files in folders

- .github/actions/\*\*
- .github/workflows/\*\*
- dist/\*\*
- docs/\*\*

<p align="right">(<a href="#top">back to top</a>)</p>

# Installation

bla bla ... everything easy and green with No Code/Low code and without any costs

## Dependencies

bla bla ... with a little help from my friends

## folder structure

<!-- readme-tree start -->

```
.
├── .github
│   ├── actions
│   │   └── doctoc
│   │       ├── action.yml
│   │       └── dist
│   │           ├── index.js
│   │           ├── index.js.map
│   │           ├── licenses.txt
│   │           └── sourcemap-register.js
│   └── workflows
│       ├── repo-actions_docu.yml
│       ├── repo-call_Readme.yml
│       ├── repo-create_doctoc.yml_
│       ├── repo-create_doctoc_md.yml
│       └── repo-create_tree_readme.yml
├── LICENSE
├── LICENSE_Apache-2
├── LICENSE_GPL-2
├── LICENSE_GPL-3
├── LICENSE_MIT
├── README.md
└── tree.bak

5 directories, 17 files
```

<!-- readme-tree end -->

<p align="right">(<a href="#top">back to top</a>)</p>

## Usage/Examples

bla bla ... usage is intuitive and runs mostly automatically with no needs of any knowledge

```HTML
<mark> under construction </mark>
```

<p align="right">(<a href="#top">back to top</a>)</p>

# API Reference

<hr>

![GHA](https://img.shields.io/badge/Github-Action-black?logo=githubactions)

_Inputs/Outputs will be filled automatically by `.github/workflows/repo-actions_docu.yml`_

## Inputs

## Outputs

<hr>

<p align="right">(<a href="#top">back to top</a>)</p>

## Parameters

**Workflow or program**

| Parameter    | Type     | Description                          |
| :----------- | :------- | :----------------------------------- |
| `name`       | `string` | _Optional_ name-of-copyright-holder  |
| `created`    | `string` | _Optional_ <YYYY>                    |
| `version`    | `string` | _Optional_ \<v0.0.0>                 |
| `link_left`  | `string` | _Optional_ link-to-contact-page      |
| `link_right` | `string` | _Optional_ link-to-legal-notice-page |

<p align="right">(<a href="#top">back to top</a>)</p>

# Documentation

see also: <https://linktodocumentation>

## Architecture / Deployment-View

```mermaid
block-beta
  columns 4
  Repo:4
  block:Structure:2
    columns 4
    id1[[".github Actions / Workflows"]]
    block:group1:1
      columns 2
      actions workflow
    end
    id2["docs"]
    id3["dist"]
    id4["src"]
  end
```

```mermaid
flowchart TD;
    A[Workflow]-. parameter .->B[[callable Workflow]]
    A[Workflow]-. parameter .->C[[callable Workflow]]
    B-- parameter -->D[Action]
    C-- parameter -->E[Action]
    D-->F(README)
    E-->G(Markdown files);
```

<p align="right">(<a href="#top">back to top</a>)</p>

## Github Page

[![GH-Page](https://img.shields.io/badge/Github-Pages-black?logo=github)](https://www.github.com/Zheng-Bote)

## Github Wiki

[![GH-Wiki](https://img.shields.io/badge/Github-Wiki-black?logo=github)](https://www.github.com/Zheng-Bote)

> \[!NOTE]
> Useful information that users should know, even when skimming content.

> \[!TIP]
> Helpful advice for doing things better or more easily.

> \[!IMPORTANT]
> Key information users need to know to achieve their goal.

> \[!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> \[!CAUTION]
> Advises about risks or negative outcomes of certain actions.

<p align="right">(<a href="#top">back to top</a>)</p>

## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

<p align="right">(<a href="#top">back to top</a>)</p>

# Authors and License

## License

**_other licenses see files `LICENSE_<name>`\_**

### MIT License

**This Repo-Template is using the MIT-License**

MIT License

Copyright (c) 2024 ZHENG Robert

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

        https://choosealicense.com/licenses/mit/

### Apache License

Apache License, Version 2.0

Copyright (c) \[year] \[fullname]

The 2.0 version of the Apache License, approved by the ASF in 2004, helps us achieve our goal of providing reliable and long-lived software products through collaborative, open-source software development.

All packages produced by the ASF are implicitly licensed under the Apache License, Version 2.0, unless otherwise explicitly stated.

        https://www.apache.org/licenses/LICENSE-2.0

## Authors

- [![Zheng Robert](https://img.shields.io/badge/Github-Zheng_Robert-black?logo=github)](https://www.github.com/Zheng-Bote)

### Code Contributors

![Contributors](https://img.shields.io/github/contributors/Zheng-Bote/repo-template?color=dark-green)

[![Zheng Robert](https://img.shields.io/badge/Github-Zheng_Robert-black?logo=github)](https://www.github.com/Zheng-Bote)

<hr>

:vulcan_salute:

<p align="right">(<a href="#top">back to top</a>)</p>
