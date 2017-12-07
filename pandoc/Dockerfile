FROM haskell

RUN cabal update && cabal install pandoc pandoc-citeproc

ENTRYPOINT [ "pandoc" ]
