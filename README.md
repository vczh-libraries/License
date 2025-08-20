# License

This repo contains license information for other repos in this organization. The [LICENSE](https://github.com/vczh-libraries/License/blob/master/LICENSE) file only applies to this file (README.md).

# License for GacJS

- [vczh-libraries/GacJS](https://github.com/vczh-libraries/GacJS)

Source code in this repo is shared under [Apache v2.0](https://github.com/vczh-libraries/License/blob/master/LICENSE_Apache_v2).

# License for release repos

### Applies to `master` and `release-*` branches of
- [vczh-libraries/Release](https://github.com/vczh-libraries/Release)
- [vczh-libraries/iGac](https://github.com/vczh-libraries/iGac)
- [vczh-libraries/gGac](https://github.com/vczh-libraries/gGac)

### Content

All source files in these locations that created by **GacUI Authors**, can be shared under [Apache v2.0](https://github.com/vczh-libraries/License/blob/master/LICENSE_Apache_v2), with **the extra restrictions**. For any statement in the Apache v2.0 license, if it conflicts with this file (README.md), then the one in this file has higher priority.

Image files are not shared under this license, they can only be used in test projects in **GacUI Organization**.

### The Extra Restrictions

For any project which uses **GacUI**, authors should ensure the following restrictions
1. If you want to redistribute the source code of **GacUI** to any other person, organization or release it publicly, you can choose any compatible license, but you should also include **the extra restrictions**.
2. If you modify **GacUI**, you should:
    - Grant **GacUI Authors** the permission of using the modified version, including merging them into **GacUI Organization**, without any condition or restriction.
    - Ensure the modified version is self-contained.
    - This rule only applies to the **GacUI** part of your projects.
3. If you port **GacUI** to a new platform, or create a new port to replace any existing port, it is also considered as modification.
    - If the platform or the source code running on a platform that is private or protected by any contracts, see `5.`.
4. `2.` and `3.` don't apply to any other kinds of improvements that are not changing licensed source files, e.g. adding new templates, new controls, new user interfaces, or making new tools to help developing projects that consume **GacUI**.
5. If you have special need, please establish an agreement with [vczh](https://github.com/vczh).

**GacUI** means any source code in this github organization or its derived version.

**GacUI Organization** means [github.com/vczh-libraries](https://github.com/vczh-libraries)

**GacUI Authors** means all autorized developers in [the GacUI team](https://github.com/orgs/vczh-libraries/people).

# License for .github/copilot-instructions.md

### Applies to

- All **.github/copilot-instructions.md** files in each dev repos

### Content

These prompt files can be shared under [Apache v2.0](https://github.com/vczh-libraries/License/blob/master/LICENSE_Apache_v2).

# License for dev repos

### Applies to
- [vczh-libraries/Tools](https://github.com/vczh-libraries/Tools)
- [vczh-libraries/Vlpp](https://github.com/vczh-libraries/Vlpp)
- [vczh-libraries/VlppOS](https://github.com/vczh-libraries/VlppOS)
- [vczh-libraries/VlppRegex](https://github.com/vczh-libraries/VlppRegex)
- [vczh-libraries/VlppParser](https://github.com/vczh-libraries/VlppParser)
- [vczh-libraries/VlppParser2](https://github.com/vczh-libraries/VlppParser2)
- [vczh-libraries/VlppReflection](https://github.com/vczh-libraries/VlppReflection)
- [vczh-libraries/Workflow](https://github.com/vczh-libraries/Workflow)
- [vczh-libraries/GacUI](https://github.com/vczh-libraries/GacUI)
- [vczh-libraries/Document](https://github.com/vczh-libraries/Document)
- [vczh-libraries/WebsiteSource](https://github.com/vczh-libraries/WebsiteSource)
- [vczh-libraries/vczh-libraries.github.io](https://github.com/vczh-libraries/vczh-libraries.github.io)
- Abondoned Repos
  - [vczh-libraries/XGac](https://github.com/vczh-libraries/XGac)

### And also applies to
- All forks of **dev repos**
- All unmentioned branches of **release repos**

### Content

All files in these locations, if they are originally created by or have been modified by [vczh](https://github.com/vczh) or other members in this organization, can be shared under [Microsoft Reference Source License](https://github.com/vczh-libraries/License/blob/master/LICENSE_MS_RSL), which simply means:
* You can read and debug the source code
* You cannot use it for other purposes
* This license doesn't stop you from submitting PRs to these repos, but you should not distribute the modification via your own forks.
  * Two licenses combined allow you to apply changes of such PRs to your own copy of codes from **release repos**.
  * To apply changes from **dev repos** to the **Release** repo automatically and systemically:
    * Enlist all repos in the same folder and run [Tools/Build.ps1](https://github.com/vczh-libraries/Tools/blob/master/Tools/Build.ps1). This is required before submitting a PR to the **Release** repo.
  * To do it manually:
    * Execute **CodePack** (described below) on `Release/CodegenConfig.xml` in a **dev repo**, and run `git status` to see what files are changed.
    * For the **GacUI** repo, [Tools/Build.ps1 -Project GacUI](https://github.com/vczh-libraries/Tools/blob/master/Tools/Build.ps1) is recommended.

### Tools

Executables of tools are no longer released directly, there are [a copy](https://github.com/vczh-libraries/Release/tree/master/Tools) for each of the following sources in **the release repo**.

Exceptions of the following sources are no longer granded, if you have any special need, you could modify the source code of [these copies](https://github.com/vczh-libraries/Release/tree/master/Tools) under this license.

- [VlppParser2/Tools/CodePack](https://github.com/vczh-libraries/VlppParser2/tree/master/Tools/CodePack)
- [VlppParser2/Tools/GlrParserGen](https://github.com/vczh-libraries/VlppParser2/tree/master/Tools/GlrParserGen)
- [Workflow/Tools/CppMerge](https://github.com/vczh-libraries/Workflow/tree/master/Tools/CppMerge)
- [GacUI/Tools/GacGen](https://github.com/vczh-libraries/GacUI/tree/master/Tools/GacGen)

### Notice

**Release repos** contain everything you need if you want to use them. You are authorized to use all the source codes [here](https://github.com/vczh-libraries/Release/tree/master/Import) under the license, but not source codes in dev repos, although they are the same only with different file organization.

If you have special need, please establish an agreement with [vczh](https://github.com/vczh).
