Normally, your button elements with the btn and btn-default classes are only as wide as the text that they contain. For example:

<button class="btn btn-default">Submit</button>
This button would only be as wide as the word Submit.


By making them block elements with the additional class of btn-block, your button will stretch to fill your page's entire horizontal space and any elements following it will flow onto a "new line" below the block.

<button class="btn btn-default btn-block">Submit</button>
This button would take up 100% of the available width.


Note that these buttons still need the btn class.

Add Bootstrap's btn-block class to your Bootstrap button.

Tests
Waiting:Your button should still have the btn and btn-default classes.
Waiting:Your button should have the class btn-block.
Waiting:All of your button elements should have closing tags