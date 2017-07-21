# particles-awscode

[![condensation-image][condensation-image]][condensation-url]

[![NPM][npm-image]][npm-url]
[![Gitter][gitter-image]][gitter-url]

## Summary

[Condensation][condensation-url] particles AWS CodeCommit, CodeBuild, and CodePipeline.

## Particles
* <a href="#cftemplates">cftemplates</a>
* <a href="#metadata">metadata</a>
* <a href="#parameters">parameters</a>
* <a href="#partials">partials</a>
* <a href="#resources">resources</a>
* <a href="#sets">sets</a>

## cftemplates

### Buckets

Creates source code and artifict buckets for AWS CodeBuild and AWS
CodePipeline

|region|launch|
|------|------|
|us-east-1|[![Launch Stack][launch-stack-image]][buckets-stack-us-east-1-url]|
|us-east-2|[![Launch Stack][launch-stack-image]][buckets-stack-us-east-2-url]|
|us-west-1|[![Launch Stack][launch-stack-image]][buckets-stack-us-west-1-url]|
|us-west-2|[![Launch Stack][launch-stack-image]][buckets-stack-us-west-2-url]|
|ap-northeast-1|[![Launch Stack][launch-stack-image]][buckets-stack-ap-northeast-1-url]|
|ap-southeast-1|[![Launch Stack][launch-stack-image]][buckets-stack-ap-southeast-1-url]|
|ap-southeast-2|[![Launch Stack][launch-stack-image]][buckets-stack-ap-southeast-2-url]|
|eu-central-1|[![Launch Stack][launch-stack-image]][buckets-stack-eu-central-1-url]|
|eu-west-1|[![Launch Stack][launch-stack-image]][buckets-stack-eu-west-1-url]|
|eu-west-2|[![Launch Stack][launch-stack-image]][buckets-stack-eu-west-2-url]|
|ca-central-1|[![Launch Stack][launch-stack-image]][buckets-stack-ca-central-1-url]|

### CodeBuild S3

Create a CodeBuild Project that uses S3 as the source

|region|launch|
|------|------|
|us-east-1|[![Launch Stack][launch-stack-image]][codebuilds3-stack-us-east-1-url]|
|us-east-2|[![Launch Stack][launch-stack-image]][codebuilds3-stack-us-east-2-url]|

---


## License
Apache-2.0 ©

[condensation-image]: https://raw.githubusercontent.com/SungardAS/condensation/master/docs/images/condensation_logo.png
[condensation-url]: https://github.com/SungardAS/condensation
[npm-image]: https://badge.fury.io/js/particles-awscode.svg
[npm-url]: https://npmjs.org/package/particles-awscode
[gitter-image]: https://badges.gitter.im/Join%20Chat.svg
[gitter-url]: https://gitter.im/SungardAS/condensation?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge


[launch-stack-image]: https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png
[buckets-stack-us-east-1-url]: https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=awscode-buckets&templateURL=https://s3.amazonaws.com/condensation-particles.us-east-1/particles-awscode/master/particles/cftemplates/buckets.template.json
[buckets-stack-us-east-2-url]: https://console.aws.amazon.com/cloudformation/home?region=us-east-2#/stacks/new?stackName=awscode-buckets&templateURL=https://s3.amazonaws.com/condensation-particles.us-east-2/particles-awscode/master/particles/cftemplates/buckets.template.json
[buckets-stack-us-west-1-url]: https://console.aws.amazon.com/cloudformation/home?region=us-west-1#/stacks/new?stackName=awscode-buckets&templateURL=https://s3.amazonaws.com/condensation-particles.us-west-1/particles-awscode/master/particles/cftemplates/buckets.template.json
[buckets-stack-us-west-2-url]: https://console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/new?stackName=awscode-buckets&templateURL=https://s3.amazonaws.com/condensation-particles.us-west-2/particles-awscode/master/particles/cftemplates/buckets.template.json
[buckets-stack-ap-northeast-1-url]: https://console.aws.amazon.com/cloudformation/home?region=ap-northeast-1#/stacks/new?stackName=awscode-buckets&templateURL=https://s3.amazonaws.com/condensation-particles.ap-northeast-1/particles-awscode/master/particles/cftemplates/buckets.template.json
[buckets-stack-ap-southeast-1-url]: https://console.aws.amazon.com/cloudformation/home?region=ap-southeast-1#/stacks/new?stackName=awscode-buckets&templateURL=https://s3.amazonaws.com/condensation-particles.ap-southeast-1/particles-awscode/master/particles/cftemplates/buckets.template.json
[buckets-stack-ap-southeast-2-url]: https://console.aws.amazon.com/cloudformation/home?region=ap-southeast-2#/stacks/new?stackName=awscode-buckets&templateURL=https://s3.amazonaws.com/condensation-particles.ap-southeast-2/particles-awscode/master/particles/cftemplates/buckets.template.json
[buckets-stack-eu-central-1-url]: https://console.aws.amazon.com/cloudformation/home?region=eu-central-1#/stacks/new?stackName=awscode-buckets&templateURL=https://s3.amazonaws.com/condensation-particles.eu-central-1/particles-awscode/master/particles/cftemplates/buckets.template.json
[buckets-stack-eu-west-1-url]: https://console.aws.amazon.com/cloudformation/home?region=eu-west-1#/stacks/new?stackName=awscode-buckets&templateURL=https://s3.amazonaws.com/condensation-particles.eu-west-1/particles-awscode/master/particles/cftemplates/buckets.template.json
[buckets-stack-eu-west-2-url]: https://console.aws.amazon.com/cloudformation/home?region=eu-west-2#/stacks/new?stackName=awscode-buckets&templateURL=https://s3.amazonaws.com/condensation-particles.eu-west-2/particles-awscode/master/particles/cftemplates/buckets.template.json
[buckets-stack-ca-central-1-url]: https://console.aws.amazon.com/cloudformation/home?region=ca-central-1#/stacks/new?stackName=awscode-buckets&templateURL=https://s3.amazonaws.com/condensation-particles.eu-central-1/particles-awscode/master/particles/cftemplates/buckets.template.json
[codebuilds3-stack-us-east-1-url]: https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=codebuild&templateURL=https://s3.amazonaws.com/condensation-particles.us-east-1/particles-awscode/master/particles/cftemplates/codebuild_s3.template.json
[codebuilds3-stack-us-east-2-url]: https://console.aws.amazon.com/cloudformation/home?region=us-east-2#/stacks/new?stackName=codebuild&templateURL=https://s3.amazonaws.com/condensation-particles.us-east-2/particles-awscode/master/particles/cftemplates/codebuild_s3.template.json
