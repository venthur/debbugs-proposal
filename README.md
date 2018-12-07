# Proposal for a new API for Debian's Bug Tracking Software

The problem is that it is getting harder and harder to find libraries in Python
that are able to parse SOAP properly. SOAP is also very hard to debug. Since
`reportbug`'s underlying library that parses debbugs API --
[python-debianbts][python-debianbts] is writting in Python, I
[proposed][proposal] to move away from SOAP towards something more modern like
JSON.

[python-debianbts]: https://github.com/venthur/python-debianbts
[proposal]: https://lists.debian.org/debian-debbugs/2018/12/msg00000.html
