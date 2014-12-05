# Overview

Jsonfilter exposes a Go packge and a command line tool for filter string values found in JSON data.

# Usage

	jsonfilter "json to filter" | jsonfilter [help|/?]
	  -filter="": The filter(s) to apply to the strings contained in the JSON file.
	  -help=false: Show the help message.
	  -output="": The output file to write to.
	  -pretty=false: Print JSON result with indentation. (shorthand)
	  -pretty-print=false: Print JSON result with indentation.

Where `filter` can either be a command to use to filter all string values or a path to a JSON file.
See the [filter package](filter) for more details on filtering.

# Packages

**[filter](filter)** - Package filter implements a JSON filter that filters all string values found in JSON data.