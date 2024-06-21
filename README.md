# Polkadot Tooling Collective (PoToC)

This repository is used to coordinate the Polkadot Tooling Collective and deliver on its [constitution](https://github.com/polkadot-tooling-collective/constitution). It provides the current list of members, applicants and the Mission List.

## Structure

Most files are managed with the [collective-cli](https://github.com/super-collective/collective-cli) to keep all files neatly sorted and in a machine-readable format. This allows for auditability and better accountability of past decisions.

The four main parts are:
- [`mission_list.md`](./mission_list.md): All projects that PoToC maintains.
- [`members.md`](./members.md): All members of the collective.
- [`join_request`](./join_request/): All accepted requests for admission.
- `work_evidence`: Proof of done work by members.

All the structural decisions here are made in line with the guidelines of the [super-collective](https://github.com/super-collective) to act as Proof-of-Concept for it.

## Mission List

Provides the projects that PoToC promises to maintain. This is done to have maximum clarity on scope of what PoToC should be doing
with their funding. Find it in the [mission_list.md](mission_list.md)

## How to Join (Request for Admission)

> *NOTE* At the current time we only accept accomplished developers. Please refrain from applying if you did not contribute to the mission of PoToC in the past.

To join PoToc, please fork this repository and create a Request for Admission, following [this](https://github.com/super-collective/collective-cli/blob/7d4a1a785396a2e29199a3d16115b67a4e8d9054/schema/potoc.join_request.schema.json) format. You can also use the [CLI](https://github.com/super-collective/collective-cli?tab=readme-ov-file#creating-a-request-for-admission---interactive) to create the file. In either case, please read the [constitution](https://github.com/polkadot-tooling-collective/constitution) and acknowledge the mission of PoToC.

Then please open a Merge Request to this repository to add your request file. It should be in the `join_request` folder. See the application from [Nikos](https://github.com/polkadot-tooling-collective/collective/pull/1) as example. Once that is merged, you are a member of PoToC!  An entry in the `member` folder will be created for you to reflect this.

### Example

To give you an idea of what it could look like, here is an example of a request for admission. Sure there should be a bit more content, but you get the idea.

```yaml
collective: Potoc
member:
  name: Max Power
  address: 12xToKVweE2YHRj818MZsiT7kCZpx5n8qdvz7wKMvwJuJE3T
  github: mpower
  matrix: "neo:matrix.org"
  rank: 0
date: 2024-04-09
about: "My name was originally Homer Simpson, but now ..."
motivation: "I want to keep building Polkadot tooling, because ..."
evidence:
- title: PolkadotJS
  category: d_app_tooling
  tasks:
  - title: Creation and Maintenance
    links:
    - https://github.com/polkadot-js/apps
- title: SrTool
  category: core_tooling
  tasks:
  - title: Creation and Maintenance
    links:
    - https://github.com/paritytech/srtool
```

## Work Evidence

PoToC promises to the Polkadot Tokenholders to regularly post evidence of its past work. This is done in a machine readable format following [this](https://github.com/super-collective/collective-cli/blob/1d019d4dd5120db8f8517df7bfb64d19eac74b69/schema/evidence_report.json) yaml schema. Again, it is possible to create, check and render these files. Please refer to the [collective-cli](https://github.com/super-collective/collective-cli?tab=readme-ov-file#creating-evidence---interactive) repo for more info.
