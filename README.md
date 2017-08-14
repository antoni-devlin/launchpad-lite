# Launchpad Lite
Small ruby utility to quickly build a folder structure for (very) simple web development, and create an html skeleton.

**I've written the "lite" version first because I could do it quicker. I'll release the full version when I can figure out how to make it as customizable as I want it to be!**

<hr>

### What do?
Does what is says on the tin really. Run *ruby launchpad-lite* and the program will create the following folder structure:

**Template Project**

--**HTML**

----index.html

--**CSS**

----style.css

--**JS**

----script.js

--**Images**

<hr>

### File contents

- index.html contains an empty html template
- style.css & script.js are empty files

### TODO

- [x] DRY up code written during prototyping
- [x] Add editable html template file to use during generation
- [x] Make the program executable from any directory, and too any directory
- [x] Add HTML framework support
- [x] Add customization for CSS frameworks
