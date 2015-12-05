#PageLangPublish

##A ProcessWire module that allows publishing pages per language.

**_This module is still in alpha stage!_**

Adds buttons for publishing/unpublishing to the page tree.

Adds flags for published/unpublished status for each language
next to the page name in the page tree. The necessary fields
to hold the icons are added to the language pages at install
time.

While PW meanwhile has an "active" flag for non-default languages,
it doesn't make it easy to have a page visible in other languages
while it should be hidden in the default language. This module
adds that functionality as well.

If a page isn't available in the requested language, a redirect
to the next available parent will be performed.

##ToDo

- Tie module behavior into languages' active status
- Work a bit on nomenclature and merge all the features of production version (git repo isn't really up-to-date)
