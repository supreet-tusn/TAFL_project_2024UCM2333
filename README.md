# TAFL_project_2024UCM2333
# NFA → DFA Subset Construction Visualizer

An interactive web-based tool that demonstrates the **Subset Construction algorithm** — converting a Nondeterministic Finite Automaton (NFA) into an equivalent Deterministic Finite Automaton (DFA), step by step.

Built to help students understand the equivalence between nondeterministic and deterministic automata through visual, guided learning.

---

## Features

### 1. NFA Input
Define a custom NFA by entering states, alphabet, start state, accept states, and transition rules. Four built-in quick presets (Simple, Ends-in-ab, ε-NFA, Complex) are also available for instant exploration.

### 2. Subset Construction Algorithm
The core algorithm is fully implemented. It converts the NFA into an equivalent DFA by forming subsets of NFA states and incrementally building the transition table — exactly as taught in formal language theory courses.

### 3. Step-by-Step Visualization
The conversion proceeds one step at a time. Students can navigate forward and backward through each step, or use auto-play to watch the algorithm unfold. Keyboard shortcuts (← → arrow keys, Space) are also supported.

### 4. Graphical Representation
Both the original NFA and the resulting DFA are displayed as interactive graphs side by side. The diagrams clearly show how multiple NFA states combine to form a single DFA state at each step of the construction.

### 5. Transition Tables
Live NFA and DFA transition tables update alongside the diagrams. DFA rows appear progressively as new states are discovered, reinforcing the tabular view of subset construction.

### 6. Narrator Bar
At every step, a plain-language explanation describes what is happening — which subset is being processed, which transition is being computed, and why. Color-coded badges distinguish between different event types (new state, transition, dead state, completion).

### 7. String Tester
Test whether any input string is accepted or rejected by the constructed DFA. A step-by-step trace shows the state transitions for each symbol, with the current state highlighted in the diagram.

### 8. Theory Reference Page
A built-in reference page covers formal definitions of NFA and DFA, a comparison table, and an explanation of the subset construction method — keeping all learning material within the same tool.

---

## How to Use

1. Open `index.html` in any modern browser — no installation required.
2. Click **"Try the Converter"** from the home screen.
3. Enter your NFA details or select a preset, then click **"Build DFA"**.
4. Use the **Prev / Next** buttons or arrow keys to step through the conversion.
5. Use the **String Tester** to verify the constructed DFA accepts the correct language.

---

## Tech Stack

- Pure HTML, CSS, and JavaScript — no frameworks or dependencies
- SVG-based interactive diagrams
- Single self-contained file (`index.html`)

---

## Intended Audience

Students studying **Theory of Computation** or **Formal Languages and Automata** who want a visual, interactive way to understand NFA-to-DFA conversion beyond textbook diagrams.
