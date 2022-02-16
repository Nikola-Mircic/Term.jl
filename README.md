# TODO
- [x] get plain text for Measure
  - [x] remove markup
  - [x] remove ansi
  
- [x] regex markup extraction
  - [x] deal with no or minmal closings
  - [x] test

- [x] color: test detection
  - [x] print all named colors
  - [x] test
  - [x] hex -> rgb

- [x] markup -> ansi substitution, modular
  - [x] detect style
  - [x] inject style
    - [x] all colors
  - [ ] fix bug with nested tags
  
- [x] segment
  - [x] base
  - [x] from string + style
  - [x] from string + markup

- [x] tests
  - [x] check that Measure is correct for all types of segment, segments, renderable...
  - [x] also check results make sense when concatenating them

## Roadmap
- [ ] macros for styling a string
- [x] box
- [x] panel
  - [ ] panel subtitle
- [ ] inspect
- [ ] latex->unicode parsing (https://github.com/phfaist/pylatexenc)
- [ ] markdown parsing
- [ ] Line divider thingy

## BUGS
- [ ] nested tags, outer's color/bg not correctly restored
- [ ] style: if a tag is at the beginning of a multiline string, it should be repeated on each line?
- [ ] panel: style's mode applies to title too.