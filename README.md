# Snakes & Ladders (Java)

A console-based **Snakes & Ladders** dice game written in Java. This was my first game project.

## How to play

- Press Enter to roll the dice.
- You need to roll a **6** to start.
- Land on a ladder to climb up, land on a snake to slide down.
- Reach the final square to win. The game reports how many moves you took.

## Run

Requires JDK 8 or newer.

```bash
javac *.java
java Main
```

## Files

| File | Purpose |
|---|---|
| `Main.java` | Entry point and welcome/exit messages |
| `Game.java` | Game loop, board, snakes and ladders |
| `Generate_Random_Number.java` | Dice roll helper |
