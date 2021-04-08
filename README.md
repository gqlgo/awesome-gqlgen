# Awesome gqlgen

A curated list of awesome GraphQL frameworks, libraries and software using gqlgen library.


## Command line

### Generator

- [99designs/gqlgen](https://github.com/99designs/gqlgen) - Generate go GraphQL server from GrahpQL scheme
- [Yamashou/gqlgenc](https://github.com/Yamashou/gqlgenc) - Generate go GraphQL client from GraphQL query
- [Code-Hex/gqldoc](https://github.com/Code-Hex/gqldoc) - Generate Markdown GraphQL documents from GraphQL schema

###  Formatter

- [gqlgo/gqlfmt](https://github.com/gqlgo/gqlfmt) - Format GraphQL file

### Linter

- [gqlgo/lackid](https://github.com/gqlgo/lackid) - Detect lack of id in GrahpQL query


## Library

### GraphQL basis

- [vektah/gqlparser](https://github.com/vektah/gqlparser) - GrahpQL schema and query parser
- [Yamashou/gqlgenc/introspection](https://github.com/Yamashou/gqlgenc/tree/master/introspection) - GraphQL instrospection query parser
- [Yamashou/gqlgenc/graphqljson](https://github.com/Yamashou/gqlgenc/tree/master/graphqljson) - GrahpQL JSON encoder and decoder

### Static analysis
- [gqlgo/gqlanaylsis](https://github.com/gqlgo/gqlanalysis) - Static analysis go library for GraphQL, inspired by [go/analysis](https://pkg.go.dev/golang.org/x/tools/go/analysis)

### gqlgen plugin
- [99designs/gqlgen/plugin/modelgen](https://github.com/99designs/gqlgen/tree/master/plugin/modelgen) - Generate go model type from GraphQL schema
- [99designs/gqlgen/plugin/resolvergen](https://github.com/99designs/gqlgen/tree/master/plugin/resolvergen) - Generate go resolver from GraphQL schema
- [99designs/gqlgen/plugin/federation](https://github.com/99designs/gqlgen/tree/master/plugin/federation) - Generate go Apollo Federation resolver from GraphQL schema
- [Yamashou/gqlgenc/clientgev2](https://github.com/Yamashou/gqlgenc/tree/master/clientgenv2) - Generate go client from GraphQL query

