---
layout: post
title:  "summary of reading: march 2026"
published: true
---

- **PPMP: Chapter I & II:** As a researcher, I care about performance, and when I
read that performance is the most important factor in parallel computing. I
felt like I am reading the right book for myself. CPUs and GPUs serve different
purpose. CPU is latency-oriented whereas GPU is throughput-oriented.

- **[GPUs go brrr](https://hazyresearch.stanford.edu/blog/2024-05-12-tk):**
Learned about tensor memory accelerator (TMA) that enables a warp fire a memory
fetch and immediately move on. While `gmm.sync` relies on occupancy, meaning
warps with loaded registers wait on SMs, for `wgmma.mma_async`, the tensor core
reads its inputs directly from shared memory, not from the warp's registers.
**ThunderKittens** was born to optimize the max utilization of GPUs and enable
writing kinds of kernels for GPUs.

- **Stoner by John Williams:** 오랫동안 손에 붙든 소설이다. 부끄럽게도 작년 여름에 처음 읽은 책인데 이것 저것 뒤적이다 돌아와 끝낸 책이다. 주인공 윌리엄 스토너는 불륜자이다. 그는 한 가정을 무너뜨렸다. 그 사실에 대해서는 그의 죄목이 명백하며 부끄러운 사실이다. 그치만 모든 악당들의 서사의 공통점은 그들은 태어나길 악당이 아닌 주변 사람과 환경에 의해 만들어진 자아라는 것이다. 사실 윌리엄을 천벌 받을 죄인이라고 부르기에는 내가 대신 억울하다. 작가 존 윌리엄스는 스토너라는 책을 통해 어쩌면 모든 사랑이 모든게 아닐 수 있다고 말하는 것 같다. 순간의 진심은 순간일 뿐이고 사랑은 그저 끝이 정해져있다기보다는 누군가를 알아가는 과정일 뿐이고 그 과정에 몰입하지 못하는 순간 사랑은 잔인하게도 도망간다.
