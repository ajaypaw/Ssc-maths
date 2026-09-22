# v10 Changes

## Main fix
The previous mobile exam dock was rendered at every mobile screen because its responsive rule was not scoped to `body.inExam`. v10 explicitly hides the exam dock outside an active test.

## Rebuild
All major screens now have a consistent app-like mobile layout rather than applying the CBT layout outside the test screen.
