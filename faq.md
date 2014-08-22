# Frequently Asked Questions

## Who can attend office hours?

Join us, we welcome all levels. 

## What happens during office hours?

Most folks bring their computers to work on their haskell code. Sometimes there are discussions and/or questions. Others who are more experienced may explain haskell concepts. Overall we are hanging out.

## Where/how should I learn haskell?

There are a number of formats and resources available.

* Books: [Learn You a Haskell (LYAH)](http://learnyouahaskell.com/), [Real World Haskell](http://book.realworldhaskell.org/), [Programming in Haskell](http://www.cs.nott.ac.uk/~gmh/book.html), [and more](http://reinh.com/notes/posts/2014-07-25-recommended-reading-material.html)
* Videos: [Haskell Lectures by Dr. Erik Meijer](https://www.youtube.com/playlist?list=PLlHF8jw6FqhBKWxhfZchP0haXXPYk5mSB)
* Classes: [edX - Intro to Functional Programming](https://www.edx.org/course/delftx/delftx-fp101x-introduction-functional-2126#.U_bFL7xdVgw)  
* Tutorials: [Haskell Wiki's list](http://www.haskell.org/haskellwiki/Tutorials), [@bitemyapp's learn haskell](https://github.com/bitemyapp/learnhaskell), [@katychuang's getting started with haskell](https://github.com/katychuang/getting-started-with-haskell)  

## GHC Compiler Installation Tips

You can either install the "all-in-one" [Haskell Platform](https://www.haskell.org/platform/) as the quick and dirty way to get a taste of ghci OR spend a bit more time up front to avoid package conflicts. 

For clean (manual) installation of ghc and cabal - [@bitemyapp wrote instructions on how to get started](https://github.com/bitemyapp/learnhaskell#getting-started) 

Of course, for those who'd like the purest install, you can install from source. The instructions below: 

Linux - Download the latest copies of GHC and Cabal. Follow instructions in the INSTALL file. The popular paths among those installing to source are ghc to `~/.ghc/bin` and cabal to `~/.cabal/bin`. Make sure your PATH environment variable can find these two paths.

OSX - similar to instructions for linux.

OSX10.9 Mavericks introduces problems with GCC compiler. As of May 2014, the most up to date instructions were written by [@cartazio](https://gist.github.com/cartazio/7131371) and [@katychuang](http://stackoverflow.com/questions/19579577/installing-building-ghc-with-osx-mavericks-ghc)

*Windows - you're in a class on your own. Your best bet is to install the haskell platform for the necessary c bindings. However if you're feeling particularly patient - feel free to [replicate the low level environment described on this stackoverflow thread](http://stackoverflow.com/questions/304614/haskell-on-windows-setup)




