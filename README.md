# StateBreaker

**Learn U.S. geography through a ball-and-paddle game.**

StateBreaker is an educational Android app built with **MIT App Inventor** by **Team StateBreaker**. It combines arcade gameplay with a U.S. map and regional information screens, giving players a playful way to explore state names, abbreviations, and locations.

## Why StateBreaker?

Learning state locations can involve a lot of memorization. StateBreaker brings that practice into a game: players keep a ball in play, hit blocks labeled with state abbreviations, and see states highlighted on the map. Regional information screens provide another way to explore the geography behind the game.

## Features

- **Geography meets arcade gameplay:** a ball, a draggable paddle, and blocks labeled with U.S. state abbreviations.
- **Visual map feedback:** state images connect gameplay to locations on the U.S. map.
- **Score and lives:** keep track of progress during each game.
- **Start, pause, and resume:** control the pace of play.
- **Results and replay:** view the final score and play again.
- **Regional learning screens:** explore West, Mountain States, Middle West, Southwest, Northeast, and Southeast.
- **Editable block code:** open the complete project in MIT App Inventor to inspect the screens and logic.

## How to play

1. Tap **Start** to begin.
2. Drag the paddle to keep the ball in play and hit the state blocks.
3. Watch the map highlights and your score as you play.
4. Tap **Pause** to stop temporarily, then **Resume** to continue.
5. On the results screen, choose **Play Again** for another game or **Info** to explore the regions.
6. Select a region to view its information, then use **Back** to return.

## Open and run the project

### What you need

- A computer with a browser and access to [MIT App Inventor](https://ai2.appinventor.mit.edu/).
- An account that can sign in to App Inventor.
- An Android phone or tablet with **MIT AI2 Companion** for live testing.
- The computer and Android device connected to the same Wi-Fi network.

This project includes an external App Inventor extension. Android is the intended testing platform; iOS compatibility has not been verified.

### Import the source

1. Download [StateBreaker.aia](StateBreaker.aia) from this repository. On GitHub, open the file and choose **Download raw file** if necessary.
2. Sign in to [MIT App Inventor](https://ai2.appinventor.mit.edu/).
3. Choose **Projects → Import project (.aia) from my computer**.
4. Select `StateBreaker.aia` and complete the import. If prompted about an existing project name, choose a different name to preserve your existing project.
5. Open **Designer** to inspect the layouts or **Blocks** to inspect the program logic.

### Test with an Android device

1. Open the imported project in App Inventor.
2. Open **MIT AI2 Companion** on your Android device.
3. In App Inventor, choose **Connect → AI Companion**.
4. Scan the displayed QR code with Companion, or enter the connection code.
5. Once the app loads, follow the gameplay instructions above.

See the [official Companion connection guide](https://appinventor.mit.edu/explore/ai2/setup-device-wifi) if you need help connecting.

**Current distribution:** editable App Inventor source. A standalone APK is not included in this preparation package.

## Repository structure

```text
StateBreaker.aia                 Complete importable App Inventor project
README.md                       Project overview and usage instructions
appinventor-source/
├── src/                        Screen layouts (.scm) and block code (.bky)
├── assets/                     Maps, images, audio, and bundled extension
└── youngandroidproject/        App Inventor project settings
```

Use the `.aia` file to import the app. The expanded files are also provided so readers can inspect individual layouts, blocks, and assets directly on GitHub.

## Built with

| Component | Purpose |
| --- | --- |
| MIT App Inventor | Visual screen design and block-based programming |
| Canvas, Ball, and ImageSprite | Game area, ball, paddle, and map graphics |
| DynamicComponents extension | Creating components at runtime |
| TinyDB | Passing saved game data between screens |
| Sound and Clock components | Audio feedback and timed behavior |

StateBreaker uses the [DynamicComponents extension](https://github.com/ysfchn/DynamicComponents-AI2) to create game components while the app is running.

## Feedback

If Issues is enabled for this repository, report a problem there. Include your Android version, device model, the screen where the problem occurred, and the steps needed to reproduce it. Screenshots are helpful when a layout looks incorrect.

## Credits and licensing

**Project team:** Team StateBreaker.

The project includes third-party components, images, and audio. Asset origins and the applicable license notices are being reviewed. This preparation package does not yet include a project-wide license granting reuse rights; public availability alone does not establish permission to reuse every asset.

## Thank you

Thanks for checking out StateBreaker! We hope you enjoy playing and learning about U.S. geography.
