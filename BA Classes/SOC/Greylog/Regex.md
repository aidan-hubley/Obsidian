#SOC
# Intro / What is Regex?
Regex, a regular expression is a sequence of characters that specifies a search pattern in text. Usually such patterns are used by string-searching algorithms for "find" or "find and replace" operations on strings, or for input validation.

## regexr.com
An online tool to **learn**, **build**, and **test** Regular expressions (RegEx / RegExp)
- Create / Connect an account to regexr.com and you can save patterns

# The Basics of Regular Expressions
Not all programs, commands, and programming languages use the same regular expressions, but they all share similarities. 
|Character|What does it do?|Example|Matches|
|-|-|-|-|
|^|Matches beginning of line|^abc|abc, abcdef..., abc123|
|$|Matches [end of line](https://www.computerhope.com/jargon/e/eol.htm)|abc$|my:abc, 123abc, theabc|
|.|Match any [character](https://www.computerhope.com/jargon/c/charact.htm)|a.c|abc, asg, a2c|
|\||[OR](https://www.computerhope.com/jargon/o/oroperat.htm) operator|abc\|xyz|abc or xyz|
|(...)|[Capture](https://www.computerhope.com/jargon/c/capture.htm) anything matched|(a)b(c)| Captures 'a' and 'c'|
|(?:...)|Non-capturing group|(a)b(?:c)|Captures 'a' but only groups 'c'
|[...]|Matches anything contained in [brackets](https://www.computerhope.com/jargon/b/bracket.htm)|[abc]|a,b, or c
|[\^....]|Matches anything not contained in brackets|[\^abc]|xyz, 123, 1de
|[a-z]|Matches any characters between 'a' and 'z'|[b-z]|bc, mind, xyz
|{x}|The exact 'x' amount of times to match|(abc){2}|abcabc
|{x,}|Match 'x' amount of times or more|(abc){2,}|abcabc, abcabcabc
|{x,y}|Match between 'x' and 'y' times.|(a){2,4}|aa, aaa, aaaaa
|*|Greedy match that matches everything in place of the *|ab*c|abc, abbcc, abcdc
|+|Matches character before + one or more times|a+c|ac, aac, aaac,|
|?|Matches the character before the ? zero or one times. Also, used as a non-greedy match|ab?c|ac, abc
|\\|Escape the character after the backslash or create an [escape sequence](https://www.computerhope.com/jargon/e/escasequ.htm).|a\\sc|a c
