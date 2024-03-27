### Compiling from Source(without Cabal and Stack)
`ghc --make <source>.hs`

### Keywords
* **Infix** notation is a notation commonly used in arithmetical and logical formulae and statements.


### Working with modules
```haskell
module Main where

import Functions

main :: IO ()
main = do
    print $ inRange 0 5 3
```
