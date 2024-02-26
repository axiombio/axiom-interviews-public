# axiom-onsite
Resources for Axiom Member of Technical Staff onsite.

For the onsite, please bring a laptop set up for Python development. You can use your IDE of choice.

Install the environment you will use for your onsite by:
1. Install mamba or a version of conda which uses the mamba solver -- we recommend micromamba, https://mamba.readthedocs.io/en/latest/installation/micromamba-installation.html
2. Create an environment using `axiom.yml`, e.g.: `mamba env create -n axiom-onsite -f axiom.yml`
3. Install a recent version of Pytorch appropriate for your system. Some options are provided:
    - for ARM macbooks, `mamba env update -n axiom-onsite -f axiom_mac.yml`,
    - for Linux machines, `mamba env update -n axiom-onsite -f axiom_cpu.yml`,
    - for a Linux laptop with a GPU, `mamba env update -n axiom-onsite -f axiom_gpu.yml`.

