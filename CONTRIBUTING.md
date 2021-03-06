# Contributing to New Relic OpenTracing Tracer Plugin
Thanks for your interest in contributing to the New Relic OpenTracing Tracer Plugin! We look forward to engaging with you.

## How to Contribute
* Read this CONTRIBUTING file
* Read our [Code of Conduct](CODE_OF_CONDUCT.md)
* Submit a [pull request](#pull-request-guidelines) or [issue](#filing-issues--bug-reports). For pull requests, please also:
    * Ensure the [test suite passes](#testing-guidelines).
    * Sign the [Contributor Licensing Agreement](#contributor-license-agreement-cla), if you haven't already done so. (You will be prompted if we don't have a signed CLA already recorded.)
    
## How to Get Help or Ask Questions
Do you have questions or are you experiencing unexpected behaviors after modifying this Open Source Software? Please engage with the “Build on New Relic” space in the [Explorers Hub](https://discuss.newrelic.com/c/build-on-new-relic/Open-Source-Agents-SDKs), New Relic’s Forum. Posts are publicly viewable by anyone, please do not include PII or sensitive information in your forum post.

## Contributor License Agreement ("CLA")
We'd love to get your contributions to improve New Relic OpenTracing Tracer Plugin! Keep in mind when you submit your pull request, you'll need to sign the CLA via the click-through using CLA-Assistant. You only have to sign the CLA one time per project.
To execute our corporate CLA, which is required if your contribution is on behalf of a company, or if you have any questions, please drop us an email at open-source@newrelic.com. 

## Filing Issues & Bug Reports
We use GitHub issues to track public issues and bugs. If possible, please provide a link to an example app or gist that reproduces the issue. When filing an issue, please ensure your description is clear and includes the following information.
* Project version (ex: 1.4.0)
* Custom configurations (ex: flag=true)
* Any modifications made to the New Relic OpenTracing Tracer Plugin

#### A note about vulnerabilities  
New Relic is committed to the security of our customers and their data. We believe that providing coordinated disclosure by security researchers and engaging with the security community are important means to achieve our security goals.

If you believe you have found a security vulnerability in this project or any of New Relic's products or websites, we welcome and greatly appreciate you reporting it to New Relic through [HackerOne](https://hackerone.com/newrelic).

## Setting Up Your Environment
This Open Source Software can be used in a large number of environments, all of which have their own quirks and best practices. As such, while we are happy to provide documentation and assistance for unmodified Open Source Software, we cannot provide support for your specific environment.

If you can build the New Relic OpenTracing Tracer Plugin, you can develop it!

## Pull Request Guidelines
Before we can accept a pull request, you must sign our [Contributor Licensing Agreement](#contributor-license-agreement-cla), if you have not already done so. This grants us the right to use your code under the same Apache 2.0 license as we use for this project in general.

Minimally, the [test suite](#testing-guidelines) must pass for us to accept a PR. Ideally, we would love it if you also added appropriate tests if you're implementing a feature!

## Coding Style Guidelines
`TODO: Project doesn't currently have code formatting configured`

Our code base is formatted according to the [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html).

The project is configured to use the [google-java-format-gradle-plugin](https://github.com/sherter/google-java-format-gradle-plugin) which can be utilized as follows:  

* Execute the task `googleJavaFormat` to format all `*.java` files in the project:

`./gradlew goJF`

* Execute the task `verifyGoogleJavaFormat` to verify that all `*.java` files are formatted properly:

`./gradlew verGJF`

## Testing Guidelines
The New Relic OpenTracing Tracer Plugin comes with tests in:.

`TODO: Add tests`

You can run all of these tests, and verify that your code is formatted correctly by running

`./gradlew check`

## License
By contributing to the Java New Relic OpenTracing Tracer Plugin, you agree that your contributions will be licensed under the [License file](LICENSE.md)
in the root directory of this source tree.