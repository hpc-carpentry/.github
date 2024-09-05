# HPC Carpentry

We are a global volunteer organization committed to
developing high-quality training materials and a modular
curriculum to educate users of high-performance computing
machinery. For more information, please visit
[HPC-Carpentry.org][hpc-home].

HPC Carpentry is not an official member of The Carpentries
yet, but we are working through the Lesson Program
Incubator to fix that. If you would like to help, please
join __#hpc-carpentry__ on the [Carpentries' Slack][slack]
and keep an eye out for our next meeting: we host two per
month, so you won't have to wait long.

We contribute lessons to the Carpentries Incubator as they
near completion, which means they can't be pinned here.
A typical HPC Carpentry workshop is stitched together from
the following resources:

0. [__hpc-carpentry/amdahl__][hpc-amdahl]

   A parallel Python program with tunable proportions of
   serial and parallel work, used in our core lessons to
   mimic a "real" parallel workload using `sleep()` instead
   of an energy-intensive task.

1. [__swcarpentry/shell-novice__][swc-shell]

   Cluster resources are often, if not always, accessed
   from a command-line interface (CLI) rather than a
   graphical user interface (GUI). Software Carpentries'
   introduction to the shell (a.k.a. "terminal,"
   a.k.a. "command line") is a prerequisite for our
   workshops.

2. [__carpentries-incubator/hpc-intro__][hpc-intro]

   A gentle introduction to workload managers (queuing
   systems) and shared computational resources, this lesson
   forms the heart of HPC Carpentry.

3. [__carpentries-incubator/hpc-workflows__][hpc-workflows]

   If you've launched one job, you might as well launch a
   thousand... but use a tool to manage your workflow!
   This lesson uses [Snakemake][snakemake] to orchestrate a
   scaling study, an important step in understanding the
   limits of any parallel application.

<!-- links -->
[hpc-amdahl]: https://github.com/hpc-carpentry/amdahl
[hpc-home]: https://www.hpc-carpentry.org
[hpc-intro]: https://github.com/carpentries-incubator/hpc-intro
[hpc-workflows]: https://github.com/carpentries-incubator/hpc-workflows
[snakemake]: https://snakemake.readthedocs.io
[slack]: https://slack-invite.carpentries.org
[swc-shell]: https://github.com/swcarpentry/shell-novice
