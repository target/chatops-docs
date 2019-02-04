# Slack Terms of Service

[![Build Status](https://drone6.target.com/api/badges/target-chatops/chatops-docs/status.svg)](https://drone6.target.com/target-chatops/chatops-docs)

The repository contains the full terms of service users must accept before using Slack. Users will be prompted for the shortened version when first logging into Slack which will contain a link to this repository.

## Supported Platforms

* GitHub Pages
* Hugo

## Dependencies

* Hugo - v0.49

## Feature Requests/Issue Reporting

To view issues, file bug reports, and suggest new features please check out the issues tab of this repository:

[https://git.target.com/target-chatops/chatops-docs/issues](https://git.target.com/target-chatops/chatops-docs/issues)

## Usage

The `.drone.yml` file is configured that on a push/merge to the master branch, it will build the Hugo site and push it to the `gh-pages` branch in this repo. From there, magic happens, and GitHub publishes the page making it accessible at [https://pages.git.target.com/target-chatops/chatops-docs](https://pages.git.target.com/target-chatops/chatops-docs).

## Testing

This site can be spun up locally at anytime provided the dependencies specified above are installed. To build this site locally, navigate to the site directory and use `hugo serve` command. This will build the site into *Fast Render Mode* listening on `http://localhost:1313/target-chatops/chatops-docs` meaning all updates will immediately refresh the site without having to stop and start it again.

```sh
cd site
hugo serve
```

## Contributing

1. Fork the repository on Github
1. Create a named feature branch (like `add_component_x`)
1. Write your change
1. Write tests for your change (if applicable)
1. Run the tests, ensuring they all pass
1. Submit a Pull Request

## Maintainers

* Matthew.Kempfert
