# opensource.microsoft.com

The `opensource.microsoft.com` web site is a simple, factual web site sharing information about Microsoft's
open source program, the open source ecosystem that we support, and opportunities to get involved and
learn more.

The site is generated by Jekyll, a popular open source static site generator implemented in Ruby (Jekyll
powers GitHub Pages). It is deployed to Microsoft Azure and an Azure Kubernetes Service (AKS) cluster, as
well as Azure Front Door and the Azure CDN. Dynamic data is retrieved through a Node.js backend.

Launched in August 2020, replacing a more antiquated site, we expect that updates and contributions to
the site will be to feature new and interesting projects, update a curated blog post list, and improve
program and ecosystem content pages. We do not currently have plans to add drastically different sections
to the site or to be the "source of truth" for blog posts or other content.

The primary site navigation is:

- Homepage overview
- Get involved
- Projects
- Ecosystem
- Our program
- Jobs (an external link)
- Blog (an external link)
- Secondary content includes hosting the Code of Conduct that Microsoft projects use and a "thank you" page regarding the open source powering the site.

# Contributing

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

Thanks for your interest in contributing to the https://opensource.microsoft.com web site. Please make sure to 
communicate any contribution ideas as an issue _before_ starting a pull request. We'd love to see how to best involve you.

We're happy that this site is open source (because an open source site should be open source). However,
as a public-facing site hosted at `microsoft.com`, we're likely not able to accept general contributions to this site, so your
pull request may be closed and not merged, even if it's great, and we may not be able to provide complete context for
any such decision. Thanks for your understanding.

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

## Jekyll site install

Ensure you have a working copy of Ruby.

```sh
bundle
bundle exec jekyll serve
```

# Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
