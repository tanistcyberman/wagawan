#!/bin/bash  
mkdir first; for i in {0..15}; do echo "first" | tr 'a-z' 'zyxwvutsrqpomlkjihgfedcba' > first/wagwan-$i.txt; done
