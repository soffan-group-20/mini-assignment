## Hampus

| Refactoring       | Effort | How often used | Outcome                                                                                                                                                 |
| ----------------- | ------ | -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Renaming field    | low    | often          | better readability, more consistent naming                                                                                                              |
| Extracting method | medium | often          | Helps keep code complexity down by moving logic into reusable blocks                                                                                    |
| Modulerizing code | high   | rarely         | Makes code more readable and easier to maintain by sometimes adding an additional layer of complexity that in turn will make the code much more mudular |

## Erik

| Refactoring       | Effort | How often used | Outcome                                                     |
| ----------------- | ------ | -------------- | ----------------------------------------------------------- |
| Renaming field    | low    | often          | better readability, more consistent naming                  |
| Extracting method | medium | rarely         | keeps code better structured and can help reduce complexity |
| Extract class     | high   | rarely         | make code more readable and easier to maintain              |

## Adam

| refactoring                                | effort | how often used | outcome |
| ------------------------------------------ | ------ | -------------- | ------- |
| renaming field                             | low    | often          | more intuitive naming making for improved code readability |
| extracting method                          | medium | often          | makes code modular and flexible, reduce clutter leading to improved code readability |
| encapsulate field                          | medium | often          | reduces risk of something unintended being done to a field, e.g. by only allowing small increments or decrements |

## Didrik

| refactoring                 | effort      | how often used | outcome                                                                              |
| --------------------------- | ----------- | -------------- | ------------------------------------------------------------------------------------ |
| renaming field              | low         | often          | increases readability, more consistent naming                                        |
| extracting method           | medium      | often          | helps keep code complexity down by moving logic into reusable blocks                 |
| implement singleton pattern | medium      | never          | this pattern sucks, so the code becomes unreadable (use context instead)             |
| implement builder pattern   | medium      | often          | increases readability, and modularity                                                |
| implement factory pattern   | medium      | rarely         | reduces LOC and makes code more self documenting                                     |
| implement observer pattern  | medium      | sometimes      | increase modularity, reduces complexity inside atomic functions                      |
| implement strategy pattern  | challenging | often          | absolute best pattern available: increases readability, modularity, self documenting |

https://en.wikipedia.org/wiki/Code_refactoring
