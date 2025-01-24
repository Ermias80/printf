 @@ Depending of the content in the (), this functions use the simple printing or th
_printf is a custom function designed for formatted output on the screen. It allows for formatting the output in various ways. In this project, I developed a simplified version of the printf function, implementing both basic functionality and advanced format specifiers.

The function behavior depends on the content within the parentheses. It handles simple printing or utilizes specifiers to modify the output format.

For this project:

I completed tasks 0 and 1 from the mandatory section.
Additionally, I implemented all 14 advanced tasks.
The core function, _printf(), serves as the main entry point. It processes the input string and specifiers by passing them to a helper function called check_format. This helper function identifies the specifier type and delegates the task to a specific function responsible for printing the corresponding argument.

### Conversion specifiers
