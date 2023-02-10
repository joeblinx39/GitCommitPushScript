#!/bin/bash

filename=$1

if [ ${filename: -2} == ".c" ]; then
	  gcc -o ${filename%.c} $filename
  else
	    echo "Error: Not a C source file. Aborting..."
	      exit 1
fi
