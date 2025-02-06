# March-30-Project: Green Fibers Environment

## Purpose
- Managing complex enterprise environments

## Design
- Using nginx's pooling architecture, and driven by modern C++23 principles, one could easily manage their own thread pools

## Async Vs Threading
- No, the owner is doing threading; the user will have a shared pointer ownership over the pool

## What About The OS
- Today, the OS has a lot of important roles, but memory pool ownership shouldnt be it!
- Instead the OS should focus on security, inode atomics, and APU clusters
    - This author doesnt believe in quantum systems or AI, instead build DSL into your APU pulling.... most programming paradigms only give quantum supremacy over slivers of applications. Just like AI
 
## Where Did This Come From
- Read the book: Asynchronous Programming in Rust. Went through Google's/Go's green fibers and others. Great resource for Rust.

## Why Not Rust
- Because it's not really supported well. Sure the old NSA (NSA 2022) announced C/C++ insecure, but new NSA won't. Trump's isolationist and commercial-first philosophies make NSA's Dec 2022 directive mute. Plus, C++26/extensions may have lifetimes enabled. It's not monomorphization, but hey it's a start. Just like the constexpr evolution, so too may behavioral concept-based monomorphization contracts prevail. Good article about this came out in early 2024.

## What's Not Covered
- Templates, concepts, nor atomics

## What's It Good For
- Eliminating SECCOMP-based containers and instead managing process-based tasks. This simpifies the DevOps env and cost.
  - Containers were pushed hard in 2018, most of the industry has backed off... way too convoluted
