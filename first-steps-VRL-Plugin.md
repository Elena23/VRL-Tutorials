CSS:        resources/css/vrl-documentation.css

# Your first steps before you'll start with the VRL - Plugin: #

## Contents ##

- [Install NetBeans] (your work-environment for java programming)
- [Creating a new user] at github.com and clone repository miho/VRL
- Install [Markdown] (to write your documentation)


## Install NetBeans  [Install NetBeans]
1. Download and instal Java (JDK) >=1.6, for example from: [http://www.oracle.com/technetwork/java/javase/downloads/index.html](http://www.oracle.com/technetwork/java/javase/downloads/index.html).
2. Download and install a suitable version (>=7.01) of NetBeans, for example from: [http://netbeans.org/downloads/](http://netbeans.org/downloads/).

[Recommended literature for java-programming](http://openbook.galileocomputing.de/javainsel/).

## Creating a new user at GitHub [Creating a new user]
GitHub is a web-based hosting service for software development projects that use the Git revision control system. [Documentation](http://git-scm.com/doc).

- Go to [GitHub](https://github.com/) and:
	Pick a username; Your email; Create a password, click on `Sign up for free`;

-  Find repository of VRL-Project. Enter miho / VRL in search mask on the top left of the page:
(see Figure [Repository of VRL-Project]); `Enter`:

![Repository of VRL-Project][]

[Repository of VRL-Project]: resources/img/Repository-VRL-Project.png width=981px

- Open NetBeans;
- Go to the top menu Team -> Git -> Clone (to clone repository);

![NetBeans-Git-Clone][]

[NetBeans-Git-Clone]: resources/img/NetBeans-Git-Clone.png width=981px

- Copy from GitHub the link https://github.com/miho/VRL.git and insert into your open window "Clone Repository"; also User und Password; click on `Next`;

![Clone-VRL-Repository][]

[Clone-VRL-Repository]: resources/img/Clone-VRL-Repository.png width=981px

- Then choose "master"; then `Next`; then `Finish`.
- Compile in NetBeans the Project VRL.
- Repeat it for VRL-Studio.

![Run VRL, VRL-Sudio][]

[Run VRL, VRL-Sudio]: resources/img/run-project.png width=981px

### Additional important functions of GitHub:###


- to load your changing version of the project in GitHub:
	right mouse-click on your project in NetBeans -> Git -> Commit...

![Commit Project][]

[Commit Project]: resources/img/chang-project-load.png width=980px

- to clone repository (fetch latest version):
	right mouse-click on your project in NetBeans -> Git -> Checkout -> Checkout Revision...

![Checkout Project][]

[Checkout Project]: resources/img/checkout-project.png width=981px



## Markdown  [Markdown] 
Markdown is a lightweight markup language, allowing people “to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML).

You need it in order to write your documentation.

1. Install Markdown, for example from: [hhttp://fletcherpenney.net/multimarkdown/download/](http://fletcherpenney.net/multimarkdown/download/).

2. Install txt-Editor, for example TextMate, from: [http://textmate.softonic.de/mac](http://textmate.softonic.de/mac). 
	For Info: 
	Table with Styles for VRL-Projects you can find in your VRL -> Source Packages -> eu.mihosoft.vrl.rootplugin.content.help -> help.zip -> resources.css -> vrl-documentation.css
3.  Write your documentation in txt-Editor and save it "name.md"
	Call the Terminal, run the MarkDown, compile your file "name.md and produce new file "name.html".
	 
	 Example: `gcscuser06-iMac:~ user$ multimarkdown -o name.html -t html name.md`
	

