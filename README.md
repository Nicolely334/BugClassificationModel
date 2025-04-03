# BugClassificationModel

Since developers typically do not know they are writing incorrect software, there is always the question of whether the change they just made has introduced a bug. A bug in the source code leads to an unintended state within the software, and this corrupted state eventually results in an undesired behavior. This is logged in a bug report message in a change tracking system, frequently surfacing months after the initial bug injection. By the time a developer receives the bug report, they must spend time to familiarize themselves with the source code and the recent changes to it.

This serves as the motivation for designing a bug classification mode, a tool to predict whether a change was buggy or clean after it has been made.

