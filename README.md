Adding Git-native **tags** to commits on a repository you'd like to include as a dependency elsewhere doesn't impact dependency importation in CumulusCI for Salesforce.

Only GitHub _**releases**_ do that.  _(See [sf-cci-02-gh-release-exists-no-sf-package](https://github.com/kkgthb/sf-cci-02-gh-release-exists-no-sf-package).)_

Tags alone are ignored, even if they use the "`rel/...`" punctuation standard CumulusCI looks for in Git tags associated with GitHub releases.

For more details about building CCI-ready dependencies that will simply build via "latest commit," see [sf-cci-01-minimum-viable-build](https://github.com/kkgthb/sf-cci-01-minimum-viable-build).