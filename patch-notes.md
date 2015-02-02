##### 0.8.7
resolve issue with duplicatesCheck throwing false positives on brackets
alphabeticalCheck should be less aggressive


##### 0.8.6
more bugs showing up for alphabetical and duplicates checks, gonna toggle them off by default until they are fully ironed out

##### 0.8.5
merge in PR #31 (BEM Naming-Convention Option and expand list of valid css properties)
stylint -v should return correct version now
universal check rewrite - earlier version was throwing false positives when used for multiplication (in some cases)

##### 0.8.4
readme update

##### 0.8.3
fixes to duplicates and alphabetical sort, made more specific basically
both were a little too general, will probably need more testing
tweak mixed spaces and tabs ( look for (  ) instead of (\s\s) )

##### 0.8.2
duplicates was not toggle-able - fixed https://github.com/rossPatton/stylint/issues/27
duplicates needs some work - update README to reflect that

##### 0.8.1
add npm badge and gitter
README tweaks

##### 0.8.0
checks:
    duplicates added, on by default, check for duplicate selectors or properties

config:
    duplicates: bool, for toggling duplicates check
    globalDupe: bool, for controlling reach of duplicates check

tests:
    unit tests for all the above added, as well as tests for 0.7.4
    code coverage should be around 89%

##### 0.7.4
checks:
    alphabetical added, check that properties are in the correct order

config:
    alphabetical: bool, for toggling alphabetical check

##### 0.7.3
zIndexDuplicates added, off by default
zIndexNormalize added, off by default

##### 0.7.2
bug fixes
code coverage
reduced dependencies

##### 0.7.1
numerous bug fixes
valid property test improved, throws fewer false positives than before