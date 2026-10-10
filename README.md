# ContacSpec.org

[ContacSpec.org] is part of the [SocialSpec.org] portfolio of specifications for social engagement on the world wide web.
It is build on open standards.

## The Specification

* Create a `contact.vcf` file (vCard 3.0 or newer)
* Publish it at `/.well-known/contact.vcf`
* Allow [CORS] requests

Learn more at https://contactspec.org

## The Website

This repository contains the source code for https://contactspec.org. 
This website is built using the HyperTexting static-site generator. 
Please visit https://hypertexting.dev to learn more.

## Contributing

1.  **GitHub Stars**

    The easiest way to contribute to [contactspec.org] is to star the repository:

    https://github.com/socialspec/contactspec.org

1.  **Adoption!**

    The best way to help contribute to [contactspec.org] is to implement support for the specification. 
    If you do, please let us know: info@socialspec.org

1.  **Comment on the RFC**

    You can also help contribute to [contactspec.org] by liking or comment on the RFC:

    https://github.com/socialspec/contactspec.org/issues/1 (coming soon)

1.  **Submit PRs**

    Did you notice a typo or have a suggestion for how to improve [contactspec.org]? 
    Pull requests from humans are always welcome!

    Download the [HyperTexting CLI] (`hyperctl`), then run: 

    ```
    mkdir contactspec.org
    cd contactspec.org
    git clone https://github.com/socialspec/contactspec.org
    hyperctl server --port 8080
    ```


<!-- Links -->
[socialspec.org]: https://socialspec.org
[followspec.org]: https://followspec.org
[aboutspec.org]: https://aboutspec.org
[contactspec.org]: https://contactspec.org
[CORS]: https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/CORS
[HyperTexting CLI]: https://hypertexting.dev
