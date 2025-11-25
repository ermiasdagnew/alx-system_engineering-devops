# 0x03 Shell, init files, variables and expansions
This folder contains solutions for the ALX 0x03 project. Each script is exactly 2 lines long and starts with the bash shebang.

Files:
- 0-alias: creates alias ls='rm *' when sourced
- 1-hello_you: prints 'hello <user>'
- 2-path: appends /action to PATH (export)
- 3-paths: prints the number of directories in PATH
- 4-global_variables: lists environment variables (printenv)
- 5-local_variables: lists local variables, env variables and functions (set)
- 6-create_local_variable: creates a local variable BEST=School
- 7-create_global_variable: creates a global variable BEST=School (export)
- 8-true_knowledge: prints 128 + $TRUEKNOWLEDGE
- 9-divide_and_rule: prints $((POWER / DIVIDE))
- 10-love_exponent_breath: prints $((BREATH ** LOVE))
- 11-binary_to_decimal: converts binary in $BINARY to decimal
- 12-combinations: prints all two-letter combinations except 'oo'
- 13-print_float: prints $NUM with 2 decimal places (printf)

Notes:
- Make scripts executable: chmod +x <file>
- For scripts that modify environment (aliases, PATH), source them: source ./0-alias
