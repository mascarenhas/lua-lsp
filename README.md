# Typed Lua Language Server

This is a [language server](http://langserver.org/) for [Typed Lua](https://github.com/andremm/typedlua).

## Requirements

 * [Typed Lua](https://github.com/andremm/typedlua)
 * [luv](https://github.com/luvit/luv)
 * [Lua CJSON](https://www.kyne.com.au/~mark/software/lua-cjson.php)

## Running

By default `lua-lsp` will serve request on the standard input/output streams.
Alternatively a port can be specified with the `-p` command line argument.

## Status

The following works

 [x] Linting as you type (syntax and type errors)
 [x] Identifier renames
 [x] Goto definition of identifiers (*not* functions or table indicies)
 [x] Find all references of identifiers (*not* functions or table indicies)
 [x] Hover identifiers

Not yet implemented

 [ ] Code completion
 [ ] Signature help
 [ ] Code formatting
 [ ] Symbol information
 [ ] Incremental synchronization
 [ ] Multiple file support
 [ ] Cancelation support (asynchroneous non-blocking operation)
 ...

