# How to use on ChatGPT #

1) Clone the master branch or download the zip file of the master branch and unzip.
2) Rename the root folder from music21-chatgpt to music21, then zip the music21 folder.
3) In ChatGPT attach the music21 zip file (not music21-chatgpt.zip)
4) Ask ChatGPT to unzip the file to /mnt/data/ directly (make sure it doesn't do it to /mnt/data/music21)
5) Ask ChatGPT to add /mnt/data/ to system path.
6) Now ChatGPT should be able to use music21

Have a look at this convo on ChatGPT for a worked example - https://chat.openai.com/share/0f90c5ef-3bd8-462a-aec7-725dbdf02a73

P.S. There is already a popular GPT on the ChatGPT store available for free that does the above automatically. It's called Song Maker (https://chat.openai.com/g/g-txEiClD5G-song-maker). It also has some wrapper functions to help with making midi and musicxml files using as little tokens as possible. It also seems to be able to convert midi and musicxml to a text representation for ChatGPT to understand and can create html sheet music.


# music21 #

`music21` -- A Toolkit for Computer-Aided Musical Analysis and 
Computational Musicology

Copyright © 2006-2023 [Michael Scott Asato Cuthbert](http://www.trecento.com)

For more information, visit:
https://web.mit.edu/music21

To try it out, visit:
https://tinyurl.com/m21colab (runs music21 v7)

And to install, see:
https://web.mit.edu/music21/doc/usersGuide/usersGuide_01_installing.html

`Music21` runs on Python 3.10+.  Use version 4 on Python 2 or Py3.4, version 5
on Py3.5, version 6 on Py3.6, version 7 on Py3.7, version 8 on Py3.8/Py3.9.

Released under the BSD (3-clause) license. See LICENSE.
Externally provided software (including the MIT licensed Lilypond/MusicXML test Suite) and
music encoding in the corpus may have different licenses and/or copyrights. 
A no-corpus version of `music21` is available also on GitHub.

[![Build Status](https://github.com/cuthbertLab/music21/workflows/maincheck/badge.svg)](https://github.com/cuthbertLab/music21)
[![Coverage Status](https://coveralls.io/repos/github/cuthbertLab/music21/badge.svg?branch=master)](https://coveralls.io/github/cuthbertLab/music21?branch=master)

## Documentation ##

[User's Guide](https://web.mit.edu/music21/doc/usersGuide/index.html)

[Module Documentation](https://web.mit.edu/music21/doc/moduleReference/index.html)

## Mailing list ##

See: https://groups.google.com/forum/#!forum/music21list

## Contributing Guide ##

[Contributing Guide](CONTRIBUTING.md)

## Community Code of Conduct ##

`Music21` encourages contributions, discussions, and usage from all people interested in
music and computers. This encouragement extends to all people regardless of (among other aspects)
gender, race, sexual orientation, disability, religion, appearance, veteran status,
gender identity, socioeconomic status, or nationality.

Members of the community will strive to be friendly, patient, and welcoming, especially of
viewpoints and experiences different from our own. We reject harassment and contributions
(in mail, comments, or code) that belittle individuals or groups of people.

We ask all members of the community to be mindful particularly about assumptions of the
gender of users (choice of pronouns in comments and code). We recognize that members
sometimes make mistakes and will, in general, accept sincere regrets for such cases.
Blatant or repeated violations of the code will result in the removal of the
contributor’s participation in the community.

The maintainers of `music21` and associated sites will commit themselves to enforcing
this code of conduct. Users who notice violations, including instances of abuse,
harassment, or otherwise unacceptable behavior are requested to contact 
michael.asato.cuthbert@gmail.com.
Maintainers will respect confidentiality with regard to reports.

## Acknowledgements ##

The development of `music21` has been supported by
the generosity of the Seaver Institute and the
National Endowment for the Humanities.  MIT's Music and Theater Arts Section
and the School of Humanities, Arts, and Social Sciences encouraged Cuthbert
in its development.
