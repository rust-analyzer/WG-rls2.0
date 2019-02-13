# rls2.0 Working Group

## What is happening right now?

We are figuring organizational stuff out! To participate, join this Zulip topic:

https://rust-lang.zulipchat.com/#narrow/stream/185405-t-compiler.2Frls-2.2E0/topic/scope.20and.20how.20to.20proceed

## About WG

### Primary Goal

Discover ideal architecture for IDE-compiler by starting a "from scratch" implementation. Especially, how to handle two hardest things:

- name resolution/macro expansion
- trait resolution

Quantify how hard would be to port existing rustc to the IDE architecture.


### Secondary Goals

- provide better RLS experience by making a "better racer"
- facilitate `rustc` librarification by discovering and prototyping separable libraries
- facilitate specification of the language, by producing "more declarative" implementation


### Deliverables

- a language server which provides compiler-based code completion for a subset of the Rust language.
- "design knowledge": which approaches do and do not work in IDE contexts.
- (optional) improvements to existing tooling, like replacing racer in RLS with something more powerful, or making rustfmt capable of dealing with incomplete code.


## Contact Points

[This repo][wg-repo] contains pointers to all the important venues, but doesn't
have much content itself.

Most of the  communication happens in this [Zulip stream]. If you want to be
involved, but don't know how, say "Hi!" in the Zulip!

The bulk of the actual work happens in the [rust-analyzer] repository.

[wg-repo]: https://github.com/rust-analyzer/WG-rls2.0
[Zulip stream]: https://rust-lang.zulipchat.com/#narrow/stream/185405-t-compiler.2Frls-2.2E0
[rust-analyzer]: https://github.com/rust-analyzer/rust-analyzer

Non-exhaustive list of folks you can ping on GitHub / Zulip about RLS-2.0 (feel
free to add yourself to the list):

* [@matklad](https://github.com/matklad)
* [@pnkfelix](https://github.com/pnkfelix)
* [@Xanewok](https://github.com/Xanewok)

There's also `WG-rls2.0` working group in the Zulip.
