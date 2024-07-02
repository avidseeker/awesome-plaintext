<!-- vim: set tw=0: -->
<p align="center">Plain text tools, resources, and integrations</p>
<p align="center"><a href="https://awesome.re" target="_blank"><img src="https://awesome.re/badge-flat.svg"></a></p>

# Markup formats
Plain plain text:
- [Journal.TXT](https://journaltxt.github.io/) - Single-Text File Journals.
- [calcurse.apts](https://calcurse.org/files/manual.html#basics_files) - plain text calendar
- [journal.html](https://journal.miso.town/)
- [Feed.TXT](https://feedtxt.github.io) - free web feeds format in (plain) text w/ structured meta data
- [Manuscripts](http://manuscripts.github.io) - free book format - write books in (plain) text
- [Bib.TXT](http://bibtxt.github.io) - free bibliographies in text (unicode) format - BibTeX for the 21st century - books, articles, & more
- [journal-cli](https://journalcli.me/) - Index Your Markdown-Based Journal With Yaml Front Matter!
- [klog](https://github.com/jotaen/klog) - klog is a plain-text file format and a command line tool for time tracking.
- [todo.txt](https://github.com/todotxt/todo.txt) - Pretty well known text file format with applications on many platforms. - \*[Todo list in version control](http://urasaru.org/post/19414431348/getting-my-todo-list-under-version-control) - Based on using notational velocity and tracking it in git.
- [Todo.TXT](https://github.com/ginatrapani/todo.txt-cli/wiki/The-Todo.txt-Format) by Gina Trapani et al -- future-proof task tracking in a file you control; if you want to get it done, first write it down.
- [CookLang](https://cooklang.org/) - Recipe Markup Language

Miscellaneous:
- [diffscuss](http://blog.hut8labs.com/introducing-diffscuss.html) - plain-text code review system.
- \*[The Plain Person’s Guide to Plain Text Social Science](https://plain-text.co/) [[PDF Version](https://kieranhealy.org/files/papers/plain-person-text.pdf)].
- \*[Improving Health Care with Plain-Text Medical Records and Git](https://www.gizra.com/content/plain-text-medical-records/)
- [Poor Man's Issue Tracker](https://github.com/driusan/PoormanIssueTracker) - a loosely defined set of conventions for using the filesystem as an issue tracker.
- [bug](https://github.com/driusan/bug) - bug writes code problem reports to plain text files as per the poor man's issue tracker conventions. Issues are stored as human readable plaintext files, they branch and merge along with the rest of your code, and you can resolve conflicts using your standard tools.

Light Markup:
- **Markdown** -- see [Awesome Markdown](https://github.com/mundimark/awesome-markdown)
- [**Kramdown**](https://kramdown.gettalong.org) -- see [Awesome Kramdown](https://github.com/viennahtml/awesome-kramdown)
- **Wikipedia Markup / Wiki Text**
- **DokuWiki Markup**
- [**Wiki Creole**](http://www.wikicreole.org)
- [**Text with Instruction (.texti)**](https://texti.github.io) - structured documents in text with formatting conventions; the best of markdown, wikipedia markup, latex & Friends - all together now
- [**AsciiDoc**](http://www.methods.co.nz/asciidoc) by Stuart Rackham et al
- [**Rimu Markup**](http://rimumarkup.org) by Stuart Rackham et al
- **reStructured Text (.rst)**
- **[Org /Org mode (Ecmacs)](http://orgmode.org)** -- your life in (plain) text; keeping notes, maintaining TODO lists, planning projects, and writing documents in fast and effective (plain) text
- **[txt2tags](http://txt2tags.org)**

<!--
Extra reading:
- [Compare Wiki Syntax @ WikiMatrix](http://www.wikimatrix.org/syntax.php)
- [Markup & Markdown Madness!](https://markupmadness.github.io)
- [Lightweight markup language @ Wikipedia](https://en.wikipedia.org/wiki/Lightweight_markup_language)
-->

Typesetting markup:
- [LaTeX](http://www.texfaq.org/FAQ-latex)
- [SILE](https://sile-typesetter.org/what-is/) - a typesetting system written in Lua and using the HarfBuzz font shaper. It’s input syntax is somewhat inspired by LaTeX.
- [groff](https://gnu.org/software/groff/) - is a typesetting system that creates formatted output when given plain text mixed with formatting commands. Primarily used for man pages, it has been used for [books](https://rkrishnan.org/posts/2016-03-07-how-is-gopl-typeset.html) as well.
- [rinohtype](http://www.mos6581.org/rinohtype/master/) - a Python library that transforms a structured document into a professionally typeset PDF guided by a document template and style sheet.
- [pandoc](https://pandoc.org/) - If you need to convert files from one markup format into another, pandoc is your swiss-army knife.
- \*[Sustainable Authorship in Plain Text using Pandoc and Markdown](https://programminghistorian.org/en/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown)
- \*[Unicode Nearly Plain-Text Encoding of Mathematics](https://www.unicode.org/notes/tn28/UTN28-PlainTextMath-v3.pdf) - With a few conventions, Unicode1can encode manymathematical expressions in readable nearly plain text. Technically thisformat is a “lightly marked up format”; hence the use of “nearly”.
- [MathML](https://www.w3.org/Math/) - MathML is a low-level specification for mathematical and scientific content on the Web and beyond.
- \*[A list of MathML Tools](https://www.w3.org/wiki/Math_Tools)
- [AsciiDoctor](https://asciidoctor.org) - AsciiDoctor is a fast text processor & publishing toolchain for converting AsciiDoc to HTML5, DocBook & more.

Specification:
- [OpenAPI Specification](https://swagger.io/specification/) - a standard, language-agnostic interface to RESTful APIs which allows both humans and computers to discover and understand the capabilities of the service without access to source code, documentation, or through network traffic inspection.
- \*[OpenAPI.Tools](https://openapi.tools/) - List of various tools that use the OpenAPI Specification including Convertors, Validators, Documentation, Mock Servers, SDK Generators, Text Editors and more.
- [MSON](https://github.com/apiaryio/mson) - A description format for describing data structures in common markup formats such as JSON, XML or YAML.
- [CommonMark]

# Utilities
* [Moreutils][moreutils]
* [par][par]
* [fmt][fmt]
* [Fold][fold]

[moreutils]: https://joeyh.name/code/moreutils/
[par]: https://en.wikipedia.org/wiki/Par_(command)
[fmt]: https://en.wikipedia.org/wiki/Fmt_(Unix)
[fold]: https://en.wikipedia.org/wiki/Fold_(Unix)

# Configuration
- [etckeeper](https://etckeeper.branchable.com/). The [Arch Wiki](https://wiki.archlinux.org/title/Etckeeper) has a nice guide on usage.
- [NixOS](https://nixos.org/) is a completely declarative OS that uses `nix`, the purely functional package manager
- [RANCID](https://shrubbery.net/rancid/) -  RANCID monitors a device's configuration, including software and hardware (cards, serial numbers, etc) and uses a version-control-system to maintain history of changes.
- [Oxidised](https://github.com/ytti/oxidized) - Oxidized is a network device configuration backup tool. It's a RANCID replacement!
- \*[Blog post about Oxidised](https://log.cyconet.org/2016/01/29/oxidized-silly-attempt-at-really-awesome-new-cisco-config-differ/)
- \*[dotfiles.github.io](https://dotfiles.github.io/) - List of various dotfile resources, curated by github
- \*[Arch Wiki Guide](https://wiki.archlinux.org/index.php/Dotfiles#Version_control) on using version control for dotfiles
- [gnu stow](http://www.gnu.org/software/stow/)
- \*[http://www.terminally-incoherent.com/blog/2012/03/12/putting-your-vim-files-under-version-control/](putting-your-vim-files-under-version-control)
- [Editorconfig](http://editorconfig.org/) - Keep your coding styles in a .editorconfig file.

DNS:
- [clouddns](https://github.com/jhawthorn/clouddns) (Cloudfront)
- [namesync](https://github.com/dnerdy/namesync) (Cloudflare)
- [Terraform](https://www.terraform.io/docs/providers/) has providers for CloudFlare, UltraDNS, and PowerDNS

## Passwords
- \*[Question](http://stackoverflow.com/questions/559611/password-storage-in-source-control) on StackOverflow
- \*John Resig's [blog post](http://ejohn.org/blog/keeping-passwords-in-source-control/)
- [pass](http://www.passwordstore.org/) - Standard unix password manager (encrypt, then commit).
- [ansible-vault](https://docs.ansible.com/playbooks_vault.html) - Encrypted storage for ansible.
- [sops](https://github.com/mozilla/sops) - Encrypts files for git.

## Encrypted Storage
- \*[HN Thread](https://news.ycombinator.com/item?id=8264496) for blackbox, with various alternatives suggested
- [git-crypt](https://www.agwa.name/projects/git-crypt/) - git-crypt enables transparent encryption and decryption of files in a git repository
- \*[Blog post](http://dsernst.com/2015/06/09/git-crypt-is-git--encryption/) on git-crypt
- [transcrypt](https://github.com/elasticdog/transcrypt) - transparently encrypt files within a git repository
- [blackbox](https://github.com/StackExchange/blackbox) - use decryption keys per user, meaning that there is no single shared password

# Graphics
* Mermaidjs
* Tikz
* asymptote
- [PrintCSS](https://printcss.live/)
- [SnowFS](https://github.com/Snowtrack/SnowFS) - a fast, scalable version control file storage for graphic files. There is a [commercial offering](https://www.snowtrack.io/) as well.
- [kactus.io](https://kactus.io/) - Version control for designers (Sketch+Git for now)
- [pixelapse](https://www.pixelapse.com/) - Visual version control and collaboration workflow
- \*[Adobe Version Cue](http://sixrevisions.com/project-management/the-ultimate-guide-to-version-control-for-designers/) - Blog post explaining version control to designers

## Diagrams & Flowcharts
- [Web Sequence Diagrams](https://www.websequencediagrams.com/) - Generates imagess from your plain text descriptions. Has [an API](http://www.websequencediagrams.com/embedding.html) for plugin support, so you can embed easily.
- [Kanga Modelling](https://kangamodeling.codeplex.com/) - UML diagram generator in plain text. Written in .NET
- [yuml.me](http://yuml.me/) - Class UML diagrams, described in plain text, and easily embeddable.
- [Mermaid](https://mermaid-js.github.io/mermaid/#/) - Mermaid lets you create diagrams and visualizations using text and code.
- [Kroki](https://kroki.io/) - Kroki provides a unified API for all the diagram libraries including BlockDiag (BlockDiag, SeqDiag, ActDiag, NwDiag, PacketDiag, RackDiag), BPMN, Bytefield, C4 (with PlantUML), Ditaa, Erd, Excalidraw, GraphViz, Mermaid, Nomnoml, Pikchr, PlantUML, SvgBob, UMLet, Vega, Vega-Lite, WaveDrom... and more.
- [ditaa](http://ditaa.sourceforge.net/) - converts diagrams drawn using ascii art, into proper bitmap graphics.
- [erd](https://github.com/BurntSushi/erd) - takes a plain text description of entities, their attributes and the relationships between entities and produces a visual diagram modeling the description using GraphViz and Dot.
- [Svgbob Editor](https://ivanceras.github.io/svgbob-editor/) - Convert your ascii diagram scribbles into happy little SVG

## ASCII
- [Sparklines](https://en.wikipedia.org/wiki/Sparkline) are possible in plain-text (specifically these 8 characters: '▁▂▃▄▅▆▇█').
- [Tables-Generator](https://www.tablesgenerator.com/text_tables) lets you generate plain-text tables.
- [tree](https://gitlab.com/OldManProgrammer/unix-tree/-/issues/21): using --fromtabfile

# Media
- [lilypond](http://www.lilypond.org/features.html) - version control for sheet music. Think Latex for sheet music
- [tunemachine](https://github.com/jez/tunemachine) - Version control for spotify playlists.
- [Git Large File Storage](https://git-lfs.github.com/) - Replaces large fileswith text pointers inside Git, while storing the file contents on a remote server. Maintained by github
- [bup](https://github.com/bup/bup) - Very efficient backup system based on the git packfile format, providing fast incremental saves and global deduplication (among and within files, including virtual machine images)

# Database
Values, records, hierarchies (trees), types & more.

- \*Jeff Atwood's [blog post](http://blog.codinghorror.com/get-your-database-under-version-control/)
- [GNU Recutils](https://www.gnu.org/software/recutils/) - set of tools and libraries to access human-editable, plain text databases called recfiles. The data is stored as a sequence of records, each record containing an arbitrary number of named fields.
- CSV (Comma-Separated Values)** -- see [Awesome CSV](https://github.com/csvalues/awesome-csv)
- [YAML (YAML Ain't Markup Language)](http://yaml.org) -- see [Awesome YAML](https://github.com/datatxt/awseome-yaml)
- [JSON (JavaScript Object Notation)](http://json.org) -- see [Awesome JSON (What's Next?)](https://github.com/jsonii/awesome-json-next)
- [TOML (Tom's Obvious, Minimal Language)](https://github.com/toml-lang/toml) by Tom Preston-Werner et al
- [Markdown Configuration (.mdconf)](https://github.com/tj/mdconf) by TJ Holowaychuk et al

Schema:
- [flyway](https://flywaydb.org/) - Version control for your database.
- [MyBatis](http://www.mybatis.org/migrations/)
- [Liquibase](https://www.liquibase.org/) - Source Control for your database
- [Rumba RDBM](https://www.dbinvent.com/) - Database schema migration tool, plain-SQL, and declarative schema definition supported.

# Documents
- [Draft](https://draftin.com/) - Easy version control and collaboration for writers.
- [Penflip](https://www.penflip.com/) - GitHub for *collaborative* writers.
- [GitBook](https://www.gitbook.com/) - Book publishing platform based on git and markdown.
- [CriticMarkup](http://criticmarkup.com/) - a way for authors and editors to track changes to documents in plain text.

# Presentation
* [Patat](https://github.com/jaspervdj/patat): terminal presentation tool written in Haskell using Pandoc as parser.
* [tpp](https://github.com/cbbrowne/tpp)
* [tkn](https://github.com/fxn/tkn)
* [slider](https://github.com/dgoodlad/slider/tree/master)
* [posero](https://github.com/alfredodeza/posero.vim): vim plugin
* [vimdeck](https://github.com/tybenz/vimdeck)
* [mdp](https://github.com/visit1985/mdp)
* [vtmc](https://github.com/jclulow/vtmc)
* [tiptip](https://github.com/mcrio/tiptip)
* [lookatme](https://github.com/d0c-s4vage/lookatme)
* [slides](https://github.com/maaslalani/slides)
* [mume](https://github.com/shd101wyy/mume)
* [org-tree-slide](https://github.com/takaxp/org-tree-slide)
* [sent](https://tools.suckless.org/sent/)

## Finance
Tools that let you manage finances, but keep your books in plain-text.
- \*[plain text accounting](https://plaintextaccounting.org/) - umbrella site for the plain text accounting community.
- [Ledger](http://plaintextaccounting.org/quickref) - double-entry bookkeeping / accounting in (plain) text; follow your money
- [hledger](https://hledger.org/) - cross-platform accounting software for both power users and folks new to accounting.
- [beancount](http://furius.ca/beancount) - A double-entry bookkeeping computer language that lets you define financial transaction records in a text file, read them in memory, generate a variety of reports from them, and provides a web interface.
- [transity](https://github.com/feramhq/transity#list-of-features--todos) - A transaction-first plain-text account tool that uses YAML to store your transactions.
- ~~[plainbudget](https://galvez.github.io/plainbudget/) - Minimalist plaintext budgeting tool.~~

# Android
* See [Syncthing integrations](https://github.com/avidseeker/awesome-syncthing)
	+ [ics syncing](https://github.com/avidseeker/awesome-syncthing?tab=readme-ov-file#icsx5)
	+ [vCard syncing](https://github.com/bitfireAT/icsx5/discussions/361)

# Misc
- [Plain Text Project](https://plaintextproject.online) by Scott Nesbitt et al
- [Mundi Mark](https://mundimark.github.io) - all about markup & markdown
