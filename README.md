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
|us-east-1|[![Launch Stack][launch-stack-image]][launch-stack-us-east-1-url]|
|us-east-2|[![Launch Stack][launch-stack-image]][launch-stack-us-east-2-url]|

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
[launch-stack-us-east-1-url]: https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=awscode-buckets&templateURL=https://s3.amazonaws.com/condensation-particles.us-east-1/particles-awscode/master/particles/cftemplates/buckets.template.json
[launch-stack-us-east-2-url]: https://console.aws.amazon.com/cloudformation/home?region=us-east-2#/stacks/new?stackName=awscode-buckets&templateURL=https://s3.amazonaws.com/condensation-particles.us-east-2/particles-awscode/master/particles/cftemplates/buckets.template.json
