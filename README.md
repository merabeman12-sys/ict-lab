1. Assembly Reflections

What did you notice about registers and instructions?  

Everything in Assembly is very low-level. Instead of variables named as registers  data is stored as  AX BX CX DX EAX etc. and Instructions are very specific (like MOV ADD SUB MUL, etc.) and there are not many registers so you must manage them carefully. This makes the code less abstract but Hardware control increases.  

How is coding in Assembly different from Python?  

Instead of your high-level, abstract, and human-readable commands where Python takes care of the low-level details, in Assembly you are required to manage every operation, including the data m[11:19 pm, 29/09/2025] Ammaan SE:  Feature            | Assembly Example       | Python Example   | Notes |
|--------------------|------------------------|------------------|-------|
| Variable storage   | MOV AX, 5              | x = 5            | Assembly uses registers, Python uses named variables. |
| Printing output    | INT 21h                | print("Hello")   | Assembly needs interrupts, Python has built-in print. |
| Arithmetic         | ADD AX, BX             | x + y            | Assembly is step-by-step, Python is simpler. |
| Looping            | LOOP label             | for i in range(5): | Assembly needs jumps, Python has built-in loops. |
| Functions          | CALL myProc            | def myFu2. Reflexions in Python Why is Python faster or easier to use when creating the same project? Python is simpler because it manages variable storage, memory, and function calls automatically. Its straightforward syntax and built-in libraries allow you to concentrate on problem-solving rather than hardware management. As a result, there are fewer lines of code and debugging is much easier. Which Python attributes—variables, functions, and loops—support abstraction? Python lets you write reusable functions (def myFunc():), define variables directly with names (x = 10), and repeat tasks using loops (for and while). In contrast to Assembly, where everything must be done by hand, these abstractions greatly reduce the length and simplify the code.nc():    | Assembly uses stack/procedures, Python has easy functions. |
[11:19 pm, 29/09/2025] ovement, and System Calls step-by-step. Assembly is harder, more detailed, and closer to the hardware. Python, on the other hand, is more straightforward, and faster for development.
