# bbedit-egsinp-language-module
A BBEdit codeless language module for EGSnrc input files.

Place the egsinp.plist file under ~/Library/Application Support/BBEdit/Language Modules/ and restart the application. This also works with TextWrangler; the egsinp.plist then goes under ~/Library/Application Support/TextWrangler/Language Modules/.

Input block delimiters and their indentation are hard-coded with spaces (4 spaces per tab). If you want to add new delimiters or edit current ones (for example, replacing the spaces with actual tab characters), simply open the egsinp.plist with a text editor. Do not use Xcode or one of the plist editor to open egsinp.plist; it messes up the format of the file sometimes.
