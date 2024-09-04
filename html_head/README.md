Welcome to my README!!

This is a project focused on the head tag of an HTML page. We'll be learning about the basic uses and functions of the head tag and then using it in one of our upcoming HTML projects. Let's break it down!

The head tag in an HTML file is a container for metadata about the document. This metadata is not displayed on the webpage itself but provides essential information to browsers and search engines. Here are some common elements that can be included within the <head> tag:

<title>: Defines the title of the document, which appears in the browser's title bar or tab.
<meta>: Provides metadata such as the character set, author, and description of the document.
<link>: Links to external resources like stylesheets.
<style>: Contains internal CSS styles.
<script>: Includes or references JavaScript code.
<base>: Specifies a base URL for all relative URLs in the document.

Here's an example of how the <head> tag is used:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="An example of a head tag">
    <meta name="keywords" content="HTML, CSS, JavaScript">
    <meta name="author" content="John Doe">
    <title>Example Page</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js"></script>
</head>
<body>
    <h1>Welcome to the Example Page</h1>
    <p>This is a paragraph.</p>
</body>
</html>
