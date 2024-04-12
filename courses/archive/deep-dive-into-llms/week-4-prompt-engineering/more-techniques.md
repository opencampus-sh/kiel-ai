# More techniques

## Self Consistency

The idea is to sample multiple, diverse reasoning paths through few-shot CoT, and use the generations to select the most consistent answer.

## Generated Knowledge Prompting

First generate some knowledge given the question. Then answer the question with the knowledge as context in the second step

## Tree of Thoughts (ToT)

ToT maintains a tree of thoughts, where thoughts represent coherent language sequences that serve as intermediate steps toward solving a problem. In plain english this means that multiple solution approaches are tried and one keeps kind of log what works or. If you have solved a Suduko you probalbly are familiar with this back and forth exploration and in one of the original ToT papers they reported huge success with this method for solving sudokus.&#x20;

The ToT approach essentially enables an LM to self-evaluate the progress intermediate thoughts make towards solving a problem through a deliberate reasoning process. The LM's ability to generate and evaluate thoughts is then combined with search algorithms (e.g., breadth-first search and depth-first search) to enable systematic exploration of thoughts with lookahead and backtracking. While this leads to much better complex task solving capabilities it takes hugely more LM calls and takes quite some time..so if you want to build a chatbot this approach should not be used.
