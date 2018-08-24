## About

Compare "members" of lists separated by newlines.

## Usage
	usage: memberCompare [-h] [--output OUTPUT] [--sort] [--hide-index] [--debug]
			     {inclusive,exclusive} ...

	positional arguments:
	  {inclusive,exclusive}
	    inclusive           Find common lines amongst files provided.
	    exclusive           Fine lines not in any of files provided.

	optional arguments:
	  -h, --help            show this help message and exit
	  --output OUTPUT, -o OUTPUT
				Output filename (absolute or relative).
	  --sort, -s            Sort the output.
	  --hide-index, -i      Hide the index on output.
	  --debug, -d           Enable debugging.
