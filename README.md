<!--
SPDX-FileCopyrightText: 2026 Y. Meyer-Norwood <norwd@noreply.codeberg.org>
SPDX-License-Identifier: LicenseRef-Hippocratic-3.0-CL-ECO-LAW-MIL-SV
-->

<!-- REUSE-IgnoreStart -->
```csharp
/**
 * SPDX-FileCopyrightText: 2026 Y. Meyer-Norwood <norwd@noreply.codeberg.org>
 * SPDX-License-Identifier: LicenseRef-Hippocratic-3.0-CL-ECO-LAW-MIL-SV
 */

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
    /// Some of my external links. Places to find me, things I'm working on, etc...
    /// </summary>
    public IDictionary<string, Uri> Links => new Dictionary<string, Uri>
    {
        ["CodeBerg"]      = new Uri("https://codeberg.org/norwd"),
        // ["GitHub"]        = new Uri("https://github.com/norwd"), // https://giveupgithub.org
        ["JiraStopWatch"] = new Uri("https://jirastopwatch.com"),
        ["ThisTimeStamp"] = new Uri("https://thistimestamp.com"),
    };

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
    }
    .OrderBy(_ => new Random().Next())
    .First();
}
```
<!-- REUSE-IgnoreEnd -->

All of my code is 100% Human-Made!

<img src="https://codeberg.org/norwd/human/raw/branch/main/docs/automatic-logo.svg" height="50" />

