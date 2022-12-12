#!/bin/bash

# This Bash script automates the process of running several tools to enumerate subdomains of a specified domain.
# This is something I personally use for my own personal recon.
# The tools used are:
# - subfinder
# - crtsh
# - githubsubs
# - assetfinder
# - amass
# - asnmap

# Usage
# To run the script, use the following command:
# ./script.sh [domain]

# You can also use the -h flag to display a help message with usage instructions:
# ./script.sh -h

# If the domain is not provided as an argument, the script will prompt the user to enter it.
# The script will then create the subdomains folder if it does not exist, and run the tools with their flags and the entered domain.
# The output of each tool will be saved to the subdomains folder.

# Requirements
# Bash shell
# The following tools must be installed and available in the PATH:
# - subfinder
# - crtsh
# - githubsubs
# - assetfinder
# - amass
# - asnmap

# License
# This script is licensed under the MIT License. See the LICENSE file for details.
