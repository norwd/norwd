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
    ["GitHub"] = new Uri("https://github.com/norwd"),
  };

  /// <summary>
  /// Get a randomised fortune each time.
  /// </summary>
  /// <remarks>
  /// These fortunes are periodically set as my bio!
  /// </remarks>
  public string Fortune => new[]
  {
    "When in doubt, use brute force. - Ken Thompson",
    "What I cannot build, I do not understand. - Richard Feynman",
    "Testing can show the presence of bugs, not their absence. - Edsger Dijkstra",
    "The most effective debugging tool is still careful thought, coupled with judiciously placed print statements. - Brian Kernighan",
    "Нет войне!",
    "No code is faster than no code. - merb motto",
    "A language that doesn't affect the way you think about programming, is not worth knowing. - Alan Perlis",
    "Anyone who tells you they're certain about how the world works is either a mathematician, or they're selling something. - Tom Scott https://youtu.be/Wif1EAgEQKI",
    "Anything added dilutes everything else.",
    "Approachable is better than simple.",
    "Avoid administrative distraction.",
    "Design for failure.",
    "Encourage flow.",
    "Favor focus over features.",
    "Half measures are as bad as nothing at all.",
    "It's not fully shipped until it's fast.",
    "Keep it logically awesome.",
    "Mind your words, they are important.",
    "Non-blocking is better than blocking.",
    "Practicality beats purity.",
    "Responsive is better than fast.",
    "Speak like a human.",
  }
  .OrderBy(_ => new Random().Next())
  .First();
}
```
