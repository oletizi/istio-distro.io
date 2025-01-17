---
title: "Contributing to GetMesh"
url: /community/contributing
---

We welcome contributions from the community. Please read the following guidelines carefully to maximize the chances of your PR being merged.

### Code Reviews

* Indicate the priority of each comment, following this
  [feedback ladder](https://www.netlify.com/blog/2020/03/05/feedback-ladders-how-we-encode-code-reviews-at-netlify/).
  If none was indicated it will be treated as `[dust]`.
* A single approval is sufficient to merge, except when the change cuts
  across several components; then it should be approved by at least one owner
  of each component. If a reviewer asks for changes in a PR they should be
  addressed before the PR is merged, even if another reviewer has already
  approved the PR.
* During the review, address the comments and commit the changes _without_ squashing the commits.
  This facilitates incremental reviews since the reviewer does not go through all the code again to
  find out what has changed since the last review.

### DCO

All authors to the project retain copyright to their work.
However, to ensure that they are only submitting work that they have rights to,
we are requiring everyone to acknowledge this by signing their work.

The sign-off is a simple line at the end of the explanation for the
patch, which certifies that you wrote it or otherwise have the right to
pass it on as an open-source patch. The rules are pretty simple: if you
can certify the below (from
[developercertificate.org](https://developercertificate.org/)):

```
Developer Certificate of Origin
Version 1.1
Copyright (C) 2004, 2006 The Linux Foundation and its contributors.
660 York Street, Suite 102,
San Francisco, CA 94110 USA
Everyone is permitted to copy and distribute verbatim copies of this
license document, but changing it is not allowed.
Developer's Certificate of Origin 1.1
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

then you just add a line to every git commit message:

    Signed-off-by: Joe Smith <joe@gmail.com>

using your real name (sorry, no pseudonyms or anonymous contributions.)

You can add the sign off when creating the git commit via `git commit -s`. 

Or, you can sign off the whole PR via `git rebase --signoff main`.

