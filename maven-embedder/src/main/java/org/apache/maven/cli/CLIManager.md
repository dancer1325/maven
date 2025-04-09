* `-am,--also-make`
  * 👀if project list is specified -> ALSO build projects / -- required by the -- list 👀
  * uses
    * \+ `-pl` / `--projects` 
      * == maven modules
* `-amd,--also-make-dependents`
  * TODO:If project list is specified, also build projects that depend on projects on the list
* -B,--batch-mode	Run in non-interactive (batch) mode (disables output color)
* -b,--builder	The id of the build strategy to use
* -C,--strict-checksums	Fail the build if checksums don't match
* -c,--lax-checksums	Warn if checksums don't match
* -null,--color	Defines the color mode of the output. Supported are 'auto', 'always', 'never'.
* -cpu,--check-plugin-updates	Ineffective, only kept for backward compatibility
* -D,--define	Define a user property
* -e,--errors	Produce execution error messages
* -emp,--encrypt-master-password	Encrypt master security password
* -ep,--encrypt-password	Encrypt server password
* -f,--file	Force the use of an alternate POM file (or directory with pom.xml)
* -fae,--fail-at-end	Only fail the build afterwards; allow all non-impacted builds to continue
* -ff,--fail-fast	Stop at first failure in reactorized builds
* -fn,--fail-never	NEVER fail the build, regardless of project result
* -gs,--global-settings	Alternate path for the global settings file
* -gt,--global-toolchains	Alternate path for the global toolchains file
* `-h,--help`
  * display help information
* -itr,--ignore-transitive-repositories	If set, Maven will ignore remote repositories introduced by transitive dependencies.
* -l,--log-file	Log file where all build output will go (disables output color)
* -llr,--legacy-local-repository	UNSUPPORTED: Use of this option will make Maven invocation fail.
* -N,--non-recursive	Do not recurse into sub-projects
* -npr,--no-plugin-registry	Ineffective, only kept for backward compatibility
* -npu,--no-plugin-updates	Ineffective, only kept for backward compatibility
* -nsu,--no-snapshot-updates	Suppress SNAPSHOT updates
* -ntp,--no-transfer-progress	Do not display transfer progress when downloading or uploading
* -o,--offline	Work offline
* -P,--activate-profiles	Comma-delimited list of profiles to activate
* `-pl,--projects project1,project2,..`
  * `projectS`
    * -- are delimited by -- `,`
    * ways to specify
      * `groupId:artifactId` OR
      * `relativePathToProject`
  * uses
    * 💡specify which projects -- to -- build 💡
* -q,--quiet	Quiet output - only show errors
* -rf,--resume-from	Resume reactor from specified project
* -s,--settings	Alternate path for the user settings file
* -t,--toolchains	Alternate path for the user toolchains file
* -T,--threads	Thread count, for instance 4 (int) or 2C/2.5C (int/float) where C is core multiplied
* -U,--update-snapshots	Forces a check for missing releases and updated snapshots on remote repositories
* -up,--update-plugins	Ineffective, only kept for backward compatibility
* -v,--version	Display version information
* -V,--show-version	Display version information WITHOUT stopping build
* -X,--debug	Produce execution debug output