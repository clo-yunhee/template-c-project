# Template folder for a Makefile C project

Written by Chloé (Rika) Ichinose, under MIT License

---

## Features for developers wanting to use this template

* Made to build only one target at a time;
* Builds based on a binary-sources-headers directory tree;
* Keeps intermediate files in hidden directories for faster incremental builds;
* Customisable target name, directory names;
* Customisable compiler and linker flags, keeps command line flags if provided (Argument conflicts aren't handled!);
* Customisable additional Debug/Release flags with a BUILD_TYPE switch;
* Predefined `clean` rule to clean up intermediate files;
* Predefined `clean-dist` rule to clean up all build files (binary and intermediate);
* Predefined `re` rule to clean up and rebuild the whole project.

## Future additions planned (maybe)

- Move the customisable bits to another file, via an `include`;
- Add support for C++ in the same Makefile;
- Add support for multiple targets at once;
- Add support for nested projects and project dependencies;
- ...

## Contributing

I don't really have any plan for contributors or anything like that, just... feel free to leave suggestions, things I should add, remove, or change, etc.

When possible try to provide an [SSCCE](http://sscce.org)-ish example with your suggestion, whether that be a manual build, an wonky Makefile, or whatnot.

## How to use

(Section to be written)
