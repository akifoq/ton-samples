In this example we will see how to use library code for specific procedures. Also it shows how to test contracts locally with specific library environment. 

Note that I have edited Asm.fif to add support for defining library-located procedures. Namely, I have added PROCLIB and PROCLIB:<{ Fift assembler words for this purpose.

In lib.fif we locate func-generated assembler code from lib.fc in custom envelop. main.fif contains main.fc assembler code and shows how to use PROCLIB word.

test.fif also contains another example of this two words usage.

You can see how to publish a lib in masterchain in ton-samples/libs folder.
