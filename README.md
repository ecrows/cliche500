# 500+ Cliché Phrase Dataset

List of cliché phrases originally assembled in 1999 by author Laura Hayden and subsequently updated with public contributions.  Reproduced in computer-friendly format from [the list provided on Laura Hayden's website](http://suspense.net/whitefish/cliche.htm), who can be reached at suspense@suspense.net.

# Usage

The single file, `cliches.txt`, contains 550 curated cliché phrases, with one phrase per line.  You can load them however you like.

For example, in Python:

```
with open("./cliches.txt", "r") as f:
    cliches = f.read().splitlines()
    
print(cliches[0:5])
> ['ace in the hole', 'ace up your sleeve', 'acid test', 'airing dirty laundry', "all in a day's work"]
```

# Citation

For convenience, here is a citation you may wish to use.  If you are reproducing the list, please ensure you include the original source website and contact email address as requested by Laura Hayden.

```
@misc{hayden_1999,
title={Clichés: Avoid Them Like The Plague},
url={http://suspense.net/whitefish/cliche.htm},
journal={Suspense.net},
author={Hayden, Laura},
year={1999},
note={
    Downloaded from: github.com/ecrows/cliche500.
    Originally published: http://suspense.net/whitefish/cliche.htm,
    suspense@suspense.net
  }
}
```
