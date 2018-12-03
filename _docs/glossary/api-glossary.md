---
title: API glossary
permalink: /api-glossary.html
keywords:
course: "Documenting REST APIs"
weight: 10.5
sidebar: docapis
section: glossary
path1: /glossary.html
---

API
: Application Programming Interface. Enables different systems to interact with each other programmatically. Two types of APIs are web services and library-based APIs. See [What is a REST API?](docapis_what_is_a_rest_api.html).

API Console
: Renders an interactive display for the RAML spec. Similar to Swagger UI, but for [RAML](https://idratherbewriting.com/learnapidoc/pubapis_raml.html#apiconsole). See [github.com/mulesoft/api-console](https://github.com/mulesoft/apiconsole).

APIMATIC
: Supports most REST API description formats (OpenAPI, RAML, API Blueprint, etc.) and provides SDK code generation, conversions from one spec format to another, and many more services. APIMATIC "lets you define APIs and generate SDKs for more than 10 languages." For example, you can automatically convert Swagger 2.0 to 3.0 using the [API Transformer](https://apimatic.io/transformer) service on this site. See [https://apimatic.io/](https://apimatic.io/) and read their [documentation](https://docs.apimatic.io/).

API Transformer
: A cross-platform service provided by APIMATIC that will automatically convert your specification document from one format or version to another. See [apimatic.io/transformer](https://apimatic.io/transformer).

Apiary
: Platform that supports the full life-cycle of API design, development, and deployment. For interactive documentation, Apiary supports the API Blueprint specification, which similar to OpenAPI or RAML but includes more Markdown elements. It also supports the OpenAPI specification now too. See [apiary.io](https://apiary.io).

API Blueprint
: The API Blueprint spec is an alternative specification to OpenAPI or RAML. API Blueprint is written in a Markdown-flavored syntax. See [API Blueprint](https://idratherbewriting.com/learnapidoc/pubapis_api_blueprint.html) in this course, or go to [API Blueprint's homepage](https://apiblueprint.org/) to learn more.

Apigee
: Similar to Apiary, Apigee provides services for you to manage the whole lifecycle of your API. Specifically, Apigee lets you "manage API complexity and risk in a multi- and hybrid-cloud world by ensuring security, visibility, and performance across the entire API landscape." Supports the OpenAPI spec. See [apigee.com](https://apigee.com/api-management/).

Asciidoc
: A lightweight text format that provides more semantic features than Markdown. Used in some static site generators, such as [Asciidoctor](http://asciidoctor.org/) or [Nanoc](https://nanoc.ws/). See [http://asciidoc.org/](http://asciidoc.org/).

branch
: In Git, a branch is a copy of the repository that is often used for developing new features. Usually you work in branches and then merge the branch into the master branch when you're ready to publish. If you're editing documentation in a code repository, developers will probably have you work in a branch to make your edits. The developers will then either merge your branch into the master when ready, or you might submit a pull request to merge your branch into the master. See [git-branch](https://git-scm.com/docs/git-branch).

clone
: In Git, clone is the command used to copy a repository in a way that keeps it linked to the original. The first step in working with any repository is to clone the repo locally. Git is a distributed version control system, so everyone working in it has a local copy (clone) on their machines. The central repository is referred to as the origin. Each user can pull updates from origin and push updates to origin. See [git-clone](https://git-scm.com/docs/git-clone).

commit
: In Git, a commit is when you take a snapshot of your changes to the repo. Git saves the commit as a snapshot in time that you can revert back to later if needed. You commit your changes before pulling from origin or before merging your branch within another branch. See [git-commit](https://git-scm.com/docs/git-commit).

CRUD
: Create, Read, Update, Delete. These four programming operations are often compared to POST, GET, PUT, and DELETE with REST API operations.

curl
: A command line utility often used to interact with REST API endpoints. Used in documentation for request code samples. curl is usually the default format used to display requests in API documentation. See [curl](https://curl.haxx.se/). Also written as curl. See [Make a curl call](docapis_make_curl_call.html) and [Understand curl more](docapis_understand_curl.html).

endpoint
: {{site.data.apirefsections.endpoints_and_methods.def}} See [Endpoints and methods](docapis_resource_endpoints.html).

Git
: Distributed version control system commonly used when interacting with code. GitHub uses Git, as does BitBucket and other version control platforms. Learning Git is essential for working with developer documentation, since this is the most common way developers share, review, collaborate, and distribute code. See [https://git-scm.com/](https://git-scm.com/).

GitHub
: A platform for managing Git repositories. Used for most open source projects. You can also publish documentation using GitHub, either by simply uploading your non-binary text files to the repo, or by auto-building your Jekyll site with GitHub Pages, or by using the built-in GitHub wiki. See [GitHub wikis](pubapis_github_wikis.html) in this course as well as on [pages.github.com/](https://pages.github.com/).

git repo
: A tool for consolidating and managing many smaller repos with one system. See [git-repo](https://code.google.com/archive/p/git-repo/).

HAT
: Help Authoring Tool. Refers to the traditional help authoring tools (RoboHelp, Flare, Author-it, etc.) used by technical writers for documentation. Tooling for API docs tend to use [Docs as code tools](pubapis_docs_as_code.html) more than [HATs](pubapis_docs_as_code.html#hats).

HATEOS
: Stands for Hypermedia as the Engine of Application State. Hypermedia is one of the characteristics of REST that is often overlooked or missing from REST APIs. In API responses, responses that span multiple pages should provide links for users to page to the other items. See [HATEOS](https://en.wikipedia.org/wiki/HATEOAS).

Header parameters
: Parameters that are included in the request header, usually related to authorization.

Hugo
: A static site generator that uses the Go programming language as its base. Along with Jekyll, Hugo is among the top 5 most popular static site generators. Hugo is probably the fastest site generator available. Speed matters as you scale the number of documents in your project beyond several hundred. See [https://gohugo.io/](https://gohugo.io/). For more about static site generators, see [Static site generators](pubapis_static_site_generators.html).

JSON
: JavaScript Object Notation. A lightweight syntax containing objects and arrays, usually used (instead of XML) to return information from a REST API. See [Analyze the JSON response](docapis_analyze_json.html) in this course and [http://www.json.org/](http://www.json.org/)

Mercurial
: An distributed revision control system, similar to Git but not as popular. See [https://www.mercurial-scm.org/](https://www.mercurial-scm.org/).

method
: The allowed operation with a resource in terms of GET, POST, PUT, DELETE, and so on. These operations determine whether you're reading information, creating new information, updating existing information, or deleting information. See [Endpoints and methods](docapis_resource_endpoints.html).

Mulesoft
: Similar to Apiary or Apigee, Mulesoft provides an end-to-end platform for designing, developing, and distributing your APIs. For documentation, Mulesoft supports [RAML](https://idratherbewriting.com/learnapidoc/pubapis_raml.html). See [https://www.mulesoft.com/](https://www.mulesoft.com/).

OAS
: Abbreviation for OpenAPI specification.

OpenAPI
: The official name for the OpenAPI specification. The OpenAPI specification provides a set of properties that can be used to describe your REST API. When valid, the specification document can be used to create interactive documentation, generate client SDKs, run unit tests, and more. See [https://github.com/OAI/OpenAPI-Specification](https://github.com/OAI/OpenAPI-Specification). Now under the Open API Initiative with the Linux Foundation, the OpenAPI specification aims to be vendor neutral. For details in this course, see [Introduction to the OpenAPI specification and Swagger](pubapis_swagger_intro.html).

OpenAPI contract:
: Synonym for OpenAPI specification document.

OpenAPI specification document
: The specification document, usually created manually, that defines the blueprints that developers should code the API to. The contract aligns with a "spec-first" or "spec-driven development" philosophy. The contract essentially acts like the API requirements for developers. See [this blog post/podcast](https://idratherbewriting.com/2015/10/12/spec-driven-design-podcast-michael-stowe/) for details on spec-first development.

OpenAPI Initiative
: The governing body that directs the OpenAPI specification. Backed by the Linux Foundation. See [https://www.openapis.org/](https://www.openapis.org/).

parameter
: {{site.data.apirefsections.parameters.def}} See [Parameters](docapis_doc_parameters.html) for more details.

Path parameters
: Parameters that appear within the path of the endpoint, before the query string (`?`). These are usually set off within curly braces. See [Parameters](docapis_doc_parameters.html) for more details.

Pelican
: A static site generator based on Python. See [https://github.com/getpelican/pelican](https://github.com/getpelican/pelican). For more about static site generators, see [Static site generators](pubapis_static_site_generators.html).

Perforce
: Revision control system often used before Git became popular. Often configured as centralized repository instead of a distributed repository. See [Perforce](https://en.wikipedia.org/wiki/Perforce_Helix).

pull
: In Git, when you pull from origin (the master location where you cloned the repo), you get the latest updates from origin onto your local system. When you run `git pull`, Git tries to automatically merge the updates from origin into your own copy. If the merge cannot happen automatically, you might see merge conflicts. See [git-pull](https://git-scm.com/docs/git-pull).

Pull Request
: A request from an outside contributor to merge a cloned branch back into the master branch. The pull request workflow is commonly used with open source projects, because developers outside the team will not usually have contributor rights to merge updates into the repository. GitHub has a great interface for making and processing pull requests. See [Pull Requests](https://www.atlassian.com/git/tutorials/making-a-pull-request).

push
: In Git, when you want to update the origin with the latest updates from your local copy, you run `git push`. Your updates will bring origin back into sync with your local copy. See [https://git-scm.com/docs/git-push](https://git-scm.com/docs/git-push).

Query string parameters
: Parameters that appear in the query string of the endpoint, after the `?`. See [Parameters](docapis_doc_parameters.html) for more details.

RAML
: Stands for REST API Modeling Language and is similar to OpenAPI specifications. RAML is backed by Mulesoft, a commercial API company, and uses a more YAML-based syntax in the specification. See [RAML tutorial](https://idratherbewriting.com/learnapidoc/pubapis_raml.html) in this course or [RAML](https://raml.org/).

RAML Console
: In Mulesoft, the RAML Console is where you design your RAML spec. Similar to the Swagger Editor for the OpenAPI spec.

repo
: In Git, a repo (short for repository) stores your project's code. Usually, you only store non-binary (human-readable) text files in a repo, because Git can run diffs on text files and show you what has changed (but not with binary files).

request
: The way information is returned from an API. In a request, the client provides a resource URL with the proper authorization to an API server. The API returns a response with the information requested. See [Request example](docapis_doc_sample_requests.html) for more details.

request body parameters
: Parameters that are included in the request body. Usually submitted as JSON. See [Parameters](docapis_doc_parameters.html) for more details.

request example
: {{site.data.apirefsections.request_example.def}} See [Request example](docapis_doc_sample_requests.html) for more details.

resource description
: {{site.data.apirefsections.resource_description.def}} See [Resource description](docapis_resource_descriptions.html) for more details.

response
: The information returned by an API after a request is made. Responses are usually in either JSON or XML format. See [Response example and schema](docapis_doc_sample_responses_and_schema.html) for details.

response example and schema
: {{site.data.apirefsections.request_example.def}} See [Response example and schema](docapis_doc_sample_responses_and_schema.html) for details.

REST API
: Stands for Representational State Transfer. Uses web protocols (HTTP) to make requests and provide responses in a language agnostic way, meaning that users can choose whatever programming language they want to make the calls. See [What is a REST API?](docapis_what_is_a_rest_api.html) for more details.

SDK
: Software development kit. Developers often create an SDK to accompany a REST API. The SDK helps developers implement the API using a specific language, such as Java or PHP. See [SDKs and sample apps](docapis_sdks_and_sample_apps.html) for more details.

Smartbear
: The company that maintains and develops the Swagger tooling &mdash; [Swagger Editor](https://swagger.io/swagger-editor/), [Swagger UI](https://swagger.io/swagger-ui/), [Swagger Codegen](https://swagger.io/swagger-codegen/), [SwaggerHub](https://app.swaggerhub.com/home), and [others](https://swagger.io/tools/). See [Smartbear](https://smartbear.com/).

Sphinx
: A static site generator developed for managing documentation for Python. Sphinx is the most documentation-oriented static site generator available and includes many robust features -- such as search, sidebar navigation, semantic markup, managed links -- that other static site generators lack. Based on Python. See [staticgen.com/sphinx](https://www.staticgen.com/sphinx) for high-level details. For more about static site generators, see [Static site generators](pubapis_static_site_generators.html#sphinx).

Static site generator
: A breed of website compilers that package up a group of files (usually written in Markdown) and make them into a website. There are more than 350 different static site generators. See [Jekyll](pubapis_jekyll.html) in this course for a deep-dive into the most popular static site generator, or [Staticgen](https://www.staticgen.com/) for a list of all static site generators. Also see [Static site generators](pubapis_static_site_generators.html) for a deep-dive into this topic.

Stoplight
: provides a platform with visual modeling tools to create an OpenAPI document for your API &mdash; without requiring you to know the OpenAPI spec details or code the spec line by line. See [http://stoplight.io/](http://stoplight.io/) for more information. Also see [Stoplight &mdash; visual modeling tools for creating your OpenAPI spec](pubapis_stoplight.html).

Swagger
: Refers to general API tooling to support OpenAPI specifications. See [swagger.io/](https://swagger.io/). See [Swagger UI tutorial](pubapis_swagger.html) for details.

Swagger Codegen
: Generates client SDK code for a lot of different platforms (such as Java, JavaScript, Scala, Python, PHP, Ruby, Scala, and more). The client SDK code helps developers integrate your API on a specific platform and provides for more robust implementations that might include more scaling, threading, and other necessary code. In general, SDKs are toolkits for implementing the requests made with an API. Swagger Codegen generates the client SDKs in nearly every programming language. See [Swagger Codegen](https://swagger.io/swagger-codegen/) for more information. See also [SDKs and sample apps](docapis_sdks_and_sample_apps.html).

Swagger Editor
: An online editor that validates your OpenAPI document against the rules of the spec, showing validation errors as found. See [Swagger editor](http://editor.swagger.io/#/).

OpenAPI specification document
: The file (either in YAML or JSON syntax) that describes your REST API. Follows the OpenAPI specification format. See [https://www.openapis.org/](https://www.openapis.org/). See also [OpenAPI 3.0 tutorial](pubapis_openapi_tutorial_overview.html).

Swagger UI
: The most common display framework for parsing an OpenAPI specification document and producing the interactive documentation as shown in the [Petstore demo site](http://petstore.swagger.io/). See [Swagger-UI](https://github.com/swagger-api/swagger-ui)

SwaggerHub
: A site developed by Smartbear to help teams collaborate around the OpenAPI spec. In addition to generating interactive documentation from SwaggerHub, you can generate many client and server SDKs and other services. See [Manage Swagger Projects with SwaggerHub](pubapis_swaggerhub_smartbear.html).

VCS
: Stands for version control system. Git and Mercurial are examples.

version control
: A system for managing code that relies on snapshots that store content at specific states. Enables you to revert to previous states, branch the code into different versions, and more. See [About Version Control](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) in Git. Also see [Version Control Systems](pubapis_version_control.html).

YAML
: Recursive acronym for "YAML Ain't No Markup Language." A human-readable, space-sensitive syntax used in the OpenAPI specification document. See [More About YAML](pubapis_yaml.html).

{% include random_ad2.html %}

{% include random_ad.html %}