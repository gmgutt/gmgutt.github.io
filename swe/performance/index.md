# Performance

## Decision-Making Process

Adapted from [Guide to the Software Engineering Body of Knowledge v4.0](https://ieeecs-media.computer.org/media/education/swebok/swebok-v4.pdf)

```mermaid
flowchart TB

  a[Understand the real problem] --> b[Define the selection criteria]
  a --> c[Identify all reasonable technically feasible solutions]
  b --> d[Evaluate each alternative against the selection criteria]
  c --> d
  d --> e[Select the preferred alternative]
  e --> f[Monitor the performance of the selected alternative]
  f --> a

```

## Profile

Run the process for real to measure where the time is being spent and establish a baseline.

## It's Probably I/O
