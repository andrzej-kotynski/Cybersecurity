## SAST and DAST Differences:

| DAST                                                            | IAST                                                           | SAST                                                                                   |
| --------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| performed after application deployment                          | performed after application deployment                         | performed before application deployment                                                |
| used at the later stages of Software Development Cycle (SDLC)   | used at the later stages of SDLC                               | used early in the Software Development Cycle (SDLC)                                    |
| does not analyse and does not require access to the source code | integrated within the application; it's present at the runtime | scans actual source code - SAST is a part of the compilation phase included in the IDE |
| lower number of false positives                                 | -                                                              | bigger number of false positives - SAST isn't aware of other security countermeasures  |
| higher number of false negatives                                | -                                                              | lower number of false negatives                                                        |
| covers front-end, configuration and an environment              | -                                                              | front-end, configuration and environment are not in the scope of SAST                  |
| identifies security issues visible from end-user point of view  | -                                                              | detects any weakness - no matter if it is relevant from the end user perspective       |


*It's important to note that both SAST and DAST compliment each other, it's best utilize both approaches.*

<a href="https://github.com/andrzej-kotynski/andrzej-kotynski/blob/main/README.md">Back to portfolio page</a>