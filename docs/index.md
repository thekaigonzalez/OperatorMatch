<!--
 Copyright (C) 2021 Kai D. Gonzalez
 
 This program is free software: you can redistribute it and/or modify
 it under the terms of the GNU Affero General Public License as
 published by the Free Software Foundation, either version 3 of the
 License, or (at your option) any later version.
 
 This program is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty of
 MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 GNU Affero General Public License for more details.
 
 You should have received a copy of the GNU Affero General Public License
 along with this program.  If not, see <http://www.gnu.org/licenses/>.
-->

# Docs / FAQ

## Why Not REGEX?

Two reasons

1. I don't know how to use regex.

2. regex is slower compared to a causal lexer.

## How do I implement this into my programming language?

```js

const OPM = require("operatormatch")

const match_paren = (string) => {
    return OPM.match(string, '(', ')')
}

match_paren("(see (me))")

```