# RegEx

* Single regex that matches either of these:

    antelope rocks out
    antelopes rock out

/antelopes?\srocks?\sout/g

* Regex that matches either of:

    goat
    moat

  but not:

    boat

/[g|m]oat/g

* Regex that matches dates in YYYY-MM-DD format.

/\d{1,4}-\d{1,2}-\d{1,2}/g