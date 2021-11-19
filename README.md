# OperatorMatch (OPM)

Operator Match (OPM) is a simple token lexer that parses expressions.

A huge flaw with all of my past lexers has been that i've never really had a proper token matcher.

I'd always hard-code things to be exactly how I'd write them, and that caused a lot of issues.

But now I've built OPM, which relieves the token matching pain without any REGEX.

## Speed

This parser is fast, it's only about 30-40 lines of code and uses a simple natural technique to match tokens.

## Test

There's a test programming language found in SupScript directory.