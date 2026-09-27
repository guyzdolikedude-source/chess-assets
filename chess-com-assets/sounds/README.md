# Chess.com sounds

> [!WARNING]
> These Chess.com-originated files may be subject to copyright, trademark, and Chess.com terms of use. This repository does not grant a license to copy, modify, distribute, or use them. Review the applicable Chess.com terms and obtain any required authorization before use.

This folder contains the Chess.com **default** sound-event catalog. All local files are in [`default/`](./default/), using the same event filename as the default sound endpoint.

Canonical source base URL:

```text
https://images.chesscomfiles.com/chess-themes/sounds/_MP3_/default/
```

| File | Trigger |
| --- | --- |
| [`move-self.mp3`](./default/move-self.mp3) | You move a piece |
| [`move-opponent.mp3`](./default/move-opponent.mp3) | Opponent moves a piece |
| [`move-check.mp3`](./default/move-check.mp3) | A check is delivered |
| [`move-self-check.mp3`](./default/move-self-check.mp3) | You deliver check |
| [`move-opponent-check.mp3`](./default/move-opponent-check.mp3) | Opponent delivers check |
| [`capture.mp3`](./default/capture.mp3) | Any capture |
| [`castle.mp3`](./default/castle.mp3) | Castling |
| [`promote.mp3`](./default/promote.mp3) | Pawn promotion |
| [`premove.mp3`](./default/premove.mp3) | Pre-move placed |
| [`illegal.mp3`](./default/illegal.mp3) | Illegal move attempted |
| [`game-start.mp3`](./default/game-start.mp3) | Game begins |
| [`game-end.mp3`](./default/game-end.mp3) | Game ends (also plays on checkmate) |
| [`game-win-long.mp3`](./default/game-win-long.mp3) | Win (extended) |
| [`game-lose.mp3`](./default/game-lose.mp3) | Loss |
| [`game-lose-long.mp3`](./default/game-lose-long.mp3) | Loss (extended) |
| [`game-draw.mp3`](./default/game-draw.mp3) | Draw |
| [`draw-offer.mp3`](./default/draw-offer.mp3) | Draw offered |
| [`tenseconds.mp3`](./default/tenseconds.mp3) | Low time warning |
| [`notify.mp3`](./default/notify.mp3) | Notification |
| [`notification.mp3`](./default/notification.mp3) | Notification (alternate) |
| [`achievement.mp3`](./default/achievement.mp3) | Achievement unlocked |
| [`puzzle-correct.mp3`](./default/puzzle-correct.mp3) | Puzzle correct |
| [`puzzle-correct-2.mp3`](./default/puzzle-correct-2.mp3) | Puzzle correct (alternate) |
| [`puzzle-wrong.mp3`](./default/puzzle-wrong.mp3) | Puzzle wrong |
| [`lesson_pass.mp3`](./default/lesson_pass.mp3) | Lesson passed |
| [`lesson-fail.mp3`](./default/lesson-fail.mp3) | Lesson failed |
| [`event-start.mp3`](./default/event-start.mp3) | Event starts |
| [`event-end.mp3`](./default/event-end.mp3) | Event ends |
| [`event-warning.mp3`](./default/event-warning.mp3) | Event warning |
| [`correct.mp3`](./default/correct.mp3) | Correct answer |
| [`incorrect.mp3`](./default/incorrect.mp3) | Incorrect answer |
| [`decline.mp3`](./default/decline.mp3) | Offer declined |
| [`shoutout.mp3`](./default/shoutout.mp3) | Shoutout |
| [`boom.mp3`](./default/boom.mp3) | Explosion effect |
| [`click.mp3`](./default/click.mp3) | Click UI sound |
| [`scatter.mp3`](./default/scatter.mp3) | Scatter effect |

## Filename compatibility

The archived default bundle used the earlier names `drawoffer.mp3` and `lesson-pass.mp3`; those files are stored here with the current endpoint names `draw-offer.mp3` and `lesson_pass.mp3`.

The historical bundle did not include distinct `move-self-check.mp3`, `move-opponent-check.mp3`, or `boom.mp3` files. Until those canonical endpoint files can replace them, the two check-specific files use the default `move-check.mp3` clip and `boom.mp3` uses the default `scatter.mp3` clip. The canonical source base above is retained for those replacements.
