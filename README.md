# berkshirehathaway

An exercise to clean up the legacy code of a famous website homepage.

## Initial observed errors/issues.

- Google Tag Manager/Google Analytics tag is in the incorrect place.
- Deprecated HTML 4.0 Transitional.
- Deprecated body attributes.
- No viewport meta tag.
- Charset is unicode, not UTF-8.
- Incorrect nesting order of tags.
- No semantic nesting of page structure.
- Hacks in coding leads to issues when trying to modernize.
- All links are purple.
- Non-breaking spaces.
- Use of bold tags.
- Use of font tags.
- Spurious tags that do nothing.
- Incorrectly nested closing font tags.
- Break tags.
- Spaces between tags.
- Lots of bold tags.

## Steps taken to update.

1. Change DOCTYPE to support HTML5.
2. Add lang to html tag.
3. Remove deprecated meta tags.
4. Remove deprecated body attributes.
5. Add viewport meta tag.
6. Remove table and table rows and replace with divs.
7. From the bottom up, remove all font tags.
8. Prettify code.

## Converting tables to divs.

1. Change address.
2. Add a header and footer.
3. Add a main section.
4. Add header tags.
5. Replace legacy break tags.
6. Replace bold tags.
7. Address font sizings.

## TO DO

- Fix table.
- Fix address style.
- Fix spacings.

## References.

- https://developer.mozilla.org/en-US/docs/Web/HTML/Element/address
