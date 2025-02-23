# What is Gip?

Gip is Pig spelled backwards, but you can also think of it as Git with the "t" changed to a "p" for no particular reason. More importantly, Gip is a set of Bash script wrappers for Git, created as a result of my own daily usage and to help me avoid the hazards of easily forgotten & arcane syntax.

Many scripts are dirt-simple and have an `--echo` parameter that causes them to just spit out the command(s) they will execute instead of performing them, which is helpful when doing potentially destructive things, as well as learning/remembering how Git works. Most have a built-in `--help` (all should, of course, but I've been lazy).

## Rationale

The average gip script has a very specific use case. In principle, if I work at enough places with enough weird and unique problems, I might eventually end up with 100+ scripts, but probably not 1000+. The idea here is structuring commands around, "What is my objective?" rather than as funny-looking tools that can be used to achieve that objective, if only I could remember how. I can't remember the names of all my scripts, but I can scan them for keywords faster than I can google for Git syntax.

Thus it isn't that I think Git is badly designed\*, just that it has horrible syntax. As an example, it took me forever to figure out how to make `gip-fetch` actually just do *what I would expect git fetch to do by default* (I'm not sure it does anything useful at all, by default). There isn't even a need for a Git GUI, especially given the current state of affairs in the GUI world...

Anyhow, I have hoped this effort might inspire others to take up the cause and build a more complete and thorough toolset along these lines.

\* Okay, I'll admit I think Git branch tracking is badly designed.