# Stretch Goals for the *nix Scavenger Hunt

The following goals are meant to provide a way for more experienced users to
extend their knowledge of the *nix command line.

* Use `curl` to look up the URL `http://www.imdb.com/title/tt0070948/`. The title of this film will lead you to the answer. *What is the answer?*

cabox@box-codeanywhere:~/workspace/challenge_files$ curl http://www.imdb.com/title/tt0070948/ | grep "<title>"
--- received <title>Zardoz (1974) - IMDb</title>

--- title of the film is Zardoz. Made in 1974