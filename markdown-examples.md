# Markdown Examples #

See [Daring Fireball](https://daringfireball.net/projects/markdown/syntax) for further details on Markdown syntax.

---
Paragraphs are created by typing on a single line. This is a continuation of the paragraph. A double line break like this...

...breaks to a new paragraph. Like so.

---

To separate sections with a horizontal line you can use three minus signs in a row.

---
You can make STRONG or EMPHASIS (bold or italic) text by wrapping them in either one or two underscores or asterisks.

This is an _emphasized_ word. This is also an *emphasized* word.

This is a __strong__ word. This is also a **strong** word.

---
Headings can be specified like this.

Heading 1
=========
Heading 2
---------

Or alternatively, use the pound/hash sign to designate further headings.

# Heading 1
## Heading 2
### Heading 3

You can wrap headings if you choose.

#### Heading 4 ####
##### Heading 5 #####
###### Heading 6 ######

---

Like email, you can blockquote things if you want like this.

> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

>> A NESTED block quote looks like this.

> More block quotes like this. Pretty useful.

---

You can make lists like this.

* Item 1
* Item 2
* Item 3

or

- Item A
- Item B
- Item C

or

1. Item a
2. Item b
3. Item c

---

Finally, in order to create links to our documents, you can make automatic links like this.

<http://www.google.com>

Or custom text links like this.

[Visit Google](https://www.google.com)

---

For images, the format is very similar to links:
![Alt text](https://daringfireball.net/graphics/logos/)

---

Codeblocks can be written by indenting in with **tab**.

	<html>
		<p>Sample</p>
	</html>

Don't matter what kind of code is in there.

	var x = 1;
	var y = 2;
	var z = x + y;

Inline code can be represented by the back-tick mark. `var area = getAreaSquare(x,y);` that is inline with the rest of the text.

---

Since Markdown uses special characters, sometimes it can cause problems if you want to use special characters _literally_ within the text. You can use the backslash to escape special characters. That is, tell Markdown to not process it as part of the Markdown formatting markup. For example:

###### Heading 6 (shows as a heading)

\#\#\#\#\#\# Heading 6 will escape the markdown syntax and print the # marks.

Double asterisks will make a **word bold**. So we need to escape by using the literal backslash like this \*\*word bold\*\*.
