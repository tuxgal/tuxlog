# tuxlog

[![PkgGoDev](https://pkg.go.dev/badge/github.com/tuxgal/tuxlog)](https://pkg.go.dev/github.com/tuxgal/tuxlog) [![Build](https://github.com/tuxgal/tuxlog/actions/workflows/build.yml/badge.svg)](https://github.com/tuxgal/tuxlog/actions/workflows/build.yml) [![Tests](https://github.com/tuxgal/tuxlog/actions/workflows/tests.yml/badge.svg)](https://github.com/tuxgal/tuxlog/actions/workflows/tests.yml) [![Lint](https://github.com/tuxgal/tuxlog/actions/workflows/lint.yml/badge.svg)](https://github.com/tuxgal/tuxlog/actions/workflows/lint.yml) [![CodeQL](https://github.com/tuxgal/tuxlog/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/tuxgal/tuxlog/actions/workflows/codeql-analysis.yml) [![Go Report Card](https://goreportcard.com/badge/github.com/tuxgal/tuxlog)](https://goreportcard.com/report/github.com/tuxgal/tuxlog)

A go library that provides minimalistic level logging based on the
[`tuxlogi`](https://github.com/tuxgal/tuxlogi) generic level logging
interface.

The goal is minimalism with no external dependencies other than the standard
go library and the [`tuxlogi`](https://github.com/tuxgal/tuxlogi) interface
itself.

This is currently used by
[`cablemodemcli`](https://github.com/tuxgal/cablemodemcli) and other projects
in `go` used by [`tuxgal`](https://github.com/tuxgal) and
[`tuxgalhomelab`](https://github.com/tuxgalhomelab).
