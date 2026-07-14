---
title: "Markdown Cheat Sheet"
menu: Markdown Help
kicker: "Keep this page as a reference"
blurb: "This is a practice copy of the site system. Nothing you do here touches the real site. Break it, fix it, play with it."
---

This whole page is written in a plain text file called `markdown-help.md`. The menu bar, the design, the footer — none of that is in this file. It all comes from the template, automatically.

The lines between the two `---` marks at the top of the file set the page title, which menu item is highlighted, the small grey kicker line, and the introduction paragraph. Everything below the second `---` is just the words on the page.

## This is a heading

You make a heading by starting a line with two hash marks and a space. A paragraph is just a paragraph — type it and leave a blank line before the next one.

Bold text is two asterisks around the words, **like this**. A link is square brackets around the words, then the address in round brackets, [like this](https://www.boyupbrook.wa.gov.au).

> A quote from a Shire document goes in a blockquote. Start the line with a greater-than sign and a space. It comes out looking like this.

Source: Shire of Boyup Brook, Ordinary Council Meeting Minutes, 30 April 2026. [Link to document](https://www.boyupbrook.wa.gov.au)
{: .src}

That small grey source line above is a normal paragraph with `{: .src}` on the line directly underneath it — that tells the template to style it as a source citation.

## Try these exercises

Open `sample-page.md` and change some wording, then re-upload it. Open `_data/nav.yml` and add or delete a menu item. Copy `bare-minimum.md`, rename the copy, change its title, add it to the menu — you have just made a new page. The HOW-TO-GUIDE.txt file walks through each of these step by step.
