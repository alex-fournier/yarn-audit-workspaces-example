An example project using yarn workspaces[1]. One of the workspaces
uses a vulnerable package in devDependencies, but `yarn audit`[2] doesn't report it.

yarn 1.22.5 was tested.




[1]
https://yarnpkg.com/lang/en/docs/workspaces/

[2]
https://github.com/yarnpkg/yarn/pull/6909
