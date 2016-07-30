# Feature name

* Proposal: [SE-NNNN](NNNN-filename.md)
* Author: [LLVM Developer](https://github.com/llvmdev)
* Status: **Awaiting review**

## Introduction

A short description of what the proposed change is. Try to keep it to a
single-paragraph "elevator pitch" so the reader understands what
problem this proposal is addressing.  

LLVM-Dev thread: [Discussion thread topic for that proposal](http://news.gmane.org/gmane.comp.compilers.llvm.devel)

## Motivation

Describe the problems that this proposal seeks to address. If the problem is
that some common pattern for which tooling/technology is currently hard to
express, show how one can currently get a similar effect and describe its
drawbacks. If it's completely new functionality that cannot be emulated,
motivate why this new functionality would help LLVM developers create better
LLVM code.

## Proposed solution

Describe your solution to the problem. Provide examples and describe how they
work. Show how your solution is better than current workarounds: is it cleaner,
safer, or more efficient?

## Detailed design

Describe the design of the solution in detail. If it involves new tooling please
describe the tooling additions in detail. If it's a new API, show the full API
and its documentation comments detailing what it does. The detail in this
section should be sufficient for someone who is *not* one of the authors to be
able to reasonably implement the proposal.

## Impact on existing users

Describe the impact that this change will have on existing code/users. Will some
use cases no longer be possible due to this change? Will parts of LLVM still
compile but produce different behavior than they used to? Is it possible to
migrate existing LLVM workflows to use the new feature or API automatically?

## Alternatives considered

Describe alternative approaches to addressing the same problem, and
why you chose this approach instead.
