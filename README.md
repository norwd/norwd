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
    "The most effective debugging tool is still careful thought, coupled with judiciously placed print statements",
    "Нет войне!",
    "No code is faster than no code",
    "A language that doesn't affect the way you think about programming, is not worth knowing",
    "Anyone who tells you they're certain about how the world works is either a mathematician, or they're selling something",
    "Anything added dilutes everything else",
    "Approachable is better than simple",
    "Avoid administrative distraction",
    "Design for failure",
    "Encourage flow",
    "Favor focus over features",
    "Half measures are as bad as nothing at all",
    "It's not fully shipped until it's fast",
    "Keep it logically awesome",
    "Mind your words, they are important",
    "Non-blocking is better than blocking",
    "Practicality beats purity",
    "Responsive is better than fast",
    "Don't communicate by sharing memory, share memory by communicating",
    "Concurrency is not parallelism",
    "The bigger the interface, the weaker the abstraction",
    "Make the zero value useful",
    "A little copying is better than a little dependency",
    "Clear is better than clever",
    "Reflection is never clear",
    "Errors are values",
    "Don't just check errors, handle them gracefully",
    "Design the architecture, name the components, document the details",
    "Don't panic",
    "If no code is good code, then surely less code is better code... right?",
    "I reject your reality and substitute my own!",
    "Failure is always an option",
    "The only difference between science and screwing around is writing it down",
  }
  .OrderBy(_ => new Random().Next())
  .First();
}
```
