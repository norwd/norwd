<!--
SPDX-FileCopyrightText: 2026 Y. Meyer-Norwood <norwd@noreply.codeberg.org>
SPDX-License-Identifier: LicenseRef-Hippocratic-3.0-CL-ECO-LAW-MIL-SV
-->

# Welcome

If you'd like to contribute, please open a PR.
Be sure to explain what your proposed changes do.
If you're unsure about something,
or don't know how to make a change that you'd like to see,
open an issue and I'll see what I can do.

## Developer Certificate of Origin

This repository enforces the Developer Certificate of Origin ([DCO]).
All commit messages must contain the [`Signed-off-by`] line
with an email address that matches the commit author.
The DCO is a lightweight way to certify that you wrote,
or otherwise have the right to submit,
the code you are contributing to this project.

The DCO (Version 1.1) reads:

<!--
SPDX-SnippetBegin
SPDX-SnippetCopyrightText: Copyright (C) 2004, 2006 The Linux Foundation and its contributors.
SPDX-License-Identifier: LicenseRef-DCO-Version-1.1
-->
```
By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.
```
<!--
SPDX-SnippetEnd
-->

Note that this effectively rules out all LLM-generated code.
As any code produced from an AI is essentially taken from publicly accessible code,
there is no way to verify that the code has been certified under the DCO.
Even the person who prompted the AI could not certify the code produced.

The *only* way that LLM generated code could be legally signed off on would be if:

1. The data-set contains only code that could be traced back to individual authors
2. *AND* those authors consented to their code being included in the data-set
3. *AND* their code was published under a compatible open source license

Such a model does not currently exist.

## AI Policy

The use of any AI or LLMs in this project is strictly forbidden.
This includes but is not limited to generation or review of code, documentation, or other files,
creation of or contribution to bug reports, pull requests, and discussions,
and to the debugging, optimising, security scaning, etc,
or otherwise using any of the files distributed under the terms of these contribution guidelines.
Likewise the usage of AI or LLMs to process, parse, analyse, train on,
or otherwise use in any way the contents or outputs of this project,
including any compilation artifacts, binary blobs, or data files,
whether distributed by this project or others, or built from this project by anyone,
is strictly forbidden.

Any AI generated PRs will be rejected.

### Exceptions

The term AI has taken on a narrow meaning in recent years,
largely due to LLMs and other kinds of generative models,
however, the term has much older and much broader meaning.
For example, the Lisp programming language was developed in the 1950s
for the the express purpose of AI reasearch,
and yet it is not the subject of this ban.
Lisp contributions, and the use of programs written in Lisp (by a human) are most welcome.

The purpose of this ban is to prevent the cancerous spread of slop,
and the illegal and unethical practices of the AI industry,
not to litigate whether ChatGPT is just the same as [ELIZA] (it isn't).

See also:

* [CODE OF CONDUCT]
* [Developer Certificate of Origin][DCO]

[CODE OF CONDUCT]: https://codeberg.org/norwd/.profile/src/branch/main/CODE_OF_CONDUCT.md
[DCO]: https://developercertificate.org
[`Signed-off-by`]: https://git-scm.com/docs/git-commit#Documentation/git-commit.txt---signoff
[ELIZA]: https://en.wikipedia.org/wiki/ELIZA
