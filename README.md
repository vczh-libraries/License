# License

This repo contains license information for other repos in this organization. The [LICENSE](https://github.com/vczh-libraries/License/blob/master/LICENSE) file only applies to this file (README.md).

If a file is covered in multiple licenses, you can pick any one from these licenses for that file.

# License for Tools, GacJS and LLM Supporting Files

### Applies to

- Source files in [vczh-libraries/Tools](https://github.com/vczh-libraries/Tools)
- Source files in [vczh-libraries/GacJS](https://github.com/vczh-libraries/GacJS)
- All files under the **.github** folder in [vczh-libraries/Release](https://github.com/vczh-libraries/Release)
- Does not apply to any submodule. They are assigned with separated licenses.

They are shared under [Apache v2.0](https://github.com/vczh-libraries/License/blob/master/LICENSE_Apache_v2).
They are not constrained by **the extra restrictions**.

# License for release repos

### Applies to
- [vczh-libraries/Release](https://github.com/vczh-libraries/Release)
- [vczh-libraries/iGac](https://github.com/vczh-libraries/iGac)
- [vczh-libraries/wGac](https://github.com/vczh-libraries/wGac)
- Does not apply to any submodule. They are assigned with separated licenses.

### Content

All source files in these locations can be shared under [Apache v2.0](https://github.com/vczh-libraries/License/blob/master/LICENSE_Apache_v2), with **the extra restrictions**. For any statement in the Apache v2.0 license, if it conflicts with this file (README.md), then the one in this file has higher priority.

Image files cannot be shared under this license, they can only be used in test projects in **GacUI Organization**.

### The Extra Restrictions

For any project which uses **GacUI**, authors should ensure the following restrictions.
- **GacUI** means the above listed repos or their modifications.
- **GacUI Organization** means [github.com/vczh-libraries](https://github.com/vczh-libraries)
- **GacUI Authors** means all autorized developers in [the GacUI team](https://github.com/orgs/vczh-libraries/people).

1. If you want to redistribute the source code of **GacUI** to any other person, organization or release it publicly, you can choose any compatible license, but you should also include **the extra restrictions**.
2. If you modify source files in **GacUI**, you should:
    - Grant **GacUI Authors** the permission of using the modified version, including merging them into **GacUI Organization**, without any condition or restriction.
    - It does not affect other source files unless the modified **GacUI** does not function without them.
3. If you port **GacUI** to an existing or new platform, it is also considered as modification.
    - This rule only applies to implementation of **INativeController**.
    - It does not affect other source files unless the **INativeController** implementation does not function without them.
    - If the platform or the source code running on a platform that is private or protected by any contracts, see `5.`.
4. `2.` and `3.` don't apply to any other kinds of improvements that are not changing licensed source files, e.g. adding new templates, new controls, new user interfaces, or making new tools to help developing projects that consume **GacUI**.
5. If you have special need, please establish an agreement with [vczh](https://github.com/vczh).

# License for GacUI Extensions

### Applies to

- Source files in [vczh-libraries/xgSkins](https://github.com/vczh-libraries/xgSkins)
- Does not apply to any submodule. They are assigned with separated licenses.
- Does not apply to any `Import` folder. These source files could be found in release repos.

They are shared under [Apache v2.0](https://github.com/vczh-libraries/License/blob/master/LICENSE_Apache_v2).
They are not constrained by **the extra restrictions**.

# License for dev repos

### Applies to
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
  - [vczh-libraries/gGac](https://github.com/vczh-libraries/gGac)
- Does not apply to any submodule. They are assigned with separated licenses.

### Content

All files in these locations, if they are originally created by or have been modified by [vczh](https://github.com/vczh) or other members in this organization, can be shared under [Microsoft Reference Source License](https://github.com/vczh-libraries/License/blob/master/LICENSE_MS_RSL), which simply means:
- You can read and debug the source code
- You cannot use it for other purposes

### Extra Flexibility

- You can modify the source code for testing purpose.
- You can submit your changes to these repos.
- You can apply changes you made to these repos to **release repos**.
  - If you would like to submit your change to the **Release** repo, ensure to run [Tools/Build.ps1](https://github.com/vczh-libraries/Tools/blob/master/Tools/Build.ps1) first. You need to enlist all repos that contains C++ source code to the same folder in order to make the script work.
  - The binary you release need to eventually built from source files from **release repos**.

### Notice

Source files from dev repos has a combined copy in **Release repos** in [here](https://github.com/vczh-libraries/Release/tree/master/Import).

If you have special need, please establish an agreement with [vczh](https://github.com/vczh).
