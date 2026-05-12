# Sunfish Fancy Mode

A modified interface for the Sunfish chess engine.

## Features

- Human playing with Human (local play)
- Original Sunfish engine support
- Rubik Mode for move memorization and training
- Replay memorized move sequences
- Simple terminal-based interface

---

## Requirements

- Python 3.x
- Sunfish chess engine

---

## Usage

### Human playing with Human Mode (new feature)

```bash
python tools/fancy.py -bothhumans
```

Play locally with two human players sharing the same board.

---

### Original Engine Mode

```bash
python tools/fancy.py -cmd ./sunfish.py
```

Play against the original Sunfish chess engine.

---

### Rubik Mode

```bash
python tools/fancy.py -Rubik_mode
```

Rubik Mode allows the program to memorize moves and replay them with you, similar to memorizing Rubik’s Cube algorithms.

---

## The Memorized Match

```text
1- e2e4  b8c6
2- b1c3  g8f6
3- d2d4  e7e5
4- d4e5  c6e5
5- f2f4  e5c6
6- c1d2  d7d6
7- g1f3  d8e7
8- d1e2  c6b4
9- a1c1  f6d7
10- a2a3  c7c6
11- f3d4  c6c5
12- d4f5  b4c2
13- c1c2  e7d8
14- c3d5  h7h6
15- e2b5  a7a6
16- b5a4  b7b5
17- f1b5  h6h5
18- b5c6  a8b8
19- e4e5  d6e5
20- d2a5  b8b4
21- a3b4  d8a5
22- d5f6  g7f6
23- b4a5  h8g8
24- c2d2  g8g2
25- c6d7  e8d8
26- a4c6  e5e4
27- d7e6  c8d7
28- c6d7
```

---

## License

Based on the original Sunfish chess engine.
Modified and extended with Fancy Mode features.
