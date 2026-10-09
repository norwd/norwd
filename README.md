<!-- REUSE-IgnoreStart -->
```csharp
/// <summary>
/// Hi, I'm <see cref="norwd" />.
/// </summary>
public class norwd
{
    /// <summary>
    /// My <see cref="norwd.Pronouns" /> are he/him/his.
    /// </summary>
    public const Pronoun Pronouns = Pronoun.He | Pronoun.Him | Pronoun.His;

    /// <summary>
    /// Get a randomised fortune each time.
    /// </summary>
    /// <remarks>
    /// These fortunes are periodically set as my bio!
    /// </remarks>
    public string Fortune => new[]
    {
        "Нет войне!", // https://crisisrelief.un.org/ukraine-crisis
        "A language that doesn't affect the way you think about, is not worth knowing",
        "Anything added dilutes everything else",
        "Approachable is better than simple",
        "Clear is better than clever",
        "Don't panic",
        "A unit test is most useful when it fails",
        "A unit test that passes, says nothing",
        "The large print giveth, and the fine print taketh away",
        "A wealth of information creates a poverty of attention",
    }
    .OrderBy(_ => new Random().Next())
    .First();
}

/**
 * SPDX-FileCopyrightText: 2026 Y. Meyer-Norwood <norwd@noreply.codeberg.org>
 * SPDX-License-Identifier: LicenseRef-Hippocratic-3.0-CL-ECO-LAW-MIL-SV
 */
```
<!-- REUSE-IgnoreEnd -->

I'm currently working on:

* [EVi] - A programmer's text editor
* [etc] - My dotfiles, configs, settings, ~/etc...
* [zzz] - Drop-in replacement for `sleep(1)` that snores 💤
* [zbase] - Unix tools, slowly being rewritten in Zig
* [farbfeld] - Image processing and conversion tools for the .ff image format.
* [slopcheck] - Check for signs of LLM agents in git repositories - Rewrite of @liberty's [slopcheck][slopcheck-orig] in POSIX shell

[slopcheck]: https://codeberg.org/norwd/slopcheck
[slopcheck-orig]: https://codeberg.org/liberty/slopcheck
[etc]: https://codeberg.org/norwd/etc
[quotes]: https://codeberg.org/norwd/quotes
[zbase]: https://codeberg.org/norwd/zbase
[sbase]: https://core.suckless.org/sbase
[EVi]: https://codeberg.org/evi-editor/evi
[zmenu]: https://codeberg.org/norwd/zmenu
[zzz]: https://codeberg.org/norwd/zzz
[zwm]: https://codeberg.org/norwd/zwm
[farbfeld]: https://codeberg.org/norwd/farbfeld

Checkout my repositories [here][my-repos] for more.

[my-repos]: https://codeberg.org/norwd?q=&tab=repositories&sort=moststars

*All of my code is 100% Slop free!*

<img src="https://codeberg.org/norwd/.profile/raw/branch/main/assets/badge.png" height="50" />

<!--
SPDX-FileCopyrightText: 2026 Y. Meyer-Norwood <norwd@noreply.codeberg.org>
SPDX-License-Identifier: LicenseRef-Hippocratic-3.0-CL-ECO-LAW-MIL-SV
-->