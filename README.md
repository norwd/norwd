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
  public string Fortune => new[]
  {
    "The computing scientist’s main challenge is not to get confused by the complexities of his own making. - Edsger Dijkstra",
    "One of my most productive days was throwing away 1000 lines of code. - Ken Thompson",
    "When in doubt, use brute force. - Ken Thompson",
    "Life is too short to run proprietary software. - Bdale Garbee",
    "What I cannot build, I do not understand. - Richard Feynman",
    "Testing can show the presence of bugs, not their absence. - Edsger Dijkstra",
    "With sufficient thrust, pigs fly just fine. However, this is not necessarily a good idea. - From RFC1925",
    "The most effective debugging tool is still careful thought, coupled with judiciously placed print statements. - Brian Kernighan",
    "Unix is simple. It just takes a genius to understand its simplicity. - Dennis Ritchie",
    "The first principle is that you must not fool yourself - and you are the easiest person to fool. - Richard Feynman",
    "The best camera is the one at L2. - https://xkcd.com/2645",
    "Нет войне!",
    "Network packets travelling uphill (use a carrier pigeon) - BOFH excuse #24",
    "No code is faster than no code. - merb motto",
    "Do not lie to your Doctor, your Lawyer, or your Compiler",
    "If we’d asked the customers what they wanted, they would have said “faster horses” - Henry Ford",
    "JWZ’s Law of Software Envelopment: “Every program attempts to expand until it can read mail. Those programs which cannot so expand are replaced by ones which can.”",
  }
  .OrderBy(_ => new Random().Next())
  .First();
}
```
