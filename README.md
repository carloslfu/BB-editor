# BB editor

This is a research project for achieve an embeddable visual programing editor. This project is mainly inspired in [Blockly][blockly-git] and [Snap-BYOB][snap-git] awesome projects.

The goal is to get anyone to create, modify and learn to program without being an expert, make accessible all technology and facilities to expert programmers to view, manage and modify programs efficiently. Imagine no plain code, work in your mobile device and navigate across your code fastly. This mainly will be a code editor not only a text editor.

To achieve this goal the editor should be:

- Cross-platform.
- Support touch gestures, awesome for work in portable devices or in a large touch screen and collaborate with others.

The advantages of this approach:

- All code are structured, not is just plain code. You only work with blocks that represents ideas, behaviors and entities.
- Easliy refactoring, all code is linked. Feel free to refactor large codes without a pain.
- Visualize your code by levels: low (atomic), medium, high ...
- Recognize code patterns allows make automatized refactors (awesome!).
- Organize and give extra meaning to your code.
- Personalize the graphical representation of your code, this will be very fun.
- Fast understanding of large codes, useful for education and productivity of develop enviroments.

Visit the [BB-editor group][BB-editor-group] for discuss, get feedback or propose your ideas.

[BB-editor-group]: https://groups.google.com/forum/#!forum/bb-editor
[blockly-git]: https://github.com/google/blockly
[snap-git]: https://github.com/jmoenig/Snap--Build-Your-Own-Blocks

##Roadmap

See the [Board on trello][BB-editor-trello]. In order of priority:

[BB-editor-trello]: https://trello.com/b/B7bNibhe/bb-editor

### BBlocks

I'm working in [BBlocks][BBlocks-git] a flexible GUI for BB editor, this must work like a blockly extension ( for use with Blocklify ).

[BBlocks-git]: https://github.com/carloslfu/BBlocks.js

### Blocklify

The main goal of this project is allows to Blockly based projects some features that for modularity and flexibility must be extesions for the Blockly core.

The idea is experiment with [blocklify][blocklify-git], understand and get some knowledge about the GUI and architecture requirements of BB-editor (Blocklify is developed with BBlocks simultaneously).

[blocklify-git]: https://github.com/carloslfu/blocklify

### BB editor implementation

Finally, with an awesome GUI and some useful features, all is ready for make a full editor for embedded visual programing.
