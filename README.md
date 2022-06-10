# promise

An example PROMISE file.
This is a method for software to employ delayed re-licensing.
I am not a lawyer and this file has not been approved by a lawyer.

## How?

1. Replace `{PRODUCT}` with your Licensed Work.
2. Replace `{COMPANY}` with the name of a single Licensor who owns the entire copyright over
   the Licensed Work.

## What?

* This method works **if and only if** the original Licensed Work is under a single copyright
  from a single entity. It should be. You should use a [CLA](https://en.wikipedia.org/wiki/Contributor_License_Agreement)
  or a [CTA](https://en.wikipedia.org/wiki/Copyright_transfer_agreement) for your project.
* This text does not need to be a part of the license itself.
  It's very clean, brief, and unambiguous when confined to a file of its own.
* The text intentionally avoids the words "License" and "Agreement" in the title so it will not
  be confused for a license itself.
* The text intentionally _does not_ link itself to the text of your `LICENSE` file in any way.
  It does not matter what original license your Licensed Work is released under.
* The sample text defaults to two (2) years license delay.

## Why?

There exist a number of software licenses (such as the [BSL 1.1](https://mariadb.com/bsl11/))
which contain within them a clause promising to change the software license as-of a particular
date and/or anniversary of the software's release.

Such a promise cannot be added to _standard_ licenses without breaking them. The GPLv2 is no
longer the GPL if you modify it by adding such a clause. As such, it makes much more sense to
encode such promises in their own file, completely separate from `LICENSE`.
