# Bee Hints

A bookmarklet plus a static results page for the NYT Spelling Bee. Run the bookmarklet on
nytimes.com/puzzles/spelling-bee while signed in; it reads your saved words and opens a page
with a found/total grid by first letter and length, a two-letter list, and pangram info.

- `install.html` builds the bookmarklet (drag it to the bookmarks bar, or copy its text on a phone).
- `index.html` is the results page. Data arrives in the URL fragment, which is never sent to a server,
  and is kept in your browser's `localStorage`.

No backend, no credentials. Unofficial and not affiliated with The New York Times.
