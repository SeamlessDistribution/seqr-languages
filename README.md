Instructions for Windows Phone
------------------------------

The English strings can be found in "AppResources.resx".


The keys named "ResourceFlowDirection" and "ResourceLanguage" must not have their values translated.


Values within curly brackets must not be translated.

Example:

Hello {World}

To Swedish:

Hej {World}


The file format should not be changed. We expect the files to saved in a ".resx" format.


We expect all languages except for English to have the correct language suffixes in the file names.
For example, the Swedish file would be named "AppResources.sv-SE.resx" and DutchBelgian would be
named "AppResources.nl-BE.resx".

Do not replace apostrohpes with the code &apos;

Instructions for Android
------------------------

Special characters have to be escaped in Android with \
Correct definition of the apostrophe sign in the files is \' not the &apos;
Already existing unicode characters that are in the files should not be edited e.g. &#8230; &amp; &#160;

Instructions for iOS
--------------------

The files should be saved in UTF-8 Unix (LF).
Comments and keys should not be translated.
Do not add extra space and new lines.
Do not remove any " or ;

Example:

/* iOS account manager titlebar. */
"ios_account_manager_title" = "Accounts";

To Swedish:

/* iOS account manager titlebar. */
"ios_account_manager_title" = "Konton";
