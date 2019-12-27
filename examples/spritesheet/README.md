# UniStore
This is an example of a store with a spritesheet.

What the following things do?

**Header part of the store**
- title: Title of the store. For example app store name.
- author: name of the author of the store.
- url: URL to the store file, so you can update it within Universal-Updater.
- file: Filename of the store. (I suggest keeping that the same name of the store, so you have a static filename.)
- sheet: [Optional] for a Spritesheet with Icons. Put the path to the `.t3x` file there.
- description: Description of the store.
- version: Not used yet.

**Entries**
- version: version of the app.
- author: Author name of the app.
- description: Description of the app.
- iconIndex: [Optional] Index of the wanted Icon of the spritesheet.
- fileSize: The size of the file, if unknown, put `0`.

- script: Includes the whole function, when you select the specific Entry.

**IMPORTANT**
- The file extension of the store *must* be `.unistore`!
- Spritesheets can be created with Tex3ds.