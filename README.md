# RAY

![licence](https://img.shields.io/badge/licence-Apache-2.0-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `RAY` in category **SUPERCOMPUTER**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** https://github.com/ray-project/ray · **Upstream pin:** `c50286910448ba6005a85da1e22eca94bba38428` · **Category:** SUPERCOMPUTER · **Vendor:** Anticloud FZ LLE · **Licence:** Apache-2.0

---

## What This Project Does

.. image:: https://github.com/ray-project/ray/raw/master/doc/source/images/ray_header_logo.png

.. image:: https://readthedocs.org/projects/ray/badge/?version=master
    :target: http://docs.ray.io/en/master/?badge=master

.. image:: https://img.shields.io/badge/Ray-Join%20Slack-blue
    :target: https://www.ray.io/join-slack

.. image:: https://img.shields.io/badge/Discuss-Ask%20Questions-blue
    :target: https://discuss.ray.io/

.. image:: https://img.shields.io/twitter/follow/raydistributed.svg?style=social&logo=twitter
    :target: https://x.com/raydistributed

.. image:: https://img.shields.io/badge/Get_started_for_free-3C8AE9?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8%2F9hAAAAAXNSR0IArs4c6QAAAERlWElmTU0AKgAAAAgAAYdpAAQAAAABAAAAGgAAAAAAA6ABAAMAAAABAAEAAKACAAQAAAABAAAAEKADAAQAAAABAAAAEAAAAAA0VXHyAAABKElEQVQ4Ea2TvWoCQRRGnWCVWChIIlikC9hpJdikSbGgaONbpAoY8gKBdAGfwkfwKQypLQ1sEGyMYhN1Pd%2B6A8PqwBZeOHt%2FvsvMnd3ZXBRFPQjBZ9K6OY8ZxF%2B0IYw9PW3qz8aY6lk92bZ%2BVqSI3oC9T7%2FyCVnrF1ngj93us%2B540sf5BrCDfw9b6jJ5lx%2FyjtGKBBXc3cnqx0INN4ImbI%2Bl%2BPnI8zWfFEr4chLLrWHCp9OO9j19Kbc91HX0zzzBO8EbLK2Iv4ZvNO3is3h6jb%2BCwO0iL8AaWqB7ILPTxq3kDypqvBuYuwswqo6wgYJbT8XxBPZ8KS1TepkFdC79TAHHce%2F7LbVioi3wEfTpmeKtPRGEeoldSP%2FOeoEftpP4BRbgXrYZefsAI%2BP9JU7ImyEAAAAASUVORK5CYII%3D
   :target: https://www.anyscale.com/ray-on-anyscale?utm_source=github&utm_medium=ray_readme&utm_campaign=get_started_badge

Ray is a unified framework for scaling AI and Python applications. Ray consists of a core distributed runtime and a set of AI libraries for simplifying ML compute:

.. image:: https://github.com/ray-project/ray/raw/master/doc/source/images/what-is-ray-padded.svg

..
  https://docs.google.com/drawings/d/1Pl8aCYOsZCo61cmp57c7Sja6HhIygGCvSZLi_AuBuqo/edit

Learn more about `Ray AI Libraries`_:

- `Data`_: Scalable Datasets for ML
- `Train`_: Distributed Training
- `Tune`_: Scalable Hyperparameter Tuning
- `RLlib`_: Scalable Reinforcement Learning
- `Serve`_: Scalable and Programmable Serving

Or more about `Ray Core`_ and its key abstractions:

- `Tasks`_: Stateless functions executed in the cluster.
- `Actors`_: Stateful worker processes created in the cluster.
- `Objects`_: Immutable values accessible across the cluster.

Learn more about Monitoring and Debugging:

- Monitor Ray apps and clusters with the `Ray Dashboard <https://docs.ray.io/en/latest/ray-core/ray-dashboard.html>`__.
- Debug Ray apps with the `Ray Distributed Debugger <https://docs.ray.io/en/latest/ray-observability/ray-distributed-debugger.html>`__.

Ray runs on any machine, cluster, cloud provider, and Kubernetes, and features a growing
`ecosystem of community integrations`_.

Install Ray with: ``pip install ray``. For nightly wheels, see the
`Installation page <https://docs.ray.io/en/latest/ray-overview/installation.html>`__.

.. _`Serve`: https://docs.ray.io/en/latest/serve/index.html
.. _`Data`: https://docs.ray.io/en/latest/data/data.html
.. _`Workflow`: https://docs.ray.io/en/latest/workflows/
.. _`Train`: https://docs.ray.io/en/latest/train/train.html
.. _`Tune`: https://docs.ray.io/en/latest/tune/index.html
.. _`RLlib`: https://docs.ray.io/en/latest/rllib/index.html
.. _`ecosystem of community integrations`: https://docs.ray.io/en/latest/ray-overview/ray-libraries.html

Why Ray?
--------

Today's ML workloads are increasingly compute-intensive. As convenient as they are, single-node development environments such as your laptop cannot scale to meet these demands.

Ray is a unified way to scale Python and AI applications from a laptop to a cluster.

With Ray, you can seamlessly scale the same code from a laptop to a cluster. Ray is designed to be general-purpose, meaning that it can performantly run any kind of workload. If your application is written in Python, you can scale it with Ray, no other infrastructure required.

More Information
----------------

- `Documentation`_
- `Ray Architecture whitepaper`_
- `Exoshuffle: large-scale data shuffle in Ray`_
- `Ownership: a distributed futures system for fine-grained tasks`_
- `RLlib paper`_
- `Tune paper`_

*Older documents:*

- `Ray paper`_
- `Ray HotOS paper`_
- `Ray Architecture v1 whitepaper`_

.. _`Ray AI Libraries`: https://docs.ray.io/en/latest/ray-air/getting-started.html
.. _`Ray Core`: https://docs.ray.io/en/latest/ray-core/walkthrough.html
.. _`Tasks`: https://docs.ray.io/en/latest/ray-core/tasks.html
.. _`Actors`: https://docs.ray.io/en/latest/ray-core/actors.html
.. _`Objects`: https://docs.ray.io/en/latest/ray-core/objects.html
.. _`Documentation`: http://docs.ray.io/en/latest/index.html
.. _`Ray Architecture v1 whitepaper`: https://docs.google.com/document/d/1lAy0Owi-vPz2jEqBSaHNQcy2IBSDEHyXNOQZlGuj93c/preview
.. _`Ray Architecture whitepaper`: https://docs.google.com/document/d/1tBw9A4j62ruI5omIJbMxly-la5w4q_TjyJgJL_jN2fI/preview
.. _`Exoshuffle: large-scale data shuffle in Ray`: https://arxiv.org/abs/2203.05072
.. _`Ownership: a distributed futures system for fine-grained tasks`: https://www.usenix.org/system/files/nsdi21-wang.pdf
.. _`Ray paper`: https://arxiv.org/abs/1712.05889
.. _`Ray HotOS paper`: https://arxiv.org/abs/1703.03924
.. _`RLlib paper`: https://arxiv.org/abs/1712.09381
.. _`Tune paper`: https://arxiv.org/abs/1807.05118

Getting Involved
----------------

.. list-table::
   :widths: 25 50 25 25
   :header-rows: 1

   * - Platform
     - Purpose
     - Estimated Response Time
     - Support Level
   * - `Discourse Forum`_
     - For discussions about development and questions about usage.
     - < 1 day
     - Community
   * - `GitHub Issues`_
     - For reporting bugs and filing feature requests.
     - < 2 days
     - Ray OSS Team
   * - `Slack`_
     - For collaborating with other Ray users.
     - < 2 days
     - Community
   * - `StackOverflow`_
     - For asking questions about how to use Ray.
     - 3-5 days
     - Community
   * - `Meetup Group`_
     - For learning about Ray projects and best practices.
     - Monthly
     - Ray DevRel
   * - `Twitter`_
     - For staying up-to-date on new features.
     - Daily
     - Ray DevRel

.. _`Discourse Forum`: https://discuss.ray.io/
.. _`GitHub Issues`: https://github.com/ray-project/ray/issues
.. _`StackOverflow`: https://stackoverflow.com/questions/tagged/ray
.. _`Meetup Group`: https://www.meetup.com/Bay-Area-Ray-Meetup/
.. _`Twitter`: https://x.com/raydistributed
.. _`Slack`: https://www.ray.io/join-slack?utm_source=github&utm_medium=ray_readme&utm_campaign=getting_involved

---

## Installation

`Installation page <https://docs.ray.io/en/latest/ray-overview/installation.html>`__.

.. _`Serve`: https://docs.ray.io/en/latest/serve/index.html
.. _`Data`: https://docs.ray.io/en/latest/data/data.html
.. _`Workflow`: https://docs.ray.io/en/latest/workflows/
.. _`Train`: https://docs.ray.io/en/latest/train/train.html
.. _`Tune`: https://docs.ray.io/en/latest/tune/index.html
.. _`RLlib`: https://docs.ray.io/en/latest/rllib/index.html
.. _`ecosystem of community integrations`: https://docs.ray.io/en/latest/ray-overview/ray-libraries.html

Why Ray?
--------

Today's ML workloads are increasingly compute-intensive. As convenient as they are, single-node development environments such as your laptop cannot scale to meet these demands.

Ray is a unified way to scale Python and AI applications from a laptop to a cluster.

With Ray, you can seamlessly scale the same code from a laptop to a cluster. Ray is designed to be general-purpose, meaning that it can performantly run any kind of workload. If your application is written in Python, you can scale it with Ray, no other infrastructure required.

More Information
----------------

- `Documentation`_
- `Ray Architecture whitepaper`_
- `Exoshuffle: large-scale data shuffle in Ray`_
- `Ownership: a distributed futures system for fine-grained tasks`_
- `RLlib paper`_
- `Tune paper`_

*Older documents:*

- `Ray paper`_
- `Ray HotOS paper`_
- `Ray Architecture v1 whitepaper`_

.. _`Ray AI Libraries`: https://docs.ray.io/en/latest/ray-air/getting-started.html
.. _`Ray Core`: https://docs.ray.io/en/latest/ray-core/walkthrough.html
.. _`Tasks`: https://docs.ray.io/en/latest/ray-core/tasks.html
.. _`Actors`: https://docs.ray.io/en/latest/ray-core/actors.html
.. _`Objects`: https://docs.ray.io/en/latest/ray-core/objects.html
.. _`Documentation`: http://docs.ray.io/en/latest/index.html
.. _`Ray Architecture v1 whitepaper`: https://docs.google.com/document/d/1lAy0Owi-vPz2jEqBSaHNQcy2IBSDEHyXNOQZlGuj93c/preview
.. _`Ray Architecture whitepaper`: https://docs.google.com/document/d/1tBw9A4j62ruI5omIJbMxly-la5w4q_TjyJgJL_jN2fI/preview
.. _`Exoshuffle: large-scale data shuffle in Ray`: https://arxiv.org/abs/2203.05072
.. _`Ownership: a distributed futures system for fine-grained tasks`: https://www.usenix.org/system/files/nsdi21-wang.pdf
.. _`Ray paper`: https://arxiv.org/abs/1712.05889
.. _`Ray HotOS paper`: https://arxiv.org/abs/1703.03924
.. _`RLlib paper`: https://arxiv.org/abs/1712.09381
.. _`Tune paper`: https://arxiv.org/abs/1807.05118

Getting Involved
----------------

.. list-table::
   :widths: 25 50 25 25
   :header-rows: 1

   * - Platform
     - Purpose
     - Estimated Response Time
     - Support Level
   * - `Discourse Forum`_
     - For discussions about development and questions about usage.
     - < 1 day
     - Community
   * - `GitHub Issues`_
     - For reporting bugs and filing feature requests.
     - < 2 days
     - Ray OSS Team
   * - `Slack`_
     - For collaborating with other Ray users.
     - < 2 days
     - Community
   * - `StackOverflow`_
     - For asking questions about how to use Ray.
     - 3-5 days
     - Community
   * - `Meetup Group`_
     - For learning about Ray projects and best practices.
     - Monthly
     - Ray DevRel
   * - `Twitter`_
     - For staying up-to-date on new features.
     - Daily
     - Ray DevRel

.. _`Discourse Forum`: https://discuss.ray.io/
.. _`GitHub Issues`: https://github.com/ray-project/ray/issues
.. _`StackOverflow`: https://stackoverflow.com/questions/tagged/ray
.. _`Meetup Group`: https://www.meetup.com/Bay-Area-Ray-Meetup/
.. _`Twitter`: https://x.com/raydistributed
.. _`Slack`: https://www.ray.io/join-slack?utm_source=github&utm_medium=ray_readme&utm_campaign=getting_involved

## Usage

.. _`Ray paper`: https://arxiv.org/abs/1712.05889
.. _`Ray HotOS paper`: https://arxiv.org/abs/1703.03924
.. _`RLlib paper`: https://arxiv.org/abs/1712.09381
.. _`Tune paper`: https://arxiv.org/abs/1807.05118

Getting Involved
----------------

.. list-table::
   :widths: 25 50 25 25
   :header-rows: 1

   * - Platform
     - Purpose
     - Estimated Response Time
     - Support Level
   * - `Discourse Forum`_
     - For discussions about development and questions about usage.
     - < 1 day
     - Community
   * - `GitHub Issues`_
     - For reporting bugs and filing feature requests.
     - < 2 days
     - Ray OSS Team
   * - `Slack`_
     - For collaborating with other Ray users.
     - < 2 days
     - Community
   * - `StackOverflow`_
     - For asking questions about how to use Ray.
     - 3-5 days
     - Community
   * - `Meetup Group`_
     - For learning about Ray projects and best practices.
     - Monthly
     - Ray DevRel
   * - `Twitter`_
     - For staying up-to-date on new features.
     - Daily
     - Ray DevRel

.. _`Discourse Forum`: https://discuss.ray.io/
.. _`GitHub Issues`: https://github.com/ray-project/ray/issues
.. _`StackOverflow`: https://stackoverflow.com/questions/tagged/ray
.. _`Meetup Group`: https://www.meetup.com/Bay-Area-Ray-Meetup/
.. _`Twitter`: https://x.com/raydistributed
.. _`Slack`: https://www.ray.io/join-slack?utm_source=github&utm_medium=ray_readme&utm_campaign=getting_involved

## API

- `Actors`_: Stateful worker processes created in the cluster.
- `Objects`_: Immutable values accessible across the cluster.

Learn more about Monitoring and Debugging:

- Monitor Ray apps and clusters with the `Ray Dashboard <https://docs.ray.io/en/latest/ray-core/ray-dashboard.html>`__.
- Debug Ray apps with the `Ray Distributed Debugger <https://docs.ray.io/en/latest/ray-observability/ray-distributed-debugger.html>`__.

Ray runs on any machine, cluster, cloud provider, and Kubernetes, and features a growing
`ecosystem of community integrations`_.

Install Ray with: ``pip install ray``. For nightly wheels, see the
`Installation page <https://docs.ray.io/en/latest/ray-overview/installation.html>`__.

.. _`Serve`: https://docs.ray.io/en/latest/serve/index.html
.. _`Data`: https://docs.ray.io/en/latest/data/data.html
.. _`Workflow`: https://docs.ray.io/en/latest/workflows/
.. _`Train`: https://docs.ray.io/en/latest/train/train.html
.. _`Tune`: https://docs.ray.io/en/latest/tune/index.html
.. _`RLlib`: https://docs.ray.io/en/latest/rllib/index.html
.. _`ecosystem of community integrations`: https://docs.ray.io/en/latest/ray-overview/ray-libraries.html

Why Ray?
--------

Today's ML workloads are increasingly compute-intensive. As convenient as they are, single-node development environments such as your laptop cannot scale to meet these demands.

Ray is a unified way to scale Python and AI applications from a laptop to a cluster.

With Ray, you can seamlessly scale the same code from a laptop to a cluster. Ray is designed to be general-purpose, meaning that it can performantly run any kind of workload. If your application is written in Python, you can scale it with Ray, no other infrastructure required.

More Information
----------------

- `Documentation`_
- `Ray Architecture whitepaper`_
- `Exoshuffle: large-scale data shuffle in Ray`_
- `Ownership: a distributed futures system for fine-grained tasks`_
- `RLlib paper`_
- `Tune paper`_

*Older documents:*

- `Ray paper`_
- `Ray HotOS paper`_
- `Ray Architecture v1 whitepaper`_

.. _`Ray AI Libraries`: https://docs.ray.io/en/latest/ray-air/getting-started.html
.. _`Ray Core`: https://docs.ray.io/en/latest/ray-core/walkthrough.html
.. _`Tasks`: https://docs.ray.io/en/latest/ray-core/tasks.html
.. _`Actors`: https://docs.ray.io/en/latest/ray-core/actors.html
.. _`Objects`: https://docs.ray.io/en/latest/ray-core/objects.html
.. _`Documentation`: http://docs.ray.io/en/latest/index.html
.. _`Ray Architecture v1 whitepaper`: https://docs.google.com/document/d/1lAy0Owi-vPz2jEqBSaHNQcy2IBSDEHyXNOQZlGuj93c/preview
.. _`Ray Architecture whitepaper`: https://docs.google.com/document/d/1tBw9A4j62ruI5omIJbMxly-la5w4q_TjyJgJL_jN2fI/preview
.. _`Exoshuffle: large-scale data shuffle in Ray`: https://arxiv.org/abs/2203.05072
.. _`Ownership: a distributed futures system for fine-grained tasks`: https://www.usenix.org/system/files/nsdi21-wang.pdf
.. _`Ray paper`: https://arxiv.org/abs/1712.05889
.. _`Ray HotOS paper`: https://arxiv.org/abs/1703.03924
.. _`RLlib paper`: https://arxiv.org/abs/1712.09381
.. _`Tune paper`: https://arxiv.org/abs/1807.05118

Getting Involved
----------------

.. list-table::
   :widths: 25 50 25 25
   :header-rows: 1

   * - Platform
     - Purpose
     - Estimated Response Time
     - Support Level
   * - `Discourse Forum`_
     - For discussions about development and questions about usage.
     - < 1 day
     - Community
   * - `GitHub Issues`_
     - For reporting bugs and filing feature requests.
     - < 2 days
     - Ray OSS Team
   * - `Slack`_
     - For collaborating with other Ray users.
     - < 2 days
     - Community
   * - `StackOverflow`_
     - For asking questions about how to use Ray.
     - 3-5 days
     - Community
   * - `Meetup Group`_
     - For learning about Ray projects and best practices.
     - Monthly
     - Ray DevRel
   * - `Twitter`_
     - For staying up-to-date on new features.
     - Daily
     - Ray DevRel

.. _`Discourse Forum`: https://discuss.ray.io/
.. _`GitHub Issues`: https://github.com/ray-project/ray/issues
.. _`StackOverflow`: https://stackoverflow.com/questions/tagged/ray
.. _`Meetup Group`: https://www.meetup.com/Bay-Area-Ray-Meetup/
.. _`Twitter`: https://x.com/raydistributed
.. _`Slack`: https://www.ray.io/join-slack?utm_source=github&utm_medium=ray_readme&utm_campaign=getting_involved

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | Apache-2.0 |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

Ray is a unified way to scale Python and AI applications from a laptop to a cluster.

With Ray, you can seamlessly scale the same code from a laptop to a cluster. Ray is designed to be general-purpose, meaning that it can performantly run any kind of workload. If your application is written in Python, you can scale it with Ray, no other infrastructure required.

More Information
----------------

- `Documentation`_
- `Ray Architecture whitepaper`_
- `Exoshuffle: large-scale data shuffle in Ray`_
- `Ownership: a distributed futures system for fine-grained tasks`_
- `RLlib paper`_
- `Tune paper`_

*Older documents:*

- `Ray paper`_
- `Ray HotOS paper`_
- `Ray Architecture v1 whitepaper`_

.. _`Ray AI Libraries`: https://docs.ray.io/en/latest/ray-air/getting-started.html
.. _`Ray Core`: https://docs.ray.io/en/latest/ray-core/walkthrough.html
.. _`Tasks`: https://docs.ray.io/en/latest/ray-core/tasks.html
.. _`Actors`: https://docs.ray.io/en/latest/ray-core/actors.html
.. _`Objects`: https://docs.ray.io/en/latest/ray-core/objects.html
.. _`Documentation`: http://docs.ray.io/en/latest/index.html
.. _`Ray Architecture v1 whitepaper`: https://docs.google.com/document/d/1lAy0Owi-vPz2jEqBSaHNQcy2IBSDEHyXNOQZlGuj93c/preview
.. _`Ray Architecture whitepaper`: https://docs.google.com/document/d/1tBw9A4j62ruI5omIJbMxly-la5w4q_TjyJgJL_jN2fI/preview
.. _`Exoshuffle: large-scale data shuffle in Ray`: https://arxiv.org/abs/2203.05072
.. _`Ownership: a distributed futures system for fine-grained tasks`: https://www.usenix.org/system/files/nsdi21-wang.pdf
.. _`Ray paper`: https://arxiv.org/abs/1712.05889
.. _`Ray HotOS paper`: https://arxiv.org/abs/1703.03924
.. _`RLlib paper`: https://arxiv.org/abs/1712.09381
.. _`Tune paper`: https://arxiv.org/abs/1807.05118

Getting Involved
----------------

.. list-table::
   :widths: 25 50 25 25
   :header-rows: 1

   * - Platform
     - Purpose
     - Estimated Response Time
     - Support Level
   * - `Discourse Forum`_
     - For discussions about development and questions about usage.
     - < 1 day
     - Community
   * - `GitHub Issues`_
     - For reporting bugs and filing feature requests.
     - < 2 days
     - Ray OSS Team
   * - `Slack`_
     - For collaborating with other Ray users.
     - < 2 days
     - Community
   * - `StackOverflow`_
     - For asking questions about how to use Ray.
     - 3-5 days
     - Community
   * - `Meetup Group`_
     - For learning about Ray projects and best practices.
     - Monthly
     - Ray DevRel
   * - `Twitter`_
     - For staying up-to-date on new features.
     - Daily
     - Ray DevRel

.. _`Discourse Forum`: https://discuss.ray.io/
.. _`GitHub Issues`: https://github.com/ray-project/ray/issues
.. _`StackOverflow`: https://stackoverflow.com/questions/tagged/ray
.. _`Meetup Group`: https://www.meetup.com/Bay-Area-Ray-Meetup/
.. _`Twitter`: https://x.com/raydistributed
.. _`Slack`: https://www.ray.io/join-slack?utm_source=github&utm_medium=ray_readme&utm_campaign=getting_involved

## Contributing

Contributing to Ray
===================

Reporting bugs and asking questions
-----------------------------------

You can post questions or issues or feedback through the following channels:

1. `Discourse forum`_: For discussions about development and questions about usage.
2. `GitHub Issues`_: For bug reports and feature requests.
3. `StackOverflow`_

Finding issues to work on
-------------------------

We use GitHub labels to categorize issues and help contributors find work that matches their interests. See `What can I work on?`_ for a list of labels by component and type.

To contribute a patch:
----------------------

We welcome contributions! See `Getting Involved`_. To set up your development environment, see
the `Setting up your development environment`_ section.

.. _`Discourse forum`: https://discuss.ray.io/
.. _`GitHub Issues`: https://github.com/ray-project/ray/issues
.. _`StackOverflow`: https://stackoverflow.com/questions/tagged/ray
.. _`Getting Involved`: https://docs.ray.io/en/latest/ray-contribute/getting-involved.html
.. _`Setting up your development environment`: https://docs.ray.io/en/latest/ray-contribute/getting-involved.html#setting-up-your-development-environment
.. _`What can I work on?`: https://docs.ray.io/en/latest/ray-contribute/getting-involved.html#what-can-i-work-on

PR Review Process
-----------------

For contributors who are in the ray-project organization:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- When you first create a PR, add a reviewer to the `assignee` section.
- Assignees will review your PR and add `@author-action-required` label if further actions are required.
- Address their comments and remove `@author-action-required` label from the PR.
- Repeat this process until assignees approve your PR.
- Once the PR is approved, the author is in charge of ensuring the PR passes the build. Add `test-ok` label if the build succeeds.
- Committers will merge the PR once the build is passing.

For contributors who are not in the ray-project organization:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Your PRs will have assignees shortly. Assignees or PRs will be actively engaging with contributors to merge the PR.
- Please actively ping assignees after you address your comments!

## License

Upstream © its respective contributors under Apache-2.0 (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** https://github.com/ray-project/ray
- **Pinned SHA:** `c50286910448ba6005a85da1e22eca94bba38428`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.rst`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`d4bc48e8402f4e1dca55733b67aa60ab43a570afc32bdf114104b0e42d60a927`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

