

# Features

| Raw Feature     | Raw Type | n    | Raw Vals                                                                                                                                                                                                                                                                                                                                                                                             | Desired Feature | Desired Type | Description                         |
| --------------- | :------: | ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------- | ------------ | ----------------------------------- |
| Student.ID      |   int   | 9546 | {26 - 1565}                                                                                                                                                                                                                                                                                                                                                                                          | S.ID            | int          | Unique identifier for students      |
| Student.Country |   chr   | 9546 | - Ireland<br />- Portugal<br />- Italy<br />- Lithuania<br />- Spain<br />- Russian Federation<br />- Romania<br />- Slovenia                                                                                                                                                                                                                                                                        | Cntry           | factor       | Country of the student              |
| Question.ID     |   int   | 9546 | {77 - 1549}                                                                                                                                                                                                                                                                                                                                                                                          | Q.ID            | int          | Unique identifier for questions     |
| Type.of.Answer  |   int   | 9546 | 0, 1                                                                                                                                                                                                                                                                                                                                                                                                 | Correct         | factor       | Coded: 0 = incorrect, 1 = correct   |
| Question.Level  |   chr   | 9546 | Basic, Advanced                                                                                                                                                                                                                                                                                                                                                                                      | Difficultty     | factor       | Categorical: Basic vs Advanced      |
| Topic           |   chr   | 9546 | 14 Categories:<br />- "Statistics"<br />- "Differentiation"<br />- "Real Functions of a single variable" <br />- "Linear Algebra"<br />- "Fundamental Mathematics" <br />- "Differential Equations"<br />- "Optimization" <br />- "Integration"<br /> - "Probability " <br />- "Complex Numbers"<br />- "Graph Theory" <br />- "Analytic Geometry"<br />- "Numerical Methods" <br />- "Set Theory" | Topic           | factor       | Level 0: Math topic                 |
| Subtopic        |   chr   | 9546 | 24 Subtopics                                                                                                                                                                                                                                                                                                                                                                                         | Subtopic        | factor       | Level 1: Topic of Math Topic        |
| Keywords        |   chr   | 9546 | 365 Unique Keywords                                                                                                                                                                                                                                                                                                                                                                                  | Keywords        | chr          | Additional context for the question |


## Subtopic by Topic

| Topic                               | Subtopic                                           |
| :---------------------------------- | :------------------------------------------------- |
| Analytic Geometry                   | Analytic Geometry                                  |
| Complex Numbers                     | Complex Numbers                                    |
| Differential Equations              | Differential Equations                             |
| Differentiation                     | Derivatives                                        |
|                                     | Partial Differentiation                            |
| Fundamental Mathematics             | Algebraic expressions, Equations, and Inequalities |
|                                     | Elementary Geometry                                |
| Graph Theory                        | Graph Theory                                       |
| Integration                         | Definite Integrals                                 |
|                                     | Double Integration                                 |
|                                     | Integration Techniques                             |
| Linear Algebra                      | Eigenvalues and Eigenvectors                       |
|                                     | Linear Systems                                     |
|                                     | Linear Transformations                             |
|                                     | Matrices and Determinants                          |
|                                     | Vector Spaces                                      |
| Numerical Methods                   | Numerical Methods                                  |
| Optimization                        | Linear Optimization                                |
|                                     | Nonlinear Optimization                             |
| Probability                         | Probability                                        |
| Real Functions of a single variable | Domain, Image and Graphics                         |
|                                     | Limits and Continuity                              |
| Set Theory                          | Set Theory                                         |
| Statistics                          | Statistics                                         |
