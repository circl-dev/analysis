# OpenAPI initiative analysis

[![Build Status](https://travis-ci.org/protodev-site/analysis.svg?branch=master)](https://travis-ci.org/protodev-site/analysis)
[![Build status](https://ci.appveyor.com/api/projects/status/x377t5o9ennm847o/branch/master?svg=true)](https://ci.appveyor.com/project/casualjim/protodev-site/analysis/branch/master)
[![codecov](https://codecov.io/gh/protodev-site/analysis/branch/master/graph/badge.svg)](https://codecov.io/gh/protodev-site/analysis)
[![Slack Status](https://slackin.goswagger.io/badge.svg)](https://slackin.goswagger.io)
[![license](http://img.shields.io/badge/license-Apache%20v2-orange.svg)](https://raw.githubusercontent.com/protodev-site/analysis/master/LICENSE)
[![Go Reference](https://pkg.go.dev/badge/github.com/protodev-site/analysis.svg)](https://pkg.go.dev/github.com/protodev-site/analysis)
[![Go Report Card](https://goreportcard.com/badge/github.com/protodev-site/analysis)](https://goreportcard.com/report/github.com/protodev-site/analysis)


A foundational library to analyze an OAI specification document for easier reasoning about the content.

## What's inside?

* A analyzer providing methods to walk the functional content of a specification
* A spec flattener producing a self-contained document bundle, while preserving `$ref`s
* A spec merger ("mixin") to merge several spec documents into a primary spec
* A spec "fixer" ensuring that response descriptions are non empty

[Documentation](https://godoc.org/github.com/protodev-site/analysis)

## FAQ

* Does this library support OpenAPI 3?

> No.
> This package currently only supports OpenAPI 2.0 (aka Swagger 2.0).
> There is no plan to make it evolve toward supporting OpenAPI 3.x.
> This [discussion thread](https://github.com/protodev-site/spec/issues/21) relates the full story.
>
