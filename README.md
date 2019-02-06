# Sublime Text - ManiaScript
:warning: Work in progress, may be changed and / or break without warning!


A basic (and inaccurate :smiley:) syntax definition and color scheme for ManiaScript (supporting embedded Manialink, and even ManiaScript inside it!)

## Setup
In Sublime Text 3:
- Go to `Preferences > Browse packages`
- Either
	- Clone this repository (recommanded for easy update) using `git clone https://github.com/undebutant/sublime-maniascript.git`
	- Create a new folder and put all files inside
- Restart Sublime Text


To use the color scheme, go to `Preferences > Color Scheme...` and select `MonokaiSpacegrayCustom` (do note that this syntax definition works well with Monokai color scheme too, but wasn't tested with others)

## Known issues
Vectors in ManiaScript (e.g. <1.,1.,1.>) are interpreted as invalid Manialink (XML parser used because of the `<`).

## Screenshot config (soon)
- Link to [package control installation](https://packagecontrol.io/installation) (not supported yet)
- Customized file icons using [FileIcons](https://packagecontrol.io/packages/FileIcons%20Mono)
- [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono) font

## Credits
- Color scheme customised from [pyoio/monokai-spacegray](https://github.com/pyoio/monokai-spacegray)

## Misc
Scopes name used by this syntax (useful for color scheme definition):
```
comment.line.double-slash
comment.block
constant.character.escape
constant.language
constant.numeric
constant.other

entity.name.enum
entity.name.function
entity.name.struct
entity.name.trait
entity.other.attribute-name

invalid.deprecated
invalid.illegal

keyword.control.conditional
keyword.control.flow
keyword.control.import
keyword.declaration.extends
keyword.operator.arithmetic
keyword.operator.assignment
keyword.operator.logical

punctuation.accessor.dot
punctuation.accessor.double-colon
punctuation.definition.comment
punctuation.definition.string.begin
punctuation.definition.string.end
punctuation.section.braces.begin
punctuation.section.braces.end
punctuation.section.brackets.begin
punctuation.section.brackets.end
punctuation.section.parens.begin
punctuation.section.parens.end
punctuation.section.mapping
punctuation.separator
punctuation.terminator

storage.type
string.quoted.double

variable.function
variable.parameter
```
