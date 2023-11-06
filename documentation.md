# MarkDown for Didi

## mdd

```
markdown tools for my blog:
	target: mdd subcommand [one of 'article' 'new']
Usage :
	mdd <target>
```

## mdd new

```
mdd sub command help
	
mdd article command:
	title: article title
	--folder|--directory|--dir <folder>: article folder name
	-c, --categories|--cat|--parent <categories>: article parent categories, repeatable
	-t, --tags|--tag <tags>: article tags, repeatable
	-g, --series|--group <series>: article belongs to this series
	-d, --date|--publication|--publish-at <date>: publication date meta
	-s, --summary|--description|--desc <summary>: summary meta
	--template|--tpl <template>: template file to use
	--headings|--part|--h2 <headings>: add headings to your file, repeatable
	--headings-level|--hl <headings-level>: heading level [default: ' 2 ']
	--filename <filename>: markdown file name [default: ' index.md ']
	--draft|--no-draft: is it a draft, on by default (use --no-draft to turn it off)
		no-aliases: --publish,
	--force|--no-force: erase if exists
	--is-category|--no-is-category: this is a category, using _index.md as filename
		aliases: --is-cat,
	--meta[-<key>] <meta-key-value>: nested, add any meta you want
Usage :
	/bin/new <title> [--folder <value>] [--categories <value>] [--tags <value>] [--series <value>] [--date <value>] [--summary <value>] [--template <value>] [--headings <value>] [--headings-level <value>] [--filename <value>] [--[no-]draft] [--[no-]force] [--[no-]is-category] [--[no-]meta]
```

## bin

### bin/new

```
mdd article command:
	title: article title
	--folder|--directory|--dir <folder>: article folder name
	-c, --categories|--cat|--parent <categories>: article parent categories, repeatable
	-t, --tags|--tag <tags>: article tags, repeatable
	-g, --series|--group <series>: article belongs to this series
	-d, --date|--publication|--publish-at <date>: publication date meta
	-s, --summary|--description|--desc <summary>: summary meta
	--template|--tpl <template>: template file to use
	--headings|--part|--h2 <headings>: add headings to your file, repeatable
	--headings-level|--hl <headings-level>: heading level [default: ' 2 ']
	--filename <filename>: markdown file name [default: ' index.md ']
	--draft|--no-draft: is it a draft, on by default (use --no-draft to turn it off)
		no-aliases: --publish,
	--force|--no-force: erase if exists
	--is-category|--no-is-category: this is a category, using _index.md as filename
		aliases: --is-cat,
	--meta[-<key>] <meta-key-value>: nested, add any meta you want
Usage :
	bin/new <title> [--folder <value>] [--categories <value>] [--tags <value>] [--series <value>] [--date <value>] [--summary <value>] [--template <value>] [--headings <value>] [--headings-level <value>] [--filename <value>] [--[no-]draft] [--[no-]force] [--[no-]is-category] [--[no-]meta]
```
