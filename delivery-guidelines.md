# 📋 Milestone Delivery Guidelines

These are the guidelines to be followed for milestones submitted for evaluation in the Polkadot Fast-Grants Programme.

## ⏱️ Important Timeframes

- Each milestone is capped at **$5,000 USD**
- Milestones must be delivered within **3 months** of approval
- Milestone evaluation will be completed within **14 days**
- If a milestone is not accepted, you will have **one opportunity** to fix and resubmit within 14 days
- Partial delivery of milestones is **not acceptable**

## 📤 Submission

Please submit all your milestones via PR to this repository (https://github.com/Polkadot-Fast-Grants/delivery).

## 📝 Content

The submission should contain the following information:

- **Name of the grant project**
- **Link to the open-source code/delivery**
- **[License](#license)**
- **[Documentation](#documentation)**
- **[Formatted code](#formatted-code), according to a set of guidelines**
- **[Testing Guide](#testing-guide)**
- **A list of the [milestone deliverables](#milestone-deliverables)**
- **Any [additional information](#additional-information)**

### 📜 License

It is necessary to publish your code under an appropriate license. Check the [Open Source Initiative database](https://opensource.org/licenses) for available licenses. Apache 2.0, MIT and Unlicense are popular choices. If your delivery comprises multiple repositories, make sure to include the license in each of them.

**You should also verify that the code you submit doesn't violate any other licenses, as a failure to comply with the license of reused code will result in an immediate rejection of the milestone and termination of the grant.**

### 📚 Documentation

We value high-quality open source code, but even the most performant code is of little use if it lacks proper documentation.

We require that you document (where applicable):

- Architecture overview and individual component details
- API calls
- Algorithms and protocols that are core to your project
- Any other fundamental building blocks to your technology

Unless absolutely necessary, make the documentation public as well, ideally as part of the appropriate code repository. This will make it easier for the community to contribute to and use your project.

**Note**: Only focus on your **own** contributions. Do not write detailed explanations of already existing components, including Substrate, ink!, or IPFS.

### 💻 Formatted code

A codebase that is easy to read is also easy to use. We suggest adopting one style from Day 1 and adhering to it across the entire team. This helps to keep the commit history clean and facilitates any reviews of the introduced changes.

For **Polkadot SDK**, we strongly recommend formatting your code according to the [official guidelines](https://github.com/paritytech/polkadot-sdk/blob/master/substrate/docs/STYLE_GUIDE.md).

For **Rust**, we encourage formatting any additional support libraries or helpers by following the [Style Guidelines](https://doc.rust-lang.org/nightly/style-guide/).

For **any other** deliveries, please commit to a particular style & let us know which official guidelines you adopt.

### 🧪 Testing Guide

We require that each milestone delivery includes a comprehensive test suite, consisting of:

#### A step-by-step guide demonstrating how your code achieves the milestones

Please provide documentation on how to install, compile, run and test the deliverable(s). Make sure to include all necessary prerequisites. Common issues while replicating test results involve, among others, undocumented dependencies and version numbers, local database setups, breaking changes in the main branch since delivery or OS- and browser-specific incompatibilities.

Depending on the deliverable, this could include (but is not limited to)

- how to embed your library in another application,
- how to make example API calls to your service,
- running your web app, and
- steps to complete some desired action in your mobile app.

#### Unit tests

As with any quality software project, each logical code component should be testable.

#### Integration tests

We prefer `Dockerfile`s to avoid problems with versions and dependencies.

**Note**: If you are not delivering code as part of your project, such a test suite is not applicable. This mainly applies to projects centering on design, research or hardware. If that is the case, please provide detailed instructions on how else we can test/run/replicate your deliverable.

### 🎯 Milestone Deliverables

Please provide a list of milestone deliverables. This list should closely reflect the list of deliverables agreed on in the pull request for the grant application.

Each item in the list should include a link to the deliverable itself, e.g.:

- a Google Doc/Medium/blog link (make sure anyone with the link has View access),
- a link to a file in a public repository (include the appropriate file/folder in the link),
- a link to a specific commit, pull request or issue in a public repository.

**Please highlight anything that deviates from the contract** and include further information that you think is relevant to the deliverable, either alongside the appropriate deliverable or under [Additional Information](#additional-information).

| Number | Deliverable | Link | Notes |
| ------------- | ------------- | ------------- | ------------- |
| 0a. | License | https://github.com/.../LICENSE | ... |
| 0b. | Documentation | ... | ... |
| 0c. | Testing Guide | ... | ... |
| 1. | ... | ... | ... |
| 2. | ... | ... | ... |

### ℹ️ Additional Information

Please add any additional comments that you consider relevant for the evaluation. Remember that the Fast-Grants Programme is designed as a first step for promising projects. Consider mentioning your plans for continuing development beyond this initial funding.
