Count a GitHub user's total stars.

Install
```
npm install -g starz
```

Usage
```
$ starz harrypotter0 -l 15

Total: 23
awesome-algorithms          ★  5
CODEFORCES                  ★  2
TopCoder_Solutions          ★  2
CodersZone                  ★  2
Hack-bvp-Track-the-load     ★  2
Niec-Hack-Earthquake-City   ★  2
awesome-data-science        ★  1
twitter-bot                 ★  1
webapp                      ★  1
Coding_Tutorials            ★  1
college-projects            ★  1
angularRestaurantApp        ★  1
tensorflow                  ★  1
Pythonista                  ★  1
```

Options
```
-a, --auth    GitHub username:password for rate limits
-t, --thresh  Only show repos above this threshold      [default: 1]
-l, --limit   Only show this many repos                 [default: null]
```
