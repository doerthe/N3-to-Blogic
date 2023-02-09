# N3-to-Blogic

These rules can be used to translate N3 rules to blogic. Note, that the rules do not yet support nested graphs. To run the code use:

eye "your-rule-file" aux.n3 --query translation-rules.n3 --nope --quantify http://eyereasoner.github.io/var#
