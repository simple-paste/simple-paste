Simple Paste - Your Clipboard Content Converter
===============================================

Simple Paste is a secure tool that converts your clipboard content into different formats. It's perfect for pasting content into Gmail, Notion, Google Docs, MS Word, and more. It allows pasting complex formatted text (e.g., from ChatGPT) into simple formats by collapsing into Markdown and then converting back to HTML!

Features
--------

-   Convert clipboard content into simple HTML and Markdown formats.
-   Paste content from ChatGPT and remove the background.
-   Convert Markdown to HTML.
-   Simplify HTML content.
-   Paste content into Gmail, Notion, Google Docs, MS Word, and more.

Usage
-----

1.  Copy the desired text or HTML content to your clipboard using `Ctrl+C` on Windows or `⌘+C` on Mac.
2.  Open Simple Paste in your browser.
3.  Paste the content into the provided window using `Ctrl+V` on Windows or `⌘+V` on Mac.
4.  Watch as your converted HTML appears!

Credits
-------

This application is powered by two fantastic open-source libraries:

-   [Turndown](https://github.com/mixmark-io/turndown): A robust HTML to Markdown converter written in JavaScript. It takes your HTML content and transforms it into Markdown, preserving the structure and format of the original content.
-   [Showdown](https://github.com/showdownjs/showdown): A JavaScript library that converts Markdown into HTML. It allows us to take the Markdown generated by Turndown and convert it back into HTML, preserving the formatting and structure of the original content.

This simple client-side application was inspired by [Paste to Markdown](https://euangoddard.github.io/clipboard2markdown/), a handy tool that converts clipboard content into Markdown. We've expanded on this idea to include conversion back to HTML and additional features for inspecting and manipulating clipboard content.

**Note:** All conversions happen in your browser, and no data is sent to the server.

Usage Instructions
------------------

1.  Clone or download the repository.
2.  Open the `index.html` file in a web browser.
3.  Follow the usage instructions provided above.

Dependencies
------------

-   [showdown](https://github.com/showdownjs/showdown): A JavaScript library for converting Markdown to HTML.
-   [turndown](https://github.com/mixmark-io/turndown): A JavaScript library for converting HTML to Markdown.

The necessary dependencies are included via CDN links in the HTML file.

License
-------

This project is licensed under the [MIT License](https://fiddle.jshell.net/_display/LICENSE).