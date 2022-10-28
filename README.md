# Blockchain-Book
Learn Blockchain by Building One
This is the full source code for my book, Learn Blockchain by Building One (Apress / Amazon).

Please submit any issues found in the code here: https://github.com/dvf/blockchain-book/issues

And if I haven't responded to them, please get my attention at hi@dvf.nyc and I'll do my best to help you out.

The Code
The finalized blockchain is located in /chapters/chapter_7.

Please ensure all dependencies are installed:

cd chapters/chapter_7
poetry install
Creating virtualenv chapter-7-uY9ygsE2-py3.8 in /home/dan3x/.cache/pypoetry/virtualenvs
Installing dependencies from lock file

Package operations: 50 installs, 0 updates, 0 removals

  • Installing pyparsing (2.4.7)
  • Installing six (1.15.0)
  • Installing attrs (20.2.0)
  • Installing colorama (0.4.3)
  • Installing idna (2.10)
  • Installing iniconfig (1.0.1)
...
Then you can run the node:

$ poetry shell
(chapter-7-py3.8) $ python node.py

2021-02-16 11:37.35 Creating genesis block
2021-02-16 11:37.35 Server listening on 0.0.0.0:8888
2021-02-16 11:37.35 Found external IP: XXX.XXX.XXX.XXX
