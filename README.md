<p align="center">
  <img src="https://www.cyberiaonline.com/assets/splash/apple-touch-icon-precomposed.png" alt="CYBERIA online"/>
</p>

<div align="center">

<h1>cyberia instances</h1>

</div>

**Instance data and deployment manifests for the Cyberia MMO Runtime.**

This repository contains deployable **Cyberia instances** and the manifests required to deploy them into the **engine-cyberia** runtime.

Each instance is a self-contained world package that includes the data required to render, simulate, and interact with a region of the Cyberia universe. Depending on the project, an instance may contain:

* maps and world topology
* object layers
* NPCs and dialogues
* quests and progression
* skills and gameplay configuration
* saga definitions
* sprite atlases and render frames
* environment configuration
* IPFS content references
* bootstrap and seed data

Deployment manifests define how an instance is provisioned by the runtime, including the instance identity, content sources, environment variables, storage configuration, networking parameters, and other deployment metadata.

The **engine-cyberia** runtime consumes this repository as the authoritative source for world content and instance configuration during deployment and bootstrap.

Cyberia is an MMORPG framework built on top of the **Underpost Platform**, providing an authoritative server architecture for persistent multiplayer worlds with support for content distribution, and modular deployments.

See the [engine-cyberia](https://github.com/underpostnet/engine-cyberia.git) repository for the runtime, CLI, deployment tooling, and complete development workflow.
