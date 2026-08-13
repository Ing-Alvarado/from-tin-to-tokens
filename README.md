# From Tin to Tokens

Building an LLM Inference Stack from Scratch in Rust.

A free textbook on inference-stack engineering. It covers the whole stack, from the driver interface where you write ioctl structures by hand to an HTTP endpoint serving thousands of concurrent users: attention kernels, a paged KV cache, a scheduler, multi-GPU collectives, a quantisation pipeline, and the correctness apparatus that proves any of it works. Concepts come first and implementations follow, because the implementations change every eighteen months and the concepts don't.

Written by Dave Lemphers at [Maincode](https://maincode.com). It is free and detailed on purpose.

## Read it

Download the current edition from the [releases page](https://github.com/MaincodeHQ/from-tin-to-tokens/releases/latest). Each release is one numbered edition, and the PDF is the whole book.

## Corrections

> If you find something wrong in here, and you will, that's the most useful thing you can send back.

Every number in the book states its conditions and every measurement names its hardware, so corrections can be specific. If something is wrong, unclear, or reproduces differently on your hardware, open an [erratum](https://github.com/MaincodeHQ/from-tin-to-tokens/issues/new/choose) and include the page number. Confirmed corrections are kept in [ERRATA.md](ERRATA.md) and folded into the next edition. For anything that isn't a specific correction, use [Discussions](https://github.com/MaincodeHQ/from-tin-to-tokens/discussions).

## What comes later

The book is first. The course it is built to carry, and the reference implementation it describes, will follow when they are ready.

## License

Licensed under [Creative Commons Attribution 4.0](LICENSE). Read it, share it, and teach from it, with credit to Maincode, From Tin to Tokens.
