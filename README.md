# ReFM Project Page

This directory contains the website for **ReFM: Retargeting with Energy Flow and Motion Semantics**.

ReFM is a source-mesh-agnostic motion-retargeting framework. Given source motion and skeleton information, plus a target skeleton and mesh, it produces semantically faithful character motion without requiring a source mesh or ground-truth target motion. Its three-stage pipeline:

1. canonicalizes global yaw,
2. encodes character-invariant motion semantics with contrastive learning, and
3. refines an initial copy retarget using an energy-guided flow that balances self-penetration, semantic preservation, temporal smoothness, and copy fidelity.

On the 308-pair canonicalized Mixamo GT benchmark, ReFM-copy obtains the lowest evaluated penetration score (0.1285) and a 6.60% penetration gain over the copy baseline.


## Acknowledgment

The page is based on the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template), which is adapted from [Nerfies](https://nerfies.github.io/).
