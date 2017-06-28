# Idcomments Tool

A fork of Henrik Levkowetz's [idcomments](https://tools.ietf.org/tools/idcomments/) tool.

## Usage

```
Usage:  idcomments [OPTIONS]... REVIEW

Extract comments from an internet-draft with interspersed review
comments.  Comments have to follow the text to which they apply
without intervening blank lines.  The first comment line has to
start with a comment tag, and following comment lines has to be
tab-indented.  A comment ends with the first blank line.  The
comment tag is by default "COMMENT:", but the tag word is
configurable with the -t switch.

Options:
	-h, --help	 Show this help, then exit
	-t, --tag	 Use the provided tag string instead of 'COMMENT'
	-V, --version	 Show program version, then exit

```

## Dependency

This command-line tool depends on [rfcdiff](https://tools.ietf.org/tools/rfcdiff/). A fork of `rfcdiff` cli version can be retrieved at [here](https://github.com/fno2010/rfcdiff).
