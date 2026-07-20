# JavaScript Keywords — Complete Reference

> In JavaScript, a **keyword** is a reserved word that has a special meaning to the language. You cannot use keywords as variable names, function names, or identifiers.

---

## Comparison Table

| Category | Keywords | What they do |
|---|---|---|
| **Variable Declaration** | `var`, `let`, `const` | Declare variables — `var` is function-scoped, `let` is block-scoped, `const` is block-scoped + read-only |
| **Control Flow** | `if`, `else`, `switch`, `case`, `break`, `default` | Conditional branching — `if/else` for boolean checks, `switch/case` for multi-way branching |
| **Loops** | `for`, `while`, `do`, `continue`, `break` | Repetition — `for` (counter-based), `while` (condition-first), `do...while` (runs at least once) |
| **Loop Helpers** | `for...in`, `for...of` | `for...in` iterates over enumerable property **keys** (strings), `for...of` iterates over iterable **values** |
| **Functions** | `function`, `return`, `=>` (arrow), `async`, `await`, `yield`, `*` (generator) | Define and control functions — `function` declares, `return` exits with a value, `async/await` for promises, `yield` for generators |
| **Object-Oriented** | `class`, `extends`, `super`, `new`, `this`, `static`, `get`, `set` | OOP — `class` defines, `extends` inherits, `super` calls parent, `new` instantiates, `this` refers to current instance |
| **Error Handling** | `try`, `catch`, `finally`, `throw` | Exception handling — `try` tests code, `catch` handles errors, `finally` always runs, `throw` raises an error |
| **Boolean & Null** | `true`, `false`, `null`, `undefined`, `NaN` | Primitive values — booleans, intentional absence (`null`), uninitialized (`undefined`), not-a-number (`NaN`) |
| **Type Checking** | `typeof`, `instanceof`, `delete`, `void` | Operators used as keywords — `typeof` returns type string, `instanceof` checks prototype chain, `delete` removes properties, `void` evaluates expression and returns `undefined` |
| **Module System** | `import`, `export`, `default`, `from`, `as` | ES Modules — `import`/`export` to share code between files |
| **Debugging** | `debugger` | Pauses execution if dev tools are open |
| **Object Literals** | `in`, `instanceof` | `in` checks if a property exists in an object |

---

## Full Alphabetical List of All JS Keywords

```
await       break       case        catch       class       const
continue    debugger    default     delete      do          else
export      extends     finally     for         function    if
import      in          instanceof  let         new         return
super       switch      this        throw       try         typeof
var         void        while       with       yield

--- Also reserved (strict mode) ---
implements  interface   package     private     protected   public
static      arguments   NaN         Infinity    undefined   null
true        false       async       await       of          get
set         target      meta

--- Future reserved (older specs) ---
enum        abstract    boolean     byte        char        double
final       float       goto        int         long        native
short       synchronized transient   volatile
```

---

## Key Takeaway

> **Keywords are the language's built-in vocabulary. You can't use them as variable names, and each one triggers a specific behavior in the JS engine.**
