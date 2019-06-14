# <a href='https://www.apollographql.com/'><img src='https://user-images.githubusercontent.com/841294/53402609-b97a2180-39ba-11e9-8100-812bab86357c.png' height='100' alt='Apollo Feature Requests'></a>

## Apollo Feature Requests

This repository is used to track [Apollo Client](https://github.com/apollographql/apollo-client) and [React Apollo](https://github.com/apollographql/react-apollo) feature requests and discussions. Click [here](https://github.com/apollographql/apollo-feature-requests/issues/new) to open a new feature request.

> **Note:** Apollo Client / React Apollo bugs are tracked in the each project's GitHub issue tracker:
> 
> - [Apollo Client issue tracker](https://github.com/apollographql/apollo-client/issues)
> - [React Apollo issue tracker](https://github.com/apollographql/react-apollo/issues)

### Suggesting Features

Most of the features in Apollo came from suggestions by you, the community! We welcome any ideas about how to make Apollo better for your use case. Unless there is overwhelming demand for a feature, it might not get implemented immediately, but please include as much information as possible that will help people have a discussion about your proposal:

1. **Use case:** What are you trying to accomplish, in specific terms? Often, there might already be a good way to do what you need and a new feature is unnecessary, but it’s hard to know without information about the specific use case.

2. **Could this be a plugin?** In many cases, a feature might be too niche to be included in the core of a library, and is better implemented as a companion package. If there isn’t a way to extend the library to do what you want, could we add additional plugin APIs? It’s important to make the case for why a feature should be part of the core functionality of the library.

3. **Is there a workaround?** Is this a more convenient way to do something that is already possible, or is there some blocker that makes a workaround unfeasible?

Please keep in mind that feature requests should be well specified and unambiguous, to have the greatest chance of being worked on by a contributor.

The [issues](https://github.com/apollographql/apollo-feature-requests/issues/) area of this repo should be used to discuss new features and possible implementation designs. You can show your support for (or against!) features by using GitHub reactions, or by adding meaningful details which help the feature definition become more clear. Please do not comment with "+1" as it creates a lot of noise (e-mails, notifications, etc.).

Please refrain from submitting a pull request in the [Apollo Client](https://github.com/apollographql/apollo-client) or [React Apollo](https://github.com/apollographql/apollo-client) repos, to implement a proposed feature, until there is consensus that it should be included. This way, you can avoid putting in work that can’t be merged in. Once there is a consensus on the need for a new feature, proceed as listed in the [CONTRIBUTING doc](https://github.com/apollographql/apollo-client/blob/master/CONTRIBUTING.md#big-prs).

### Feature Request Issue Triage

1. For reasons described [above](#suggesting-features), we would prefer features to be built as separate packages. If the feature can clearly be built as a package, explain this to the requester and close the issue.
> - If the feature could be built as a package and serves a particular need, encourage the user to contribute it themselves.
>- If the underlying issue could be better solved by existing technology, encourage them to seek help in the [Slack channel](https://www.apollographql.com/slack) or on [Stack Overflow](http://stackoverflow.com/questions/tagged/apollo).
2. If it's not possible to build the feature as a package (as you identified in step 1), explore whether creating hooks in core would make it possible to do so. If it would, redefine the issue as a request to create those hooks.
3. Work with the requester and others in the community to build a clear specification for the feature and update the issue description accordingly.
4. Finally, add the `confirmed` label.

Core contributors may add the `help-wanted` label to feature requests. This indicates the feature is aligned with the project roadmap and a high-quality pull request will almost certainly be merged.

### Resources

- [Main Apollo Client repo](https://github.com/apollographql/apollo-client)
- [Main React Apollo repo](https://github.com/apollographql/react-apollo)
- [Contribution guidelines](https://github.com/apollographql/apollo-client/blob/master/CONTRIBUTING.md)
