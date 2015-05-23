
# TODO

* Deal with Windows newlines \r\n in Unix (opening a Windows text
file in the GUI shows some sort of symbol instead of \r). Test it
with Mac text files.

* Should the following program fail in runtime?

  procedure Main()
  {
    case (Azul) of
      Norte -> {}
      _     -> {}
  }

  - Gobstones/Hugs fails.
  - PyGobstones currently doesn't on runtime. (Typechecking fails though).

# Bugs / Issues

* Syntax highlighting doesn't work well with multiline comments.
(It could be fixed easily by syncing the whole file on each keypress,
but that would make the editor very slow).

* Ctrl+V doesn't replace the selected text if there is any.

