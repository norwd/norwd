<!-- markdownlint-disable -->

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
    ["GitHub"]        = new Uri("https://github.com/norwd"),
    ["JiraStopWatch"] = new Uri("https://jirastopwatch.github.io"),
  };

  /// <summary>
  /// Get a randomised fortune each time.
  /// </summary>
  /// <remarks>
  /// These fortunes are periodically set as my bio!
  /// </remarks>
  public string Fortune => new[]
  {
    "When in doubt, use brute force",
    "What I cannot build, I do not understand",
    "Testing can show the presence of bugs, not their absence",
    "Нет войне!",
    "A language that doesn't affect the way you think about, is not worth knowing",
    "Anything added dilutes everything else",
    "Approachable is better than simple",
    "It's not shipped until it's fast",
    "Non-blocking is better than blocking",
    "Practicality beats purity",
    "Responsive is better than fast",
    "The bigger the interface, the weaker the abstraction",
    "A little copying is better than a little dependency",
    "Clear is better than clever",
    "Don't panic",
  }
  .OrderBy(_ => new Random().Next())
  .First();
}
```
