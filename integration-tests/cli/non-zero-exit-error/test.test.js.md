# Snapshot report for `integration-tests/cli/non-zero-exit-error/test.test.js`

The actual snapshot is saved in `test.test.js.snap`.

Generated by [AVA](https://avajs.dev).

## Invocation

    'elm-in-elm -m src/Main.elm'

## Stderr

    `Compiled in DEV mode. Follow the advice at https://elm-lang.org/0.19.1/optimize for better performance and smaller assets.␊
    ␊
    ␊
    ---------------------------␊
    -- COMPILER ERROR ---------␊
    ---------------------------␊
    The variable `y` is not visible from the module `Main`. Have you imported it? Does it exist?␊
    `

## Stdout

    `---------------------------␊
    -- STARTING THE COMPILER --␊
    ---------------------------␊
    Main.main: Value (Plus (Int 1) (Var { module_ = Nothing, name = "y" }))␊
    `