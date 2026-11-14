# Grid rules library

An open library of building rules for architects and the tools they use: one sheet per
place, each figure with where it comes from.

## Status

Nothing is in this repository yet. The format of a sheet is not settled, and no sheet has
been written.

The code that checks a plan against rules lives in the
[Grid repository](https://github.com/ongrid-arch/grid), under `packages/rules`.

## What a sheet will hold

A sheet covers one place: a country, a region or a city. For each rule it records facts
only:

- the figure and its unit;
- the document it comes from, its edition and the clause number;
- who and what the rule applies to, in our own words;
- the address of the official page where it was read, and the day it was read;
- whether a person has checked it against the document.

## What it will never hold

- Text from a building code, a standard or a regulation. No sentences, tables, definitions
  or images of them.
- Rules collected in bulk from a publisher's website.
- A figure presented as checked when no person has checked it. A figure found by an AI is
  marked as found by an AI until a named person has opened the document and confirmed it.

## What it is not

General guidance, not your local rules. Nothing here says a plan complies or is approved.
The local authority and a licensed professional decide. This library is not affiliated
with, or endorsed by, the publishers of the documents it names.

## Licence

The licence has not been chosen yet. See [LICENSE-PENDING.md](LICENSE-PENDING.md).
