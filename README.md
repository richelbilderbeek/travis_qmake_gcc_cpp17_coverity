# travis_qmake_gcc_cpp17_coverity

Branch|[![Travis CI logo](TravisCI.png)](https://travis-ci.org)
---|---
master|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp17_coverity.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp17_coverity)
coverity_scan|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp17_coverity.svg?branch=coverity_scan)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp17_coverity)

<a href="https://scan.coverity.com/projects/richelbilderbeek-travis_qmake_gcc_cpp17_coverity">
  <img alt="Coverity Scan Build Status"
       src="https://scan.coverity.com/projects/12045/badge.svg"/>
</a>

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean Travis CI build, with specs:
 * Build system: `qmake`
 * C++ compiler: `gcc`
 * C++ version: `C++17`
 * Libraries: `STL` only
 * Code coverage: none
 * Static code analys: Coverity Scan
 * Source: one single file, `main.cpp`

More complex builds:
 * [none]

Less complex builds:
 * Use C++98: [travis_qmake_gcc_cpp98_coverity](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp98_coverity)
 * Use C++11: [travis_qmake_gcc_cpp11_coverity](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp11_coverity)
 * Use C++14: [travis_qmake_gcc_cpp11_coverity](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_coverity)
