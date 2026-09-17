# Hero Mission: The Healthy Choice

Playable build: https://joenasriani.github.io/kids-hero-quest/

Hero Mission: The Healthy Choice is a randomized 10-question health-and-safety quiz game developed as part of a multi-game interactive children’s edutainment activation in the UAE.

## Game structure

Each run randomly selects 10 questions from a built-in bank of 17 two-choice questions.

For every question, the player chooses between two responses. A correct response adds one point. An incorrect response stores that question’s associated advice text for use in the final report.

**randomly selected question → two choices → score update → next question → 10-question score → final report**

The end screen reports the score out of 10 and displays feedback determined by the score band plus advice from the first missed question, when applicable.

## Topics represented

The current question bank includes vaping and nicotine, unknown pills, drug offers, peer pressure, trusted adults, stress, lungs and heart health, exercise, smoking effects, and personal control over one’s body.

## Activation context

This game belongs to the same `kids-*` game set developed for the multi-game interactive children’s edutainment activation in the UAE.

## Evidence boundary

The game implements a quiz and score/report mechanism. The repository does not contain a validation study establishing the score as a clinical, educational, behavioral, or health assessment, nor evidence of learning retention or behavior change outside the game.

## Deployment

The working public build is the GitHub Pages deployment linked above. The repository’s current GitHub Homepage field points to an older Vercel address that returns 404 and should not be treated as the canonical build.

## Repository scope

The playable implementation is contained in `index.html`.

`index.html` is preserved as the game artifact. Documentation and discovery files must not alter the question bank, answer keys, scoring, final-report logic, controls, visuals, timing, reset behavior, or runtime behavior.
