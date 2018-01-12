DevOps tools
============

A curated list of development and operational tools for Unix-like operating
systems.

## Databases

* **[squirrelsql](http://squirrel-sql.sourceforge.net/)**: Multi-database
  graphical SQL client. Supports anything JDBC supports (MySQL, Postgres,
  MSSQL, etc).
* **[dbeaver](https://github.com/serge-rider/dbeaver)**: Free universal
  database manager and SQL client.
* **[apache directory studio](http://directory.apache.org/studio/)**: A
  complete GUI LDAP management tool.


## Data filtering and transformations

* **[xmlstarlet](http://xmlstar.sourceforge.net/)**: Commandline tools to work
  with XML. Validate (DTD, XSD), XPath, XSLT, modify and visualize XML
  documents.
* **[xlstproc](http://xmlsoft.org/XSLT/xsltproc.html)**: Process XSLT on the
  commandline.
* **[xmllint](http://xmlsoft.org/xmllint.html)**: parses one or more XML
  files, specified on the command line as xmlfile. It prints various types of
  output, depending upon the options selected. It is useful for detecting
  errors both in XML code and in the XML parser itself.
* **[jq](https://stedolan.github.io/jq/)**: a lightweight and flexible
  command-line JSON processor.
* **[meld](http://meldmerge.org/)**: a visual diff and merge tool targeted at
  developers. Meld helps you compare files, directories, and version
  controlled projects. It provides two- and three-way comparison of both files
  and directories, and has support for many popular version control systems.
* **[expect](https://linux.die.net/man/1/expect)**: Systematically interact
  with programs that can't be scripted but require human interaction.
* **[fop](https://xmlgraphics.apache.org/fop/)**: XSL-driven documentation
  generator. Basically takes XML and XSL as input and generates PDF, PS, etc.


## Desktop

* **[tilix](https://github.com/gnunn1/tilix)**: A tiling terminal emulator for
  Linux.
* **[zim](http://zim-wiki.org/)**: Powerful desktop wiki / note taking
  application.

## Dev stubbing

* **[fakesmtp](http://nilhcem.com/FakeSMTP/index.html)**: a Fake SMTP Server
  with GUI for testing emails in applications easily.
* **[mailslurper](http://mailslurper.com/)**: a Fake SMTP server with a web
  interface for testing emails without actually sending them. Simple
  single-package installation.
* **[tcconfig](https://github.com/thombashi/tcconfig/blob/master/README.rst)**:
  Easy to set up traffic control of network bandwidth/latency/packet
  loss/packet-corruption to a network interface.

## Development aids

* **[soapui](https://www.soapui.org/)**: A SOAP and REST testing tool.
* **[skajla](http://skajla.blogspot.nl/2010/05/jmx-command-line-client.html)**:
  Command-line [JMX](https://en.wikipedia.org/wiki/Java_Management_Extensions)
  client.
* **[virtualbox](https://www.virtualbox.org/)**: Powerful x86 and
  AMD64/Intel64 virtualization lets you run full-fledged Windows, Linux,
  Solaris and BSD Virtual machines on your computer.
* **[vagrant](https://www.vagrantup.com/)**: Quickly bring up Virtual Machines
  for development and testing using a single declarative configuration file.
* **[lxdock](http://lxdock.readthedocs.io/)**: Quickly bring up lightweight
  containers for development and testing.

## Documentation

* **[pandoc](https://pandoc.org/)**: convert files from one markup format into
  another. Supports a large number of formats.
* **[asciidoc](http://www.methods.co.nz/asciidoc/)**: a text document format
  for writing notes, documentation, articles, books, ebooks, slideshows, web
  pages, man pages and blogs. AsciiDoc files can be translated to many formats
  including HTML, PDF, EPUB, man page.
* **[mkdocs](http://www.mkdocs.org/)**: a fast, simple and downright gorgeous
  static site generator that's geared towards building project documentation.
  Documentation source files are written in Markdown, and configured with a
  single YAML configuration file.
* **[yed](https://www.yworks.com/products/yed)**: cross-platform diagram
  editor.
* **[plantuml](http://plantuml.com/)**: Generate UML diagrams from a simple
  text-based description.
* **[graphviz](http://www.graphviz.org/)**: Use a simple text language to
  generate diagrams of abstract graphs and networks.


## Filesystems

* **[mhddfs](https://romanrm.net/mhddfs)**: join several filesystems together to
  form a single larger one.
* **[sshfs](https://github.com/libfuse/sshfs)**: allows you to mount a remote
  filesystem using SFTP. Most SSH servers support and enable this SFTP access
  by default, so SSHFS is very simple to use - there's nothing to do on the
  server-side.
* **[squashfs](http://squashfs.sourceforge.net/)**: Create and mount compressed
  filesystem images.
* **[xdiskusage](http://xdiskusage.sourceforge.net/)**: Visually represent
  disk usage in and below a directory.
* **[rsync](https://rsync.samba.org/)**: Provides fast, reliable, configurable
  incremental file transfer on local disk or over the network. Archive,
  mirror, etc.


## Linting

* **[httpolice](https://github.com/vfaronov/httpolice)**: a validator for HTTP
  requests and responses. It can spot bad header syntax, inappropriate status
  codes, and other interoperability problems in your HTTP server or client.
* **[shellcheck](http://www.shellcheck.net/)**: a tool that gives warnings and
  suggestions for bash/sh shell scripts.


## Networking

* **[mtr](https://www.bitwizard.nl/mtr/)**: My TraceRoute. combines the
  functionality of the 'traceroute' and 'ping' programs in a single network
  diagnostic tool.
* **[lft](https://linux.die.net/man/8/lft)**: display the route packets take
  to a network host/socket using one of several layer-4 protocols and
  methods. Basically traceroute for TCP, UDP and ICMP.
* **[netcat](https://en.wikipedia.org/wiki/Netcat)**: a computer networking
  utility for reading from and writing to network connections using TCP or
  UDP. Replacement for telnet. Can also act as a server.
* **[sshuttle](https://github.com/apenwarr/sshuttle)**: Sshutle is VPN over
  SSH without requiring a remote VPN server or admin rights. Instead, it
  builds up an ssh session and than locally forwards traffic over it by
  creating local PREROUTING firewall rules.
* **[stunnel](https://www.stunnel.org/)**: a proxy designed to add TLS
  encryption functionality to existing clients and servers without any changes
  in the programs' code.
* **[tcptraceroute](https://linux.die.net/man/1/tcptraceroute)**: A traceroute
  implementation using TCP packets
* **[wavemon](https://github.com/uoaerg/wavemon)**: an ncurses-based
  monitoring application for wireless network devices.
* **[rinetd](https://www.boutell.com/rinetd/)**: Redirects TCP connections
  from one IP address and port to another. 
* **[dig](https://mediatemple.net/community/products/dv/204644130/understanding-the-dig-command)**:
  The multitool for DNS enquiries.
* **[ipcalc](http://jodies.de/ipcalc)**: IP network calculator. Available as
  online tool as well as a downloadable package. (Ubuntu users: `apt install
  ipcalc`).
* **[netalyzr](http://netalyzr.icsi.berkeley.edu/)**: Commandline tool that
  runs various network related tests and generates a report for potential
  problems. (careful: sends the results to Berkeley for research purposes).
* **[mitmproxy](https://mitmproxy.org/)**: An interactive console program that
  allows HTTP traffic flows to be intercepted, inspected, modified and
  replayed.
* **[iftop](http://www.ex-parrot.com/pdw/iftop/)**: iftop does for network
  usage what top(1) does for CPU usage. It listens to network traffic on a
  named interface and displays a table of current bandwidth usage by pairs of
  hosts. Handy for answering the question "why is our ADSL link so slow?".
* **[iptraf](http://iptraf.seul.org/)**: IPTraf is a console-based network
  statistics utility for Linux. It gathers a variety of figures such as TCP
  connection packet and byte counts, interface statistics and activity
  indicators, TCP/UDP traffic breakdowns, and LAN station packet and byte
  counts.


## Miscellaneous

* **[lnav](http://lnav.org/)**: An advanced log file viewer for the
  small-scale. Watch and analyze your log files from a terminal. No server. No
  setup. Still featureful.

## Monitoring

* **[monit](https://mmonit.com/monit/)**: a small utility for managing and
  monitoring Unix systems. Monit conducts automatic maintenance and repair and
  can execute meaningful causal actions in error situations.
* **[iotop](http://guichaz.free.fr/iotop/)**: Show disk and swap I/O per
  process.
* **[logtail](https://www.fourmilab.ch/webtools/logtail/)**: Watch multiple
  log files on multiple machines.


## Security

* **[fail2ban](https://www.fail2ban.org/wiki/index.php/Main_Page)**: Fail2ban
  scans log files and bans IPs that show malicious signs. Easily protects your
  SSH ports against attacks.
* **[ferm](http://ferm.foo-projects.org/)**:  a tool to maintain complex
  firewalls, without having the trouble to rewrite the complex rules over and
  over again. 
* **[testssl](https://testssl.sh/)**: checks a server's service on any port
  for the support of TLS/SSL ciphers, protocols as well as recent
  cryptographic flaws and more. 
* **[pwgen](https://github.com/jbernard/pwgen)**: Generate pronouncable and
  easy to type passwords.
* **[keystore explorer](http://keystore-explorer.org/)**: Java GUI for
  managing Java Key stores (SSL certificate databases). Also lets you convert
  all kinds of certificate formats.
* **[qualys ssl server test](https://www.ssllabs.com/ssltest/)**: Online tool
  for deep analysis of the configuration of any SSL web server on the public
  Internet.


## Source control

* **[tig](https://github.com/jonas/tig)**: an ncurses-based text-mode
  interface for git.
* **[git cola](https://git-cola.github.io/)**: a sleek and powerful graphical
  user interface for Git.
* **[multi-git-status](https://github.com/fboender/multi-git-status)**: Show
  uncommitted, untracked and unpushed changes for multiple Git repos.
