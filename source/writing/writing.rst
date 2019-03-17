.. _writing:

Writing
=======

Although it's easier at first to write text into each Label and textbox in a
game, this can make editing the text later down the road a tedious process, and
managing translations like this would be impossible. Instead, Godot can use
spreadsheets in a .csv format for managing translations.

Essentially, you just need to make a spreadsheet in your favorite spreadsheet
editing program (Microsoft Excel, Libreoffice Calc, Google Sheets, etc.).
Godot will automatically import any .csv file in the project file, and will
automatically reimport any changes to them. The structure of the spreadsheet
must follow a specific format, where the First column is a translation
key (e.g. PLAYER_NAME, WORLD1_DIALOG1, etc.), the first row is a locale
(e.g. en_US), and the cells in the spreadsheet are the translations. You can
see a list of supported locales here: `Locales`_.

+----------------+----------+------------------+------------+
|                | en       | de               | fr         |
+----------------+----------+------------------+------------+
| DIALOG_GREET   | Hello!   | Guten tag!       | Bonjour!   |
+----------------+----------+------------------+------------+
| DIALOG_GOODBYE | Goodbye! | Auf Wiedersehen! | Au revoir! |
+----------------+----------+------------------+------------+

You can read the official documentation about this here:
`Importing translations`_.

You can also read more about Godot's translation system here:
`Internationalizing games`_, however it's not strictly necessary. Just know
sound effects and images can be swapped out for different locales, and that a
project's name can also be translated.

.. _`Importing translations`: http://docs.godotengine.org/en/3.1/getting_started/workflow/assets/importing_translations.html
.. _`Locales`: http://docs.godotengine.org/en/3.1/tutorials/i18n/locales.html
.. _`Internationalizing games`: http://docs.godotengine.org/en/3.1/tutorials/i18n/internationalizing_games.html
