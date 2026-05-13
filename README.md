<!-- markdownlint-disable -->

<!-- WARNING! ANY CHANGES MADE HERE WILL BE LOST -->

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
  /// Some of my external links.
  /// </summary>
  public IDictionary<string, Uri> Links => new Dictionary<string, Uri>
  {
    ["CodeBerg"]      = new Uri("https://https://codeberg.org/norwd"),
    ["GitHub"]        = new Uri("https://github.com/norwd"),
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
    "Нет войне!",
    "A language that doesn't affect the way you think about, is not worth knowing",
    "Anything added dilutes everything else",
    "Approachable is better than simple",
    "Clear is better than clever",
    "Don't panic",
    "A unit test is most useful when it fails",
    "A unit test that passes, says nothing",
    "When an honest man discovers that he is mistaken, he will either cease to be mistaken, or cease to be honest",
    "The large print giveth, and the fine print taketh away",
  }
  .OrderBy(_ => new Random().Next())
  .First();
}
```

# I'm Using GitHub Under Protest

My projects are currently hosted on GitHub.
This is not ideal; GitHub is a proprietary, trade-secret system that is not Free and Open Source Software (FOSS).
I am deeply concerned about using a proprietary system like GitHub to develop my FOSS projects.
I have an [open discussion][Leaving GitHub Discussion] where I am planning how to move away from GitHub in the long term.
I urge you to read about the [Give up GitHub] campaign from the [Software Freedom Conservancy] to understand some of the reasons why GitHub is not a good place to host FOSS projects.

If you are a contributor who personally has already quit using GitHub, please [check this resource][Leaving GitHub Discussion] for how to send in contributions without using GitHub directly.

Any use of my projects' code by GitHub Copilot, past or present, is done without my permission.
I do not consent to GitHub's use of any of my projects' code in Copilot.

![Logo of the GiveUpGitHub campaign](https://sfconservancy.org/static/img/GiveUpGitHub.png)

[Leaving GitHub Discussion]: https://github.com/norwd/norwd/discussions/7
[Give up GitHub]: https://GiveUpGitHub.org
[Software Freedom Conservancy]: https://sfconservancy.org

All of my code is 100% Human-Made!

<img src="https://codeberg.org/norwd/human/raw/branch/main/docs/automatic-logo.svg" height="50" />

