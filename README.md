HW1 Your First Deployed Page
===

# homework_1
Code repository for Homework 1

You can use command line to fork the code or you can use the download option.

Description and Instructions at: https://docs.google.com/document/d/1lNsDFM8JuBw1dpldbnhcRoabhD7KLv0SumIbGj0mh6c/edit?usp=sharing

# Backblog:
1. The order of link to css is matter:<link rel="stylesheet" href="css/html5reset.css"> needs to be the frist.
2. Organization of page:

```HTML
<!DOCTYPE html>
<html>
<head>
</head>
  
<body>
<!-- The <header> element represents a container for introductory content or a set of navigational links.-->
<header>
    <nav>   <!-- Navigation bar on the top of page-->
        <ul>    <!-- In a nav element any list items should be unordered lists, not ordered lists.-->
            <li>...</li>
            <li>...</li>
        </ul>
    </nav>
</header>

<!-- Main content for this page-->
<main>
    <p>....</p>
    <img src="   " alt="   ">
</main>
    
<footer>
    <p> &copy；</p>
<footer>
    
</body>
</html>
```
3. 
```bash
FAIL!! There should be 3 "<p>":
    There is a incomplete <p> </p> pair, maybe forget "/" in "</p>"
```
4. There must be `alt` in <img >. And alt content should be meaningful.
