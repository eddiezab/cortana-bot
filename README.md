<<<<<<< HEAD
The Z-bot adds a simple command/arguments handler into Cortana. Simply add a subroutine in the following manner:

sub cmd_foo {
  elog("[*] Bar");
}

Commands can be entered from the event log, and must be prefixed with a !. To execute the above command one must simply type: !foo <along with any arguments>

Arguments are provided to the command as an array.

Additionally a help subroutine can be created to provide a summary of the command by declaring:

sub help_foo {
  return "Foo is a demo command that has no real purpose.";
}

=======
cortana-bot
===========
>>>>>>> d6c35422bd8d271bd04f7f434a5a19b77dfb3a23
