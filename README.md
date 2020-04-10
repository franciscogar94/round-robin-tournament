# Round-robin tournament

A round-robin tournament (or all-play-all tournament) using JavaScript / TypeScript.
The goal is to create a competition in which each team meets the other teams in two rounds.

## Actions

- `npm i` Installing Dependencies
- `npm test` Executing tests

## Basic usage

```js
import Tournament from "./src/Tournament";

const TEAMS = [
  { id: 1, name: "Arsenal" },
  { id: 2, name: "Chelsea" },
  { id: 3, name: "Liverpool" },
  { id: 4, name: "Manchester City" },
  { id: 5, name: "Manchester United" },
  { id: 6, name: "Westham" },
];

const matches = new Tournament(TEAMS).matches;
```
