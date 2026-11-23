# Kaze Syntax Highlighting

Official TextMate grammar and language configuration for the **Kaze** programming language (`.kaze`), powering syntax highlighting for editors (VS Code, Sublime Text, TextMate, Atom) and GitHub Linguist.

## Overview

- **Language:** Kaze
- **Scope Name:** `source.kaze`
- **File Extensions:** `.kaze`
- **Specification:** ISO C99 lowering, zero-GC bump arena, physical units, sentence actions, and capability envelopes.

## Scopes Provided

- `keyword.control.kaze` (`action`, `routine`, `check`, `filter`, `when`, `every`, `try`, `otherwise`, `return`, `let`, `set`, `if`, `while`, `bounded`)
- `storage.type.unit.kaze` (`meters`, `m/s`, `ms`, `degrees`, `percent`, `Celsius`, `Kelvin`, `mbar`, `hz`, `volt`)
- `storage.type.primitive.kaze` (`u8`, `i32`, `f32`, `bool`, `void`, `text`, `num`, `tensor`)
- `support.class.capability.kaze` (`drone`, `rover`, `sensor`, `device`, `memory`, `policy`, `log`, `alert`)
- `support.function.capability.kaze` (`pulse`, `turn`, `arm`, `takeoff`, `fly`, `goto`, `land`, `rtl`, `set_relay`, `analog_read`)
- `variable.other.telemetry.kaze` (`battery`, `altitude`, `heading`, `speed`, `position`, `temperature`, `humidity`)
- `keyword.operator.kaze` (`+`, `-`, `*`, `/`, `%`, `==`, `!=`, `<=`, `>=`)

## License

MIT License. Copyright (c) 2026 Sofuu Runtime.
