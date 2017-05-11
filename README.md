# License

This repo contains license information for other repos in this organization. The [LICENSE](https://github.com/vczh-libraries/License/blob/master/LICENSE) file only applies to this file (README.md).

# License for release repos

### Applies to
- [vczh-libraries/Release](https://github.com/vczh-libraries/Release)
- [vczh-libraries/XGac](https://github.com/vczh-libraries/XGac)
- [vczh-libraries/iGac](https://github.com/vczh-libraries/iGac)

### Content

All files in these repos, if they are created by [vczh](https://github.com/vczh) or other members in this organization, can be shared under [Apache v2.0](https://github.com/vczh-libraries/License/blob/master/LICENSE_Apache_v2), with extra restrictions:

For any project which uses any source codes from these repo, authors should ensure the following restrictions
1. You cannot use **GacUI** with any project under GPL family licenses. It's OK if your project is not under GPL family licenses but contains LGPL components.
2. You cannot use **GacUI** to achieve any illegal goal.
3. You should share your improvements or modifications of **GacUI** to [vczh](https://github.com/vczh) under **this license**, and ensure that they are self-contained and can be compiled, if
    - You modify **GacUI**
    - You port **GacUI** to new platforms, which basically means all classes derived from `::vl::presentation::INative*` or `::vl::presentation::elements::I*` directly or indirectly.
    - This rule doesn't apply to other kinds of improvements, e.g. adding new templates or new controls.
4. If you redistribute the code, you should keep **GacUI** under **this license**. All other code is not restricted.
5. If you have special need, please estabilish an agreement with [vczh](https://github.com/vczh).

P.S.
- **GacUI** includes all files in these release repos, and all improvements or modifications described by `3.`.
- **This license** here means Apache v2.0 with these extra restrictions.

# License for dev repos

### Applies to
- [vczh-libraries/Tools](https://github.com/vczh-libraries/Tools)
- [vczh-libraries/Vlpp](https://github.com/vczh-libraries/Vlpp)
- [vczh-libraries/Workflow](https://github.com/vczh-libraries/Workflow)
- [vczh-libraries/GacUI](https://github.com/vczh-libraries/GacUI)
- [vczh-libraries/GacJS](https://github.com/vczh-libraries/GacJS)
- [vczh-libraries/vczh-libraries.github.io](https://github.com/vczh-libraries/vczh-libraries.github.io)

### Content

All files in these repos, if they are created by [vczh](https://github.com/vczh) or other members in this organization, can be shared under [Microsoft Reference Source License](https://github.com/vczh-libraries/License/blob/master/LICENSE_MS_RSL), which simply means:
* You can read and debug the source code
* You cannot use it for other purposes

**Release repos** contain everything you need if you want to use them. You are authorized to use all the source codes [here](https://github.com/vczh-libraries/Release/tree/master/Import) under the license, but not source codes in dev repos, although they are the same only with different file organization.

If you have special need, please estabilish an agreement with [vczh](https://github.com/vczh).
