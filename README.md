# berkshirehathaway

An exercise to clean up legacy code.

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

## Steps taken to update.

1. Change DOCTYPE to support HTML5.
2. Add lang to html tag.
3. Remove deprecated meta tags.
4. Remove deprecated body attributes.
5. Add viewport meta tag.
6. Remove table and table rows and replace with divs.
7. From the bottom up, remove all font tags.
8. Prettify code.
