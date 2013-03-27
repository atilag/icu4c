= NOTE =
This is just a fork from Linaro icu4c repository (http://android.git.linaro.org/git-ro/platform/external/icu4c).
There are some variables that are initialized but not used, causing gcc 4.6 to break build when -Werror flag is used. This is the case for FirefoxOS builds. So I fix it.
I'm not sure why this is not fixed on mainstream repository.

Juan Gomez
_AtilA_
