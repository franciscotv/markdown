Intro to Markdown
=================
Version 0.2 - Dom 10 May 2020
by Francisco Treviño
<https://sites.google.com/site/zerofrancisco/>

Introduction
------------
Markdown is a text-to-HTML conversion tool for web writers. Markdown
allows you to write using an easy-to-read, easy-to-write plain text
format, then convert it to structurally valid XHTML (or HTML).

Full documentation of Markdown's syntax and configuration options is
available on the web: <http://daringfireball.net/projects/markdown/>.

**XHTML** __EXtensible HyperText Markup Language__, a transition from html to
xml, these files contain 3 parts:
- DOCTYPE: It is used to declare a DTD
- head: The head section is used to declare the title and other attributes.
- body: The body tag contains the content of web pages. It consists many tags.

Thus, "Markdown" is two things: a plain text markup syntax, and a
software tool, written in *Perl*, that converts the plain text markup
to *HTML*.

Configuration
-------------
By default, ***Markdown produces XHTML*** output for tags with empty elements.
E.g.:
>    <br>
>        Markdown can be configured to produce HTML-style tags; e.g.:
>    <br>

By default, Markdown produces XHTML output. To configure
Markdown to produce HTML 4 output, see "Configuration", below.


Insert hyper-links
------------------
[Please do visit my active site](https://nohaciaelsur.wordpress.com/)
[Or my archive](https://sites.google.com/site/zerofrancisco)


Task Lists
----------
- [x] Dive into the hype
- [x] Be aware of recomendations
- [ ] Reach out


Markdown Cheat Sheet
--------------------
1. ##### headings
2. ***bold***, *italics*
3. > block quotes
4. order list recursively go see step 1
5. unorder go see task Lists
6. `code!`
---
7. that is a horizontal line "---"
8. Link [title](https://www.example.com)
---
9. Image ![alt text](imgs/ricardo-mtz-man-black-red.JPG)


Bugs
----
To file bug reports or feature requests please send email to:
<zerofrancisco@gmail.com>.

The tux in the house ![Tux](imgs/tux.jpg "the tuxedo!")

Use [Duck Duck Go](https://duckduckgo.com)
