# rectangularbot
An archival Discord bot for the cardistry community. That is, a bot that allows cardists on Discord to access popular tutorials for their favorite flourishes, indexing both those currently available and many thought to be lost to time.

## Commands
Users can interface with Rectangularbot's library through a variety of commands, all of which are prefixed (aligning with common Discord bot style) with `$`. Commands may be followed in some cases by arguments, which are space-delimited. All example images were taken from Discord servers where Rectangularbot is regularly used!

### `tutorial`
The `tutorial` command allows a user to request a link to a specific tutorial. It must be followed by exactly one argument, which is the name of the requested move. If such Rectangularbot can't find a tutorial with that name, it will instead provide a link to a form where users can request the addition of new moves.

![an example of a successful tutorial request](/tutorial-success.png)
![an example of a failed tutorial request](/tutorial-failure.png)

### `show`
The `show` command generates a text file containing the names of all the moves that match some search criteria and sends that file as a response to the command. It must be followed by exactly one argument, which is a tag to filter Rectangularbot's library by. A tag is the name of a cardist, cardistry brand, media type (video, tutorial pack, book), or a move type (cuts, twirls, fans, aerial moves, etc). For the `show` command, users may also use the argument `all`, which returns all moves currently in the library.

![an example of the show command for all oliver sogard moves](/show-oliver-sogard.png)

### 'random'
The `random` command allows a user to request a random move from Rectangularbot's library. It is optionally followed by an argument for the tag from which to make a random selection. For example `$random fans` sends a link to a tutorial for a random fan move. In the absence of an argument, `random` selects from the entire library.

![an example of requesting a random twirl](/random-twirls.png)
![random move](/random.png)

## Where's the code?
I developed Rectangularbot as a passion project hosted on [Repl.it](repl.it) before I understood the critical importance of local backups. In the process of Repl.it's steady crawl towards mediocrity, they deleted Rectangularbot's source code due to inactivity on my account for a few months. Rectangularbot, though I spent much time maintaining it while it was active, now only exists in the message history of several of the most popular cardistry Discord servers, but it remains to me an important project and learning experience.
