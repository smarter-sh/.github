# The Smarter Project

[![OpenAI](https://a11ybadges.com/badge?logo=openai)](https://platform.openai.com/)
[![LangChain](https://a11ybadges.com/badge?text=LangChain&badgeColor=0834ac)](https://www.langchain.com/)
[![Python](https://a11ybadges.com/badge?logo=python)](https://www.python.org/)
[![Django](https://a11ybadges.com/badge?logo=django)](https://www.djangoproject.com/)
[![React](https://a11ybadges.com/badge?logo=react)](https://react.dev/)
[![Golang](https://a11ybadges.com/badge?logo=go)](https://go.dev/)
[![Terraform](https://a11ybadges.com/badge?logo=terraform)](https://www.terraform.io/)
[![Kubernetes](https://a11ybadges.com/badge?logo=kubernetes)](https://kubernetes.io/)

[![hack.d Lawrence McDaniel](https://img.shields.io/badge/hack.d-Lawrence%20McDaniel-orange.svg)](https://lawrencemcdaniel.com)

**Smarter is an enterprise-class platform for designing and managing chat solutions. Think of Smarter as the 'Redhat Linux' of chat.**

Info: [Kent Fuka](mailto:kent@querium.com)

Smarter gives prompt engineering teams an intuitive workbench approach to designing, prototyping, testing, deploying and managing powerful chat solutions for common corporate use cases including customer sales support, vendor/supplier management, human resources, and more. Smarter is compatible with a wide variety of chatbot UI front ends for technology ecosystems such as NPM, Wordpress, Squarespace, Drupal, Office 365, Sharepoint, .Net, Netsuite, salesforce.com, and SAP. It is developed to support prompt engineering teams working in large organizations. Accordindly, Smarter provides common enterprise features such as security, accounting cost codes, and audit capabilities.

Smarter is LLM provider-agnostic, and provides seamless integrations to a continuously evolving list of value added services for security management, prompt content moderation, audit, cost accounting, and workflow management. It can be used as a pay-as-you-go, platform as a service, or, installed in your own AWS cloud account and supported by Querium's professional services team. It can also be installed on-premise in a hybrid model.

Smarter is cost effective when running at scale. It is extensible and architected on the philosophy of a compact core that does not require customization nor forking. It is horizontally scalable. It is natively multi-tenant, and can be installed alongside your existing systems. The principal technologies in the Smarter platform stack include:

- Ubuntu Linux
- Docker/Kubernetes/Helm
- MySQL
- Redis
- Terraform/awscli/Boto3
- Python/Django
- Pytest/Pluggy
- Langchain
- Pydantic
- ReactJS/Bootstrap
- Go lang
- GitHub Actions

## Designed by and for prompt engineers

Smarter provides design teams with a web console, and a convenient yaml manifest-based command-line interface for Windows, macOS, and Linux.

![Smarter Stack](https://cdn.platform.smarter.sh/github.com/smarter-sh/stack.png?)

### Plugin Architecture

Smarter features a unique Plugin architecture for extending the knowledge domain of any LLM aimed at generative AI text completions. Smarter Plugins are uncharacteristically accurate, highly cost effective, and have been designed around the needs of enterprise customers. Its unique 'selector' feature gives prompt engineers a sosphisticated strategy for managing when and how LLM's can make use of Smarter Plugin's powerful data integrations, which include the following:

- **Static**: an easy to implement scheme in which your private data is simply included in yaml Plugin manifest file.
- **Sql**: a flexible parameterized manifest scheme that exposes query parameters to the LLM, enabling it to make precise requests via proxy to your corporate databases.
- **Rest Api**: Similarly, you can also configure proxy connections to your Rest Api's, enabling the LLM to make precise requests to an unlimited range of private data sources.

### Yaml Manifest Resource Management

Smarter brings a [yaml-based manifest file](./smarter/smarter/apps/plugin/data/sample-plugins/example-configuration.yaml) approach to prompt engineering, originally inspired by the [kubectl](https://kubernetes.io/docs/reference/kubectl/) command-line interface for [Kubernetes](https://kubernetes.io/).
