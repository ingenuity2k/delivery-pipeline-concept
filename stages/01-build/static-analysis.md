# Static Analysis

Static code analysis (SCA) checks the software source code for

* potential and obvious errors, and
* code smells.

## Static Code Analysis

It is a good practice to use a combination of several tools.

### Java SCA

* [Sonar](http://www.sonarqube.org/) provides a graphical overview of different analyzers.
* [Find Bugs](http://findbugs.sourceforge.net/) finds various problems in the source code.
* [Checkstyle](http://checkstyle.sourceforge.net/) finds various problems in the source code.
* [PMD](http://pmd.sourceforge.net/) finds various problems in the source code.
* [JDepend](http://www.clarkware.com/software/JDepend.html) finds cyclic dependencies
* [Classycle](http://classycle.sourceforge.net/) finds cyclic dependencies

### Ruby SCA

* [RuboCop](https://github.com/rubocop-hq/rubocop) finds various problems in the source code
* [MetricFu](https://github.com/metricfu/metric_fu) overview of different analyzers
* [Rails Best Practices](https://github.com/railsbp/rails_best_practices) finds various issues in Rails applications
* [Flay](http://ruby.sadi.st/Flay.html) find duplicated source code
* [Flog](http://ruby.sadi.st/Flog.html) find source code with high complexity

### Frontend SCA

* JavaScript: [ESLint](https://eslint.org/)
* TypeScript: [ESLint](https://eslint.org/) with [typescript-eslint](https://github.com/typescript-eslint/typescript-eslint) ([TSLint](https://medium.com/palantir/tslint-in-2019-1a144c2317a9) is deprecated)
  * Specifically Angular: Currently still [TSLint](https://angular.io/cli/lint), see [Angular Roadmap](https://angular.io/guide/roadmap#migration-to-eslint)

## Static Application Security Testing (SAST)

* [Source Code Analysis Tools](https://www.owasp.org/index.php/Source_Code_Analysis_Tools)
  * The [OWASP SonarQube project](https://www.owasp.org/index.php/OWASP_SonarQube_Project) covers 20+  programming languages.

### Ruby SAST

* [Brakeman](http://brakemanscanner.org/) finds security issues in Rails applications.
