# About PowerMTML Completions

PowerMTML Completions is autocompletions of PowerCMS for Sublime Text 2.
You can use suggestions of "Movable Type Template Tags" after installing [MTML Completions ](https://github.com/bit-part/MTML-ST2) .

## Instalation

### With Package Control: Add Repository

```
Package Control: Add Repository
```

Input URL ‘https://github.com/bit-part/PowerMTML-ST2’

```
Package Control: Install Package
```

Select ‘PowerMTML Completions’

### With Git

Please clone into your Sublime Text 2 package directory.

```
cd /path/to/your/Sublime Text 2/Packages
git clone https://github.com/bit-part/PowerMTML-ST2
```
## Preference

You can change the format of Template Tags.

### mtml_prefix

  no setting => <mt:EntryTitle />
  "mtml_prefix": "MT:" => <MT:EntryTitle />
  "mtml_prefix": "MT"  => <MTEntryTitle />

### mtml_function_tag_type

  no setting => <mt:EntryTitle />
  "mtml_function_tag_type": "dollar" => <$mt:EntryTitle$>
  "mtml_function_tag_type": "none" => <mt:EntryTitle>

## Usage

You can use this feature when you input "<" in html or php file. When you set extension as ".mtml" or ".tmpl" , please change Syntax as html.

For modifier, you run "Edit > Show Completions [cntrol + space]" when you input a space and a few calactors.

## Example

![Example](http://bit-part.github.com/data/img_powermtml-st2.png)

* [B]：Block Tag
* [F]：Function Tag
* [C]：Conditional Tag

---

_Movable Type is a registered trademark of Six Apart, the Ltd.._

_PowerCMS is a registered trademark of Alfasado Inc.._
