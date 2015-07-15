# Conclusion

AOSCC 2015, and the discussion that lasted for the first two days has brought us to some conclusions.
The conclusions below includes those of which covers AOSC OS, website, instruments, etc. And they will
be listed with details in their votes.

## AOSC OS

### AOSC OS Core (Versioning Rules)

AOSC OS Core will be using the sub-version rule of update, when minor changes are made inside of AOSC
OS Core. There were four options raised by participants of the conference.

1. 3.0.1pN ("OpenSSH style", N is a non-zero natural number)  -> Votes: 5
2. 3.0.1a ("OpenSSL style", a stands for alphabetical letter) -> Votes: 1
3. 3.0.1.n ("GNU style", n is a non-zero natural number)      -> Votes: 4
4. 3.0.1-n ("Debian style", n is a non-zero natural number)   -> Votes: 6

As a result of this vote, the "3.0.1-n" form of versioning will be used in AOSC OS Core when minor
changes are made inside of AOSC OS Core.

### AOSC OS Core (GCC 5, the when)

AOSC OS Core will eventually "import" GCC 5.x, a question was asked regarding when to import this new
version of GCC. Everyone agreed over a suggestion to "keep both libstdcxx to retain compatibility".
Two options are raised by participants.

1. Keep it experimental in 3.99 branch, and import when Core 4 releases -> Votes: 6
2. Import the new version as a minor update during Core 3 cycle         -> Votes: 1

As a result of this vote, GCC 5.x will be imported into the Core as a experimental package, and will
not be imported into the stable series until Core 4.

### AOSC OS Core (LLVM)

Should LLVM be removed from the Core? A question raised by Icenowy Zheng, arguing against LLVM as a
part of Core, for the difficulties in cross compilation (Zheng works on the ARM port), and its 
non-universal existence between different architectural ports. So here is a yes, or no vote.

1. Remove LLVM from Core -> Votes: 7
2. Keep LLVM in Core     -> Votes: 0

LLVM will be removed from the Core in the next update release, and thus being merged to the base
sector of the abbs tree.

### Web (Domain Mail address)

Domain mail addresses will be distributed between AOSC contributors/developers, as soon as they are
set up by the webmaster. There were several options provided and raised by the participants.
Discussions were held.

The result was to use the format ```username@anthonos.org``` for the e-mail accounts.

### Web (Mail host)

Several possible mail server hosts were listed by Xiaoxing Ye during the conference that includes:

1. QQ Enterprise Mail -> No Vote
2. Office 365         -> No Vote
3. Office 365 Student -> No Vote
4. Sohu mail          -> No Vote
5. Self-hosting       -> Votes: 10

Therefore, self-hosting mail will be made. And in addition, mailing list will be hosted locally with
the help of GNU Mailman.

### AOSCC (next meeting place)

A vote on the next meeting place of AOSCC is held in the afternoon of Day 2. And several options
are provided/raised by participants.

```WARN: lacking details due to the absence of log!!```

1. Guangzhou
2. Shenzhen
3. Beijing
4. Shanghai
5. Dongguan
6. Yangzhou
7. ...

```TODO: FIND THE LACKING DETAILS```

Shanghai was chosen to be the next meeting place, for AOSCC 2016. Further details on exact dates
and location(s) were not specified yet. Keep posted for further updates.
