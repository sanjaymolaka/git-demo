#Demo Git Repository

This is the first file in this repo

##Ipsum Below

Change the user name and e-mail address to your own. You will probably also want to use this when registering to GitHub later on.

Note: Use global to set the username and e-mail for every repository on your computer.

If you want to set the username/e-mail for just the current repo, you can remove global


Hi

The include and includeIf sections allow you to include config directives from another source. These sections behave identically to each other with the exception that includeIf sections may be ignored if their condition does not evaluate to true; see "Conditional includes" below.

You can include a config file from another by setting the special include.path (or includeIf.*.path) variable to the name of the file to be included. The variable takes a pathname as its value, and is subject to tilde expansion. These variables can be given multiple times.

The contents of the included file are inserted immediately, as if they had been found at the location of the include directive. If the value of the variable is a relative path, the path is considered to be relative to the configuration file in which the include directive was found. See below for examples.