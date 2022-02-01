[![Build Status](https://travis-ci.org/krishnamiriyala/astrid.svg?branch=master)](https://travis-ci.org/krishnamiriyala/astrid) [![Go Report Card](https://goreportcard.com/badge/github.com/krishnamiriyala/astrid)](https://goreportcard.com/report/github.com/krishnamiriyala/astrid) [![codecov](https://codecov.io/gh/krishnamiriyala/astrid/branch/master/graph/badge.svg)](https://codecov.io/gh/krishnamiriyala/astrid)

# Astrid

Astrid is a collection of AST utilities for Go

# Matcher

NewMatcher returns a new *Matcher with the provided Uses and Defs from
types.Info

### Matcher.Match

Match determines whether two ast.Expr's are equivalent

# Invert

Invert returns the inverse of the provided expression.