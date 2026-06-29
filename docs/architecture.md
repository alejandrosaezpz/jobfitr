# Architecture

## Purpose

This document describes the intended structure of JobFitr at a high level.
It does not describe an implemented system yet.

## Proposed shape

- **Backend**: application layer under `backend/app/`
- **Frontend**: source layer under `frontend/src/`
- **Tests**: isolated test space under `tests/`
- **CI**: workflow definitions under `.github/workflows/`

## Guiding principles

- Keep the first implementation small
- Prefer explicit naming over clever abstractions
- Separate documentation from implementation

## Fictitious example boundaries

- `jobs` domain for vacancy management
- `profiles` domain for candidate data
- `applications` domain for tracking submissions

These names are illustrative only.
