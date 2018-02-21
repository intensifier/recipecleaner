# RecipeThing

Recipe sites suck. Make them suck a little less.

#### [Download for Firefox](https://addons.mozilla.org/en-US/firefox/addon/recipething/)
#### [Download for Chrome](https://chrome.google.com/webstore/detail/recipe-thing/omonbdfjebcopdfdkiaaajifkaelcohp)

![](https://i.imgur.com/hIRrrvF.gif)


## Building

If you'd rather build the extension yourself rather than downloading
from the extension stores.

    npm install
    npm run build

    # Open a firefox window with the extension already loaded in.
    npm run web-ext

    # Rebuild on files changed:
    npm run build:watch

    # Run tests on files changed
    npm run test:watch

    # Check for style violations
    npm run lint

## License

RecipeThing is available under GNU GPLv3. See `LICENSE` in the root of
this repository.
