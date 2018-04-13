# Custom Rules in Shake 0.16.3

This is an educational project to explain how to use Niel Mitchell's
[Shake](http://shakebuild.com) build system as a library, and how to enrich it
with custom rules.

This project aims to explain the concepts needed to to create custom rules with 
Shake >= 0.16.3.

As explained in the [release announcement](https://neilmitchell.blogspot.com/2017/09/shake-016-revised-rule-definitions.html)
the API for user defined rules has changed drastically.

The motivation for writing this came from the rewrite of parts of the build tool 
we use where I work, as I explained in a [blog post](http://sheyll.blogspot.com/2018/04/shake-for-shake-users.html) where I also explain 
some fundamental concepts and terms used in the new Shake.

More input came from this [discussion on reddit](https://www.reddit.com/r/haskell/comments/8amdov/i_wrote_a_short_piece_on_three_important_concepts) and 
[this github issue](https://github.com/ndmitchell/shake/issues/574).

In order to write a short and helpful guide to Shake custom rules,
I decided to use a literate Haskell as document format, and hackage as
a publishing platform ;)

This way I can use Haddock to generate a fully hyperlinked document!

