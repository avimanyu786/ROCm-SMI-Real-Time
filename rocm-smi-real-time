#!/bin/bash

echo "Running 'rocm-smi' in real time..."
echo Press Q to exit.
sleep 4
while true; do
	clear
	rocm-smi
	sleep 0.5


# In the following line -t for timeout, -N for just 1 character
    read -t 0.25 -N 1 input
    if [[ $input = "q" ]] || [[ $input = "Q" ]]; then
# The following line is for the prompt to appear on a new line.
	clear
	rocm-smi
        echo "Exiting..."

        break 
    fi
done



