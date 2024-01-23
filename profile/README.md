![logo](https://raw.githubusercontent.com/typedfolio/.github/main/profile/assets/logo.svg)

# What is Typedfolio?

Typedfolio is a project that helps structure the content behind a portfolio website so that it can be presented using a compatible visualisation template. Typedfolio is a specification of _extensible data schemas_ and _customisable visualisation templates_. The data schemas are generalised content models for common websites, such as portfolios of researchers, developers, designers and so on. The visualisation templates help display the portfolio content, which is conformant with the data schemas, in desired visual output and interaction formats, such as website front-ends.

## Are there implementations?

Is Typedfolio simply a specification? No!

Reference implementations will be provided as listed below.

> [!WARNING]
> The following are forward-looking statements as of January 2024.

 - **Schema**: the [Sanity content management system](https://www.sanity.io/). **Template**: the [Next.js framework](https://nextjs.org/).
 - **Schema**: Python [Pydantic models](https://docs.pydantic.dev/) without any content management system. API implementation in [FastAPI](https://fastapi.tiangolo.com/). **Template**: Python [Jinja](https://jinja.palletsprojects.com/).

## When not to use Typedfolio?

Typedfolio may not be suitable when:

 - the content of the website and its desired functionality are too complex to be generalised using content models, and
 - the website or another user interface format is too simple (e.g., this README file and its visualisation as rendered Markdown) to need a content model.

# A bit more details

Explain the concept of Typedfolio with one or more diagrams.

## Let's delve a bit further

![Concept overview](https://raw.githubusercontent.com/typedfolio/.github/main/profile/assets/concept-overview.svg)

# Roadmap

Where did this project begin, where is it at and where is it going?
