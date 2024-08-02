Hi!

Gstack is a French consultancy, specialized in several Cloud techs:

- Platforms: [Kubernetes][k8s] & [Cloud Foundry][cf].
- CI/CD: ✈️ [Concourse][concourse], [GitLab][gitlab], [GitHub Actions][gh_actions],
  🗡️ [Dagger][dagger].
- Cross-Cloud automation: [Bosh][bosh].

We contribute to Bosh souce code and documentation, being active member of the
[Foundational Infrastructure WG][fiwg], a [working groups][fiwg] of the Cloud
Foundry foundation.

Talks:

- [Authoring a BOSH Release Is Actually Easy!][bosh_release_authoring], a
  short walk-thru the whole process of authoring a Bosh release, to that the
  Bosh robot can handle your clusterd cloud workloads for you (it's a lighting
  talk!)
- [Project 42 - Making CI/CD a First Class Citizen in Cloud Foundry][prj42_long],
  presenting a project done for the hachathon (that we won!) at Cloud Foundry
  Summit in Philadelphia (also the short [submission talk][prj42_short])
- [Deploy like a Boss with BOSH][bosh_intro], an introduction to BOSH, that hs
  been the base of the Bosh trainings we've built and delivered later.

[k8s]: https://kubernetes.io
[cf]: https://www.cloudfoundry.org
[concourse]: https://concourse-ci.org
[gitlab]: https://about.gitlab.com
[gh_actions]: https://github.com/features/actions
[dagger]: https://dagger.io
[bosh]: https://bosh.io

[cf_wg]: https://www.cloudfoundry.org/working-groups/
[fiwg]: https://github.com/cloudfoundry/community/blob/main/toc/working-groups/foundational-infrastructure.md

[bosh_release_authoring]: https://youtu.be/pVxKltt4egI
[prj42_long]: https://youtu.be/-GVv-o6LLzc
[prj42_short]: https://youtu.be/IoyB2O4BSTc
[bosh_intro]: https://youtu.be/CLN84B-HnmU?t=10


Go checkout some of our hottest projects:

- [Kubeadm Bosh release][kubeadm_boshrelease] (yet private, contact us), a
  scalable Kubernetes bosh release with all Day-2 operations automatized:
  config updates, OS upgrades, Kube versions upgrades, scale up/down of VMs or
  disks, scale out/in for worker nodes nodes, with full flexibility to scale
  control-plane nodes to HA (3 or 5 nodes) or back to non-HA (1 node).
- [GitLab Bosh release][gk_gitlab_boshrelease] (yet private, contact us), a
  top notch GitLab deployment, ready to scale horizontally, properly
  leveraging a cluster of Praefect proxy in front of a Gitaly cluster, and
  using the efficient and scalable stateless Golang-based SSH proxy.
- Turbine ([CLI][turbine_cli]), a framework that helps structuring coordinated
  and modularized Bosh deployments, for managing a Cloud Foundry or Concourse
  platform.
- [Concourse Turbine][concourse_turbine], a Turbine project for deploying a
  top notch Concourse cluster, with full encryption.

Maintained Bosh Releases:

- [k8s Bosh release][k8s_boshrelease], an evolution of James Hunt's brilliant
  k8s Bosh release, for deploying and managing Kubernetes clusters.
- [Træfik Bosh release][traefik_boshrelease], a Traefik v1 Bosh release,
  cupporting cluster mode (using Consul) out of the box.
- [Consul Bosh release][gk_consul_boshrelease], a modern Consul Bosh release,
  leveraging recent Bosh features.
- [Kong Bosh release][gk_kong_boshrelease], a full-fledged Bosh release for
  deploying and managing cluster of Kong API Gateway instance, also providing
  an deployment for the Konga web UI.

Maintaned Concourse resources:

- [cf-community/github-pr-resource](https://github.com/cloudfoundry-community/github-pr-resource)
- [cf-community/slack-notification-resource](https://github.com/cloudfoundry-community/slack-notification-resource)
- [cf-community/bosh-config-resource](https://github.com/cloudfoundry-community/bosh-config-resource)
- [keyval-resource](https://github.com/gstackio/keyval-resource)
- [openssl-source-code-resource](https://github.com/gstackio/openssl-source-code-resource)

Maintained Concourse pipeline templates:

- https://github.com/gstackio/pipeline-templates, now moved to CF community

[k8s_boshrelease]: https://github.com/gstackio/k8s-boshrelease
[turbine_cli]: https://github.com/gstackio/turbine-cli
[concourse_turbine]: https://github.com/gstackio/concourse-turbine
[gk_consul_boshrelease]: https://github.com/gstackio/gk-consul-boshrelease
[traefik_boshrelease]: https://github.com/gstackio/traefik-boshrelease
[gk_kong_boshrelease]: https://github.com/gstackio/gk-kong-boshrelease
