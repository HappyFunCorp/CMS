# Headless CMS Tools

An overview of various headless CMS tools, as well as what to consider while picking one for a specific use case.

## Why use a headless CMS tool?

Headless CMS tools offer a modern way of managing and delivering content, separating the content management from the front-end presentation. With a headless CMS, content can be created, managed, and stored in a centralized location, while allowing for greater flexibility in how the content is presented and delivered to end-users.

## Average User Friendliness

Headless CMS tools aim to provide a way for non-technical users to manage and publish content without having to think about the underlying technical infrastructure. Depending upon the headless CMS, some basic knowledge of the content modeling and schemas may be needed, but typically it moves the logic out of the hands of the developer and closer to the content editor. Additionally, a good headless CMS will provide a user-friendly interface for managing and organizing content, so that users can easily publish and manage their content without needing to rely on developers. Also, headless CMS can usually handle the integration with third-party resources and APIs through its app framework.

## Headless CMS Integrations

Integrating a headless CMS with other systems is a crucial aspect to consider when choosing a headless CMS tool. A good headless CMS should provide a wide range of integration options, making it easy to connect to other platforms such as e-commerce, CRM, and marketing automation tools. This can greatly streamline your workflow and eliminate the need for manual data transfer between systems.

It's important to check if the headless CMS has pre-built integrations with popular systems or if it offers APIs and webhooks for custom integrations. A CMS that provides robust and flexible integration options can help you avoid potential issues and improve the overall efficiency of your setup.

## Headless CMS Agnostic

In theory, a headless CMS can be agnostic and allow quick integration with different frontend technologies. In practice, that depends on the level of compatibility and integration offered by the headless CMS. If you are changing the frontend technology part way through the development, there may be complications that require additional tools and configurations. If someone else has already done the same integration, the steps and best practices should be easily available online.

More likely than not, there will be some cases where custom API calls are required - in such cases, it is best if the headless CMS provides robust APIs and documentation to make these custom integrations possible. Additionally, it's important to have a headless CMS that allows for flexible content modeling and structure, to ensure that the content can be easily adapted to different frontend requirements.

## Why Not Use a Headless CMS?

Headless CMS has become increasingly popular in recent years, but it's not the right solution for every use case. Before choosing a headless CMS, it's important to evaluate your requirements and determine whether it's the best fit for your project.

One of the drawbacks of using a headless CMS is that it requires a strong understanding of front-end development and APIs. If your development team is not well-versed in these areas, the learning curve can be steep. Additionally, a headless CMS may not provide all the necessary tools for building a complete website or application, such as a built-in templating system, which means that additional tools and technologies must be added to the development stack.

Another consideration is the lack of integrated functionality. Headless CMS provides a decoupled content management system, but it doesn't provide all the features and functionality that a traditional, monolithic CMS offers. While a headless CMS can be paired with different front-end frameworks, there might be functionalities that aren't available out-of-the-box, requiring custom development or integration with third-party tools. This can lead to a lack of cohesion and increased complexity in the overall solution.

Additionally, the cost of using a headless CMS can sometimes be a disadvantage, especially if there are multiple integrations needed or if the project requires a lot of custom development. In these cases, the cost can add up quickly, making a headless CMS less cost-effective than a traditional monolithic CMS.

In conclusion, while headless CMS tools have many benefits, they may not be the best fit for every project. It's important to carefully evaluate your specific requirements and consider the potential drawbacks before making a decision.

## More on Headless CMS

Headless CMS tools provide a lot of flexibility and independence from frontend development, but they do come with some limitations as well. Some of these limitations include the absence of integrated functionality, lack of visual representation, and the need for custom development to achieve certain features.

The lack of integrated functionality means that some features and functionalities may need to be developed from scratch or through a third-party integration. This can be time-consuming and add additional costs to the development process.

The lack of visual representation can also make it challenging for non-technical users to manage content and make updates. This means that some basic functionalities such as formatting and styling may need to be handled through code, rather than a user-friendly interface.

Additionally, custom development may be required to achieve certain features, such as multi-language support or advanced SEO optimization. This can be a barrier for small businesses or organizations with limited resources for development.

While headless CMS tools provide a lot of benefits, it's important to carefully consider these limitations and weigh them against the specific needs and requirements of your project before making a decision.

## Headless CMS Comparison

This table of features is built based on the team members experience with different headless CMS tools and information found online. The features listed are some of the key aspects that set the different tools apart from each other.

| Headless CMS                        | Contentful           | Dato               | HyGraph             | Sanity\*             | Kontent.ai\*         | Magnolia\*           | Agility CMS\*        | Butter CMS\*         | Contentstack\*       | Bloomreach\*         | Netlify\*            | Strapi\*             |
| ----------------------------------- | -------------------- | ------------------ | ------------------  | -------------------- | -------------------- | -------------------- | -------------------- | -------------------- | -------------------- | -------------------- | -------------------- | -------------------- |
| Singleton Types Support             | :heavy_check_mark:   | :heavy_check_mark: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| SEO Support                         | :heavy_check_mark:   | :heavy_check_mark: | :heavy_check_mark:   | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Page-Driven Content/Schema Modeling | :heavy_check_mark:   | :heavy_check_mark: | :heavy_check_mark:   | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Content-Type Templating             | :white_large_square: | :heavy_check_mark: | :heavy_check_mark: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Development Process and Workflows   | :heavy_check_mark:   | :heavy_check_mark: | :heavy_check_mark:   | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Content Federation                  | :white_large_square: | :heavy_check_mark: | :heavy_check_mark:   | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Simple Permissions                  | :heavy_check_mark:   | :heavy_check_mark: | :heavy_check_mark: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Advanced Permissions (Model level)  | :white_large_square: | :heavy_check_mark: | :heavy_check_mark: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Batch Content Validation            | :white_large_square: | :heavy_check_mark: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Deploy API                          | :heavy_check_mark:   | :heavy_check_mark: | :heavy_check_mark: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Preview API                         | :heavy_check_mark:   | :heavy_check_mark: | :heavy_check_mark: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Supports Websocket                  | :white_large_square: | :heavy_check_mark: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Global Content Types and Entries    | :heavy_check_mark:   | :heavy_check_mark: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Image API                           | :heavy_check_mark:   | :heavy_check_mark: | :heavy_check_mark:   | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Scalability and Performance         | :white_large_square: | :heavy_check_mark: | :heavy_check_mark:   | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Integrating with APIs or Services   | :white_large_square: | :heavy_check_mark: | :heavy_check_mark:   | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Support/Resources Available         | :white_large_square: | :heavy_check_mark: | :heavy_check_mark:   | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Native App Support                  | :white_large_square: | :heavy_check_mark: | :heavy_check_mark: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Data Migration (Export/Import)      | :heavy_check_mark:   | :heavy_check_mark: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| SaaS Model                          | :heavy_check_mark:   | :heavy_check_mark: | :heavy_check_mark:   | :white_large_square: | :heavy_check_mark:   | :white_large_square: | :white_large_square: | :heavy_check_mark:   | :heavy_check_mark:   | :white_large_square: | :white_large_square: | :white_large_square: |
| API-driven                          | :heavy_check_mark:   | :heavy_check_mark: | :heavy_check_mark:   | :heavy_check_mark:   | :heavy_check_mark:   | :heavy_check_mark:   | :heavy_check_mark:   | :heavy_check_mark:   | :heavy_check_mark:   | :heavy_check_mark:   | :white_large_square: | :heavy_check_mark:   |
| Real-time collaboration             | :white_large_square: | :heavy_check_mark: | :white_large_square: | :heavy_check_mark:   | :heavy_check_mark:   | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Supports multiple channels          | :heavy_check_mark:   | :heavy_check_mark: | :white_large_square: | :white_large_square: | :heavy_check_mark:   | :heavy_check_mark:   | :heavy_check_mark:   | :heavy_check_mark:   | :heavy_check_mark:   | :heavy_check_mark:   | :white_large_square: | :white_large_square: |
| Supports multiple devices           | :heavy_check_mark:   | :heavy_check_mark: | :heavy_check_mark: | :white_large_square: | :heavy_check_mark:   | :heavy_check_mark:   | :white_large_square: | :heavy_check_mark:   | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Flexible tech stack                 | :white_large_square: | :heavy_check_mark: | :heavy_check_mark: | :white_large_square: | :heavy_check_mark:   | :heavy_check_mark:   | :heavy_check_mark:   | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :heavy_check_mark:   |
| Easy to use                         | :white_large_square: | :heavy_check_mark: | :heavy_check_mark:   | :heavy_check_mark:   | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :heavy_check_mark:   | :white_large_square: | :heavy_check_mark:   | :heavy_check_mark:   |
| Supports WYSIWYG                    | :white_large_square: | :heavy_check_mark: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :heavy_check_mark:   | :white_large_square: | :white_large_square: |
| Supports frontend frameworks        | :heavy_check_mark:   | :heavy_check_mark: | :heavy_check_mark: | :white_large_square: | :white_large_square: | :heavy_check_mark:   | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :heavy_check_mark:   | :white_large_square: |
| Usage Limits                        | High                 | :heavy_check_mark: | :heavy_check_mark: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |
| Write Rate Limits                   | High                 | :heavy_check_mark: | :heavy_check_mark: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: | :white_large_square: |

Note: This table is not exhaustive and only covers some of the key features that the team members have encountered while working with the different headless CMS tools. Other factors such as migration between environments, data modeling for native apps, and management of content for non-developers should also be considered when choosing a headless CMS tool.

Note 2: The tools that are marked with a `*` are still a work in progress.

### More details

| Headless CMS | User Experience for Content Editors |
| ------------ | ----------------------------------- |
| Contentful   | Depends on content modeling         |
| Dato         | Ideal for web-based projects        |
| HyGraph      | Ideal for web-based projects        |
| Sanity       | Ideal for web-based projects        |

| Headless CMS | Opinion and Recommendations for Specific Use Cases                                |
| ------------ | --------------------------------------------------------------------------------- |
| Contentful   | Ideal for production-ready projects with a big client budget and management needs |
| Dato         | Ideal for projects with a dev and team preference                                 |
| HyGraph      | Ideal for projects with a dev and team preference                                 |
| Sanity       | Ideal for projects with a dev and team preference                                 |

| Headless CMS | Cloud Infrastracture                               |
| ------------ | -------------------------------------------------- |
| Contentful   | AWS (cloudfront and lambda using us-east-1 region) |

## Recommendations

The team members have worked with several headless CMS tools, including Contentful, Dato, and Sanity, and offers recommendations for specific use cases.

Contentful is recommended for any project with a significant client, where the CMS plays a significant role. This platform is widely recognized and respected by both enterprise clients and start-up companies.

For projects that allow for experimentation and the CMS is not a central component, it would be appropriate to consider using Sanity/Dato/HyGraph.

It is important to factor in the budget for the CMS solution. Although the free tier can accommodate a range of use cases, the cost of the enterprise version can become prohibitive in certain scenarios, particularly if enterprise features are required.

## Singleton Types Support

Singleton types are a type of content model that allows you to create a single instance of a specific content type. This is useful when you want to create content that is unique and doesn't need to be repeated.

For example, you might use a singleton type to create a "Site Settings" content type that contains global settings for your website, such as the site name, logo, and contact information. With a singleton type, you can ensure that there is only one instance of this content type, and that it can be easily accessed and managed from within your CMS.

### Dato CMS

Dato CMS allows you to create singleton types just like any other content type, and you can use the same editor interface and API to manage them. This makes it easy to incorporate singleton types into your content management workflow and ensures that your unique content is well-organized and easy to manage.

### Contentful

Contentful does not allow you to create singleton Content Types, implementing a single content for a Content Type is possible but the number of items has to be handled manually.

### HyGraph

HyGraph does not yet allow you to create singleton Content Types, implementing a single content for a Content Type is possible but the number of items has to be handled manually. It is on their radar as can be seen [here](https://hygraph.nolt.io/25) 

## SEO Support

### Dato CMS

Dato CMS has SEO support. Here are some of the ways that Dato CMS can help with SEO:

- Customizable metadata: Dato CMS allows you to set custom meta titles, descriptions, and keywords for each piece of content. This makes it easy to optimize your content for search engines and improve your search rankings.
- Structured data: Dato CMS allows you to add structured data to your content, which can help search engines understand the content of your website better. This can improve your search rankings and make your content more visible in search results.
- URL management: Dato CMS allows you to customize the URLs for your content, which can make them more readable and search engine-friendly. You can also set up redirects to ensure that visitors are always directed to the correct page.
- Sitemap generation: Dato CMS automatically generates a sitemap for your website, which can help search engines discover and index your content more easily.
- Integration with third-party SEO tools: Dato CMS integrates with a variety of third-party SEO tools, such as Google Analytics and Google Search Console, making it easy to monitor your website's performance and optimize your content for search engines.

Overall, Dato CMS provides a variety of SEO features that can help you optimize your content for search engines and improve your search rankings.

### Contentful

Contentful only allows you to store SEO related content in Content Types, the implementation like meta tags, site maps, others have to be build in the frontend from scratch. More details on: [The Contentful SEO Guide](https://www.contentful.com/seo-guide/)

### HyGraph

HyGraph has SEO support. They offer a SEO Schema model that has all the required fields for SEO:

- Meta Title
- Meta Description
- Focus Keywords
- OG Image
- No Index
- Page
- Post

And the possibility to add _noindex and _nofollow attributes


## Page-Driven Content and Schema Modeling

Page-driven content modeling is a method of organizing content around the pages of a website, rather than around individual content types.

With page-driven content modeling, you can create dynamic, responsive websites that can be easily customized and updated. You can also manage your content more efficiently, since you can edit and update content within the context of the page, rather than in isolation.

### Dato CMS

In Dato CMS, you can create page models that define the structure and content of each page on your website. These page models can include custom fields, relationships, and validation rules, just like any other content model. You can also define the content blocks that make up each page, and specify the layout and design of each block.

Dato CMS also supports hybrid content modeling, which allows you to combine page-driven content models with traditional content models. This gives you the flexibility to organize your content in a way that makes sense for your website and your workflow.

In summary, Dato CMS provides robust support for page-driven content/schema modeling, allowing you to create dynamic, responsive websites that are easy to manage and update.

### Contentful

The Content Type is the main block for building the content structure, it includes fields, data types, validations and relationships with other Content Types. Custom data shapes and React components can be used to customize fields look and behavior for the most advanced use cases.

### HyGraph

HyGraph is very similar to Dato in the way page models are defined and structured. Everything that is true for Dato is also true for HyGraph.

## Content-Type Templating

Content-type templating is a way of defining a standard layout and design for a particular content type, which can be applied to all instances of that content type.

With content-type templating, you can ensure that your content is well-organized and visually appealing, and that it meets the specific requirements of your website or application.

Content-type templating can help you create dynamic, engaging content that meets the needs of your audience.

### Dato CMS

In Dato CMS, you can create content-type templates using a combination of HTML, CSS, and Liquid, a templating language that allows you to dynamically generate content based on data from your CMS. You can use these templates to define the layout, design, and functionality of your content types, and ensure that all instances of that content type are consistent and well-organized.

Content-type templates in Dato CMS are highly customizable, and you can create templates that reflect the unique needs of your website or application. You can also use Liquid to create dynamic content, such as image galleries, carousels, and forms, which can be easily added to your content types.

### Contentful

As a headless CMS, Contentful only provides the structured information using the API, the look and feel of the content has to be developed on the frontend side.

### HyGraph

HyGraph uses what they call "Components" to define a modular content type structure. Components are reusable, can contain fields or they can be nested. This is similar to what Dato offers as far as I've seen.

## Development Process and Workflows

### Dato CMS

Dato CMS provides a robust development process and workflow features to help teams collaborate and manage content effectively. Here are some of the key features:

- Staging environments: Dato CMS provides staging environments that allow teams to test and preview changes before pushing them live. This ensures that changes are thoroughly tested and approved before they are made public.
- Versioning and history: Dato CMS tracks changes to content, allowing teams to view previous versions and revert to earlier versions if needed. This makes it easy to track changes and collaborate on content.
- Roles and permissions: Dato CMS allows teams to set up roles and permissions, ensuring that team members have the appropriate level of access to content and features. This makes it easy to manage workflows and ensure that content is reviewed and approved by the appropriate team members.
- Workflow management: Dato CMS provides workflow management features that allow teams to set up custom workflows and automate content approval processes. This can help teams manage content more efficiently and ensure that content is reviewed and approved in a timely manner.
- API access: Dato CMS provides API access, allowing teams to integrate content management into their existing development workflow. This makes it easy to use Dato CMS alongside other development tools and services.

Dato CMS provides a robust set of development process and workflow features that make it easy for teams to collaborate and manage content effectively. These features can help teams save time, reduce errors, and ensure that content is consistently high-quality and meets the needs of the audience.

### Contentful

Contentful provides a robust development process and workflow features to help teams collaborate and manage content effectively. Here are some of the key features:

- Environments: You can create multiple environments to test and preview changes before pushing them live, the number of environments, names, and capabilities can be configured to match any existing development workflow.
- Versioning and history: Contentful tracks changes to content, allowing teams to view previous versions and revert to earlier versions if needed.
- API access: Contentful provides API access using the Content Management API, allowing teams to integrate content management into their existing development workflow.

### HyGraph

HyGraph offers a pretty robust process and workflows for collaboration and content management. 

- Staging environments: HyGraph provides staging environments that allow teams to test and preview changes before pushing them live. This ensures that changes are thoroughly tested and approved before they are made public.
- Roles and permissions: HyGraphallows teams to set up roles and permissions, ensuring that team members have the appropriate level of access to content and features. This makes it easy to manage workflows and ensure that content is reviewed and approved by the appropriate team members.
- API access: HyGraph provides API access, allowing teams to integrate content management into their existing development workflow. This makes it easy to use HyGraph alongside other development tools and services.

## Programmatic content Managemement

### HyGraph

I'm not sure if this can be done with Dato, but on the GraphQL level you can actually use the GraphQL API both for content management and Mutations. 


## Content Federation

Content federation is a way of managing content across multiple systems and platforms, allowing teams to create, manage, and publish content from a centralized location.

Using content federation, teams can create a centralized content repository that can be accessed and managed from any system or platform. This makes it easy to manage content across multiple channels, such as websites, mobile apps, and social media, and ensures that content is consistent and up-to-date.

### Dato CMS

In Dato CMS, content federation is achieved through its API-first architecture, which allows content to be accessed and managed via an API. This API can be used to connect Dato CMS to other systems and platforms, such as eCommerce platforms, marketing automation tools, or other content management systems.

Dato CMS also provides a variety of tools and features to make content federation easier, such as webhook integrations, content synchronization, and data mapping. These features allow teams to automate content management tasks, reduce errors, and ensure that content is delivered to the right channels at the right time.

Content federation helps teams manage content more efficiently and effectively across multiple systems and platforms.

### Contentful

Developers can use the Content Delivery API, Content Preview API and Content Management API to consume and manage the content from any backend, script or frontend application, there is also the Contentful CLI tool to manage content from the console.

### HyGraph

HyGraph has content federation through their api. Their integration capabilities are thorough and other APIs and data sources can be integrated seamlessly.

## Simple Permissions

You can create custom roles and permissions to control access to content and features.

This allows you to give team members the appropriate level of access to content, based on their role and responsibilities.

These features allow you to monitor and track changes to content, ensuring that your team is working effectively and that content is being reviewed and approved in a timely manner.

### Dato CMS

Dato CMS provides simple permissions management features.

Dato CMS provides a simple and intuitive interface for managing permissions. You can set up roles with specific permissions, such as read-only access, content creation, or administrative access. You can also assign individual team members to specific roles, ensuring that each team member has the appropriate level of access to content and features.

In addition to roles and permissions, Dato CMS also provides features such as activity logs, revision history, and audit trails.

Overall, Dato CMS provides simple and effective permissions management features, allowing teams to control access to content and features and ensure that content is managed in a safe and secure manner.


### HyGraph

HyGraph provides simple permissions management features.

## Advanced Permissions at the Model level

You can define custom permissions for each individual content model, allowing you to control access to specific content types or fields.

You might want to restrict access to certain fields within a content model to specific team members or roles.

These features allow you to set up complex workflows and approvals processes, ensuring that content is reviewed and approved by the appropriate team members before being published.

### Dato CMS

Dato CMS provides advanced permissions management features at the model level.

You can define custom permissions at the field level, ensuring that only authorized team members can view or modify specific fields.

In addition to field-level permissions, Dato CMS also provides advanced permissions management features such as workflow approvals, content approvals, and role-based access control.

Dato CMS provides advanced permissions management features at the model level, allowing teams to control access to specific content types or fields and ensure that content is managed securely and effectively. These features make it easy to manage complex workflows and ensure that content is consistently high-quality and meets the needs of the audience.

### HyGraph

HyGraph provides advanced permissions management features at most levels.

## Batch Content Validation

Batch content validation allows you to check all content on your website or application at once, rather than checking each item individually. This can be a useful tool for identifying errors or inconsistencies across large amounts of content.

You can use validation rules to check the content of your website or application for errors or inconsistencies. This can help you identify and correct errors before they affect your users.

### Dato CMS

Dato CMS provides batch content validation features.

Dato CMS provides a variety of validation rules that can be applied to your content, including required fields, minimum and maximum values, and data type validation. You can also create custom validation rules to ensure that your content meets specific requirements.

Dato CMS also provides features such as revision history and audit trails, which can help you track changes to your content and identify the source of errors or inconsistencies. This can make it easier to correct errors and ensure that your content is consistently high-quality.

Batch content validation helps teams identify and correct errors or inconsistencies in their content. This can improve the user experience and ensure that your content meets the needs of your audience.

## Deploy API

The Deploy API allows developers to programmatically deploy changes to a Dato CMS project, making it easy to automate deployment workflows and integrate Dato CMS with other development tools and services.

Using the Deploy API, developers can create custom deployment scripts that can be triggered automatically whenever changes are made to the content in Dato CMS. This can help to streamline the deployment process and ensure that changes are pushed live quickly and reliably.

The Deploy API also provides a variety of features that can help to ensure that deployments are successful, such as pre-deployment checks, rollback functionality, and status monitoring. These features can help to minimize errors and downtime, and ensure that changes are pushed live smoothly and efficiently.

### Dato CMS

Dato CMS does provide a Deploy API. It helps teams streamline the deployment process and integrate Dato CMS with other development tools and services.

### Contentful

Any deployment workflow can be integrated using the Content Management API.


## Preview API

The Preview API allows developers to preview changes to content before they are published to the live site. This can be useful for reviewing and testing changes, ensuring that they are working as expected and do not introduce any errors or issues.

Using the Preview API, developers can create custom preview templates that can be used to render content in a preview environment. These templates can be customized to match the design and layout of the live site, making it easy to preview changes in context.

The Preview API also provides a variety of features that can help to ensure that previews are accurate and reliable, such as real-time synchronization, revision history, and preview content filtering. These features can help to minimize errors and ensure that previews accurately reflect the changes that will be published to the live site.

### Dato CMS

The Preview API in Dato CMS can help teams review and test changes before they are published to the live site. This can improve the quality of your content and ensure that changes are working as expected.

### Contentful

Contentful offers the Content Preview API where you can preview the changes in the content that is not pushished yet, proven to be useful when content managers want to preview content using custom frontend solutions. 


### HyGraph

HyGraph allows users to use the equivalent of the Preview API where you can preview the changes in the content that is not pushished yet by creating an API Key that can read the "Draft" status. 

## Supports Websocket

WebSockets are a protocol that allow for real-time communication between a client and a server, making it possible to build dynamic and interactive applications.

You can use WebSockets to build real-time applications that can respond quickly and efficiently to changes in content. For example, you might use WebSockets to build a real-time chat application, or to build a dashboard that displays real-time analytics data.

### Contentful

No support for websockets implementation.

### Dato CMS

Dato CMS provides WebSocket support through its API, which allows you to build custom WebSocket applications that can communicate with the Dato CMS server in real-time. This makes it possible to build dynamic and responsive applications that can respond to changes in content quickly and efficiently.

Dato CMS helps teams build real-time applications that are fast, responsive, and efficient. This can improve the user experience and make it possible to build applications that are more engaging and interactive.

## Global Content Types and Entries

Global content types and entries are a way of organizing content that is used across multiple pages or sections of a website or application.

You can create global content types that can be used across multiple pages or sections of your website or application. For example, you might create a "Product" content type that contains information about a product, such as the name, description, and price. You can then use this content type to display product information on multiple pages or sections of your website or application.

Global content entries are instances of a global content type that can be used on multiple pages or sections of your website or application. For example, you might create a global content entry for a particular product, and then use that content entry to display information about the product on multiple pages or sections of your website or application.

You can ensure that content is consistent across your website or application, and that changes are easy to manage and propagate. This can save time and reduce errors, and ensure that your content is always up-to-date and relevant.

### Dato CMS

Global content types and entries in Dato CMS can help teams manage content more efficiently and ensure that content is consistent across multiple pages or sections of their website or application.

### Contentful

All the Content Types content can be requested from the API and can be structured based on the requirements. It's recommended to use the GraphQL API which is a great tool to compose and optimize data requests to get only what is needed for an specific page or section.

## Image API

The Image API allows you to manipulate and optimize images programmatically, making it easy to deliver optimized images to your website or application.

You can resize, crop, and compress images, as well as add effects, filters, and watermarks. This can help to ensure that images are optimized for performance and user experience, without sacrificing quality.

The Image API also provides a variety of features that can help to ensure that images are delivered quickly and efficiently, such as automatic image format detection, responsive image support, and image lazy loading. These features can help to improve the performance of your website or application, especially on mobile devices or slower connections.

### Dato CMS

The Image API in Dato CMS can help teams optimize and deliver images more efficiently and effectively. This can improve the user experience and ensure that your website or application is fast, responsive, and engaging.

### Contentful

Contentful can work as an assets repository and CDN, and those assets can be consumed and managed via the Images API.

This API allows you to resize, crop, change format, reduce quality plus other features, proven to be useful getting images and optimizing them for the Web and serving them directly from Contentful without any other CDN needed.

### HyGraph

HyGraph has image APIs that allow you to resize images and other things on the fly from within the GraphQL Query.

## Scalability and Performance

### Dato CMS

Dato CMS is designed to provide scalability and performance for websites and applications of all sizes. Here are some of the ways that Dato CMS achieves scalability and performance:

- Cloud-based hosting: Dato CMS is hosted in the cloud, which allows it to scale easily to handle increased traffic and content volumes. This ensures that your website or application can handle traffic spikes and high volumes of content without experiencing performance issues.
- API-first architecture: Dato CMS is built around an API-first architecture, which allows it to integrate with other systems and platforms easily. This makes it easy to scale your content management system alongside other parts of your infrastructure.
- Content delivery network (CDN) integration: Dato CMS integrates with CDNs, which can help to improve the performance of your website or application by caching content and delivering it from a server that is closer to the user.
- Image optimization: Dato CMS provides image optimization features that can help to reduce the size of images and improve their performance. This can help to reduce page load times and improve the user experience.
- Serverless architecture: Dato CMS is built on a serverless architecture, which allows it to scale automatically based on usage. This ensures that resources are allocated efficiently and that your website or application can handle traffic spikes without experiencing performance issues.

Dato CMS is designed to provide scalability and performance for websites and applications of all sizes. Its cloud-based hosting, API-first architecture, CDN integration, image optimization, and serverless architecture all contribute to a fast, reliable, and scalable content management system.

### HyGraph

HyGraph is scalable and has many different CDNs. Scalability and redundancy are based on different pricing tiers.

## Integrating with APIs or Services

### Dato CMS

Dato CMS provides a variety of features and tools that allow you to integrate with APIs or services. Here are some of the key features:

- API-first architecture: Dato CMS is built around an API-first architecture, which makes it easy to integrate with other systems and platforms. The API provides a flexible way to access and manage content, allowing you to build custom integrations and workflows.
- Webhooks: Dato CMS provides webhook integrations, which allow you to trigger custom events based on changes to content. This can be useful for integrating with other systems or services, such as sending notifications or triggering automated workflows.
- Zapier integration: Dato CMS integrates with Zapier, a popular automation platform, allowing you to build custom integrations with thousands of other apps and services.
- Content federation: Dato CMS allows you to federate content across multiple systems and platforms, making it easy to manage content from a centralized location.
- Custom extensions: Dato CMS provides a variety of tools and features for building custom extensions, such as field types, plugins, and widgets. This makes it easy to extend the functionality of Dato CMS and integrate with other systems or services.

Dato CMS provides a variety of features and tools that make it easy to integrate with APIs or services. Its API-first architecture, webhook integrations, Zapier integration, content federation, and custom extensions all contribute to a powerful and flexible content management system that can be easily integrated with other parts of your infrastructure.

### HyGraph

HyGraph can connect to third party APIs as well as use WebHooks. The documentation is not very rich and I suspect this is still a young feature.

## Support/Resources Available

### Dato CMS

Dato CMS provides comprehensive support and resources to help you get the most out of the platform. Here are some of the key support and resource features:

- Documentation: Dato CMS provides detailed documentation that covers all aspects of the platform, from getting started to advanced features. The documentation includes step-by-step guides, tutorials, API reference, and more.
- Customer support: Dato CMS provides customer support via email, chat, and phone. Their support team is available to help with any issues or questions you may have, and they typically respond within a few hours.
- Community forum: Dato CMS maintains a community forum where users can ask questions, share tips and tricks, and discuss best practices. This is a great resource for getting help from other users and sharing your own experiences.
- Developer tools: Dato CMS provides a variety of developer tools and resources, such as SDKs, APIs, and CLI tools. These tools make it easy to integrate with Dato CMS and extend its functionality.
- Blog and newsletter: Dato CMS maintains an active blog and newsletter that cover industry news, platform updates, and best practices. This is a great resource for staying up-to-date on the latest trends and developments in content management.

Dato CMS provides comprehensive support and resources to help you get the most out of the platform. Whether you're a developer, marketer, or content creator, there are resources available to help you succeed with Dato CMS.

## Native App Support

### Dato CMS

Dato CMS provides seamless integration with native app frameworks. Dato CMS is designed to be a headless CMS, which means that it provides content as an API that can be accessed by any front-end application, including native app frameworks.

Dato CMS provides a flexible API that supports a variety of formats and protocols, including REST, GraphQL, and JSON. This makes it easy to integrate Dato CMS content into any native app framework, regardless of the programming language or framework used.

Dato CMS also provides SDKs for various programming languages, such as JavaScript, iOS, and Android, which can help developers to easily integrate Dato CMS content into their native app projects. These SDKs provide a streamlined way to connect to the Dato CMS API and access content.

In addition, Dato CMS provides a variety of tools and features that can help you optimize your content for use in a native app. For example, you can use the Image API to optimize images for mobile devices, or the Preview API to preview changes to content on a mobile device.

Dato CMS makes it easy to integrate content into native app frameworks. Its flexible API, SDKs, and optimization features allow developers to deliver high-quality content to native app users, ensuring that they have a seamless and engaging user experience.

### Contentful

As a headless CMS any other service with network request capabilities using REST API or GraphQL APIs are able to consume and manage the content.

## Data Migration (Export/Import)

This can be useful for migrating content between different same CMS projects, or for migrating content from other content management systems to the one in use.

The ability to export and import content in JSON or CSV format, along with customizable import and export functionality, makes it easy to migrate content between systems and ensure that your content is always up-to-date and relevant.

### Dato CMS

Dato CMS supports data migration through export and import functionality.

Here are some key features of the data migration functionality in Dato CMS:

- Export functionality: Dato CMS provides the ability to export content to JSON or CSV format. This allows you to extract content from one Dato CMS project and import it into another, or to migrate content from other systems to Dato CMS.
- Import functionality: Dato CMS allows you to import content from JSON or CSV files. This makes it easy to migrate content from other systems to Dato CMS, or to import content into a new Dato CMS project.
- Customizable import and export: Dato CMS provides customizable import and export functionality, allowing you to tailor the process to your specific needs. For example, you can choose which content types and fields to include in the export or import.
- Automatic mapping: Dato CMS automatically maps content types and fields during the import process, making it easy to import content into the correct fields.

The data migration functionality in Dato CMS provides a conveninant way for managing content across different projects or systems.

### Contentful

Contentful provides the Contentful CLI tool that allows to import and export the Content Types and content in JSON format across multiple Spaces.

Also provides the Contentful Migration tool that allows to do batch transformations in the content using code scripts.


## SaaS Model

With the SaaS model, you don't need to worry about hosting or maintaining your own content management system. Instead, the CMS system handles everything for you, from hosting to updates to security.

The SaaS model provides a convenient and cost-effective way to manage your content, allowing you to focus on creating great content and growing your business.

### Dato CMS

Dato CMS provides a SaaS (Software-as-a-Service) model, which means that it is hosted in the cloud and provides a subscription-based pricing model.

The Dato CMS SaaS model provides several benefits:

- Easy setup: With the SaaS model, you don't need to worry about setting up and configuring your own content management system. Dato CMS handles everything for you, making it easy to get started with managing your content.
- Scalability: Dato CMS is designed to scale to handle websites and applications of all sizes. With the SaaS model, you can easily scale your content management system to meet your needs as your website or application grows.
- Predictable costs: With the subscription-based pricing model, you can easily predict your costs and budget accordingly. This makes it easier to manage your finances and plan for the future.
- Security: Dato CMS provides a secure and reliable platform that is constantly monitored and updated. With the SaaS model, you don't need to worry about security issues or keeping your content management system up-to-date.

### Contentful

Contentful provides a SaaS (Software-as-a-Service) model, which means that it is hosted in the cloud and provides a subscription-based pricing model.

### HyGraph

HyGraph also provides a SaaS (Software-as-a-Service) model, it's hosted in the cloud and provides a subscription-based pricing model. It also offers a free tier.

## Real-time collaboration

Real-time collaboration allows multiple users to edit content simultaneously, and updates are synced in real-time, allowing users to see changes as they happen.

The ability to collaborate in real-time, track changes, and leave feedback or notes can help teams work more efficiently and effectively, leading to higher quality content and better results.

### Dato CMS

Dato CMS supports real-time collaboration, which makes it easy for teams to work together on content creation and management.

Here are some key features of real-time collaboration in Dato CMS:

- User roles and permissions: Dato CMS provides user roles and permissions that allow you to control who has access to which content and what level of access they have. This ensures that team members have the appropriate level of access to work on content collaboratively.
- Live updates: Dato CMS provides live updates that allow multiple users to edit content simultaneously. As one user makes changes, the changes are synced in real-time, allowing other users to see the changes as they happen.
- Version control: Dato CMS provides version control that allows you to track changes to content over time. This makes it easy to revert to a previous version of content if needed, or to review changes made by team members.
- Comments and annotations: Dato CMS provides comments and annotations that allow team members to leave feedback or notes on content. This can be useful for providing feedback on content, or for discussing changes with other team members.

Real-time collaboration in Dato CMS provides a way for teams to work together on content creation and management.

## Supports multiple channels

Mult-channel support allows you to manage content across multiple platforms and channels, including websites, mobile apps, social media, and more.

### Dato CMS

Dato CMS is a headless CMS, which means that it provides content as an API that can be accessed by any front-end or mobile application. This makes it easy to use Dato CMS content in a variety of channels and platforms.

Here are some key features of the multi-channel support in Dato CMS:

- Flexible API: Dato CMS provides a flexible API that supports a variety of formats and protocols, including REST, GraphQL, and JSON. This makes it easy to integrate Dato CMS content into any channel or platform.
- Content federation: Dato CMS allows you to federate content across multiple systems and platforms, making it easy to manage content from a centralized location.
- Customizable content models: Dato CMS provides customizable content models, which allows you to tailor your content for specific channels or platforms. For example, you can create content types that are optimized for mobile devices, or that are designed specifically for social media platforms.
- Image optimization: Dato CMS provides image optimization features that can help to reduce the size of images and improve their performance. This can help to ensure that images are optimized for different channels and platforms.

Dato CMS manages content across multiple channels and platforms. Its flexible API, content federation, customizable content models, and image optimization features allow you to deliver high-quality content to your audience, regardless of the channel or platform they are using.

### Contentful

The developers must decide the needs of every channel and optimize the queries based on the requirements, it's recommended to use the GraphQL that allows you to optimize your requests selecting only the required fields and relationships and this can be decided and implemented on the client/consumer side.

## Supports multiple devices

Multiple devices support allows you to manage content that is optimized for a variety of devices, including desktops, laptops, tablets, and mobile devices.

### Dato CMS

Dato CMS supports multiple devices, which allows you to manage content that is optimized for a variety of devices, including desktops, laptops, tablets, and mobile devices.

Dato CMS is a headless CMS, which means that it provides content as an API that can be accessed by any front-end or mobile application. This makes it easy to use Dato CMS content on a variety of devices.

Here are some key features of the multi-device support in Dato CMS:

- Responsive design: Dato CMS allows you to create content that is optimized for a variety of devices, using responsive design techniques that adapt the layout and design of content to different screen sizes.
- Image optimization: Dato CMS provides image optimization features that can help to reduce the size of images and improve their performance on different devices. This can help to ensure that images are optimized for different devices and screen sizes.
- Preview functionality: Dato CMS provides preview functionality that allows you to see how content will look on different devices before it is published. This can help you to ensure that content is optimized for different devices and screen sizes.
- Customizable content models: Dato CMS provides customizable content models, which allows you to tailor your content for specific devices or screen sizes. For example, you can create content types that are optimized for mobile devices, or that are designed specifically for tablets.

Dato CMS is optimized for a variety of devices and screen sizes. Its responsive design, image optimization features, preview functionality, and customizable content models allow you to deliver high-quality content to your audience, regardless of the device they are using.

## Flexible tech stack

### Dato CMS

Dato CMS provides a flexible tech stack, which means that it can be used with a variety of front-end technologies and programming languages.

Dato CMS is a headless CMS, which means that it provides content as an API that can be accessed by any front-end or mobile application. This makes it easy to use Dato CMS content with a variety of front-end technologies and programming languages.

Here are some key features of the flexible tech stack in Dato CMS:

- Flexible API: Dato CMS provides a flexible API that supports a variety of formats and protocols, including REST, GraphQL, and JSON. This makes it easy to integrate Dato CMS content into any front-end or mobile application, regardless of the programming language or framework used.
- SDKs and libraries: Dato CMS provides SDKs and libraries for various programming languages, including JavaScript, iOS, and Android. These tools can help developers to easily integrate Dato CMS content into their front-end projects.
- Customizable content models: Dato CMS provides customizable content models, which allows you to tailor your content for specific front-end technologies and programming languages. For example, you can create content types that are optimized for specific front-end frameworks or programming languages.
- Integrations: Dato CMS provides integrations with a variety of front-end technologies and services, including Gatsby, Next.js, Vue.js, and more. These integrations make it easy to use Dato CMS with popular front-end technologies and services.

Dato CMS can be used with a variety of front-end technologies and programming languages. Its flexible API, SDKs and libraries, customizable content models, and integrations allow developers to deliver high-quality content to their audience, regardless of the front-end technology or programming language used.

## Easy to use

### Dato CMS

Dato CMS is designed to be easy to use, with a user-friendly interface and intuitive features that make it easy to manage your content.

Here are some key features that make Dato CMS easy to use:

- User-friendly interface: Dato CMS provides a user-friendly interface that is easy to navigate and understand. The interface is designed to be intuitive and easy to use, even for users with little or no technical expertise.
- Drag-and-drop functionality: Dato CMS provides drag-and-drop functionality that allows you to easily add and arrange content on your website or application. This makes it easy to create and manage content without needing to write any code.
- Customizable content models: Dato CMS provides customizable content models, which allows you to tailor your content for your specific needs. This makes it easy to create and manage content that is relevant and useful for your audience.
- Collaboration features: Dato CMS provides collaboration features that allow team members to work together on content creation and management. Real-time collaboration, version control, comments and annotations, and user roles and permissions make it easy to collaborate with team members and ensure that content is high-quality.
- Seamless deployment: Dato CMS provides seamless deployment features that make it easy to deploy your content to a variety of platforms and channels, including websites, mobile apps, social media, and more. This allows you to reach your audience wherever they are, without needing to worry about technical details or coding.

Dato CMS's user-friendly interface, drag-and-drop functionality, customizable content models, collaboration features, and seamless deployment make it easy to create, manage, and publish high-quality content that engages your audience and helps you achieve your goals.

### HyGraph

HyGraph is extremely simple to use. If you have any experience with Dato CMS it will feel very familiar. They have an abundance of youtube videos to explain concepts, which, in my opinion, is a big strength.

## Supports WYSIWYG

### Dato CMS

Dato CMS supports WYSIWYG (What You See Is What You Get) editors, which allows you to create and edit content visually, without needing to write any code.

Here are some key features of the WYSIWYG support in Dato CMS:

- Rich text editing: Dato CMS provides a rich text editor that allows you to create and edit content with formatting options such as bold, italic, lists, and more. This makes it easy to create content that is visually appealing and engaging for your audience.
- Image and video support: Dato CMS allows you to add images and videos to your content using a WYSIWYG editor. This makes it easy to create visually appealing content that includes multimedia elements.
- Customizable content models: Dato CMS provides customizable content models, which allows you to create WYSIWYG editors that are tailored to your specific needs. This makes it easy to create and edit content that is relevant and useful for your audience.
- Preview functionality: Dato CMS provides preview functionality that allows you to see how your content will look before it is published. This makes it easy to ensure that your content looks and functions as intended.

The WYSIWYG support in Dato CMS is a conveniant way for creating and editing content visually. Its rich text editing, image and video support, customizable content models, and preview functionality make it easy to create engaging and visually appealing content that resonates with your audience.

### Contentful

Contentful supports adding WYSIWYG fields to any Content Type, the WYSIWYG editor is customizable, depending on the features required to be enabled, as a React component it is also extensible with custom code. It supports rich text editing, image and video, and it is also able to embed other Content Types to display them inside the content.

On the frontend, all the content included in the field it's decomposed as nodes and the developers must decide how to render them.

## Supports frontend frameworks

### Dato CMS

Dato CMS supports frontend frameworks, making it easy to integrate Dato CMS content into any frontend application built with popular frontend frameworks such as React, Angular, Vue.js, and more.

Dato CMS is a headless CMS, which means that it provides content as an API that can be accessed by any frontend or mobile application. This makes it easy to use Dato CMS content with a variety of frontend frameworks and libraries.

Here are some key features that make it easy to integrate Dato CMS with frontend frameworks:

- Flexible API: Dato CMS provides a flexible API that supports a variety of formats and protocols, including REST, GraphQL, and JSON. This makes it easy to integrate Dato CMS content into any frontend application built with any frontend framework or library.
- SDKs and libraries: Dato CMS provides SDKs and libraries for various programming languages, including JavaScript, iOS, and Android. These tools can help developers to easily integrate Dato CMS content into their frontend projects.
- Customizable content models: Dato CMS provides customizable content models, which allows you to tailor your content for specific frontend frameworks or libraries. For example, you can create content types that are optimized for React, Angular, or Vue.js.
- Integrations: Dato CMS provides integrations with a variety of frontend technologies and services, including Gatsby, Next.js, Vue.js, and more. These integrations make it easy to use Dato CMS with popular frontend technologies and services.

Dato CMS provides a flexible tool for integrating with frontend frameworks, making it easy to use Dato CMS content with any frontend application built with any frontend framework or library.

### Contentful

The Content Delivery API, Content Preview API, Images API are agnostic and can be consumed by any service based on their needs. These API are offered in REST and GraphQL versions, being GraphQL the recommended one.

## Usage Limits

Usage limits are designed to ensure that the platform remains stable and reliable, and that resources are allocated fairly to all users.

Here are some common usage limits that may be imposed by Dato CMS:

- API requests: The system may impose limits on the number of API requests that can be made per month, or per day. This ensures that the API is not overloaded and that resources are available to all users.
- Content items: The system may impose limits on the number of content items that can be created, or on the total amount of storage used for content. This ensures that resources are allocated fairly and that the platform remains stable and reliable.
- Team members: The system may impose limits on the number of team members that can be added to your account, or on the number of team members that can access certain features or content. This ensures that access to sensitive content is restricted to authorized team members.
- Concurrent editors: The system may impose limits on the number of concurrent editors that can work on content at the same time. This ensures that the platform remains stable and reliable, and that resources are allocated fairly to all users.

### Dato CMS

Dato CMS has usage limits, which are determined by your subscription plan.

### Contentful

Contentful has environments limit, read rate and complexity limits, those can be lifted based on the project requirements contacting the Contentful support team.

### HyGraph

HyGraph CMS has usage limits for the free tier (1 million api calls/100GB asset traffic) and paid plans with no limits.


## Write Rate Limits

Write rate limits restrict the number of write operations that can be performed on the platform within a certain time frame.

Write operations include creating, updating, and deleting content items, as well as uploading files and assets. By imposing write rate limits, the system ensures that resources are allocated fairly to all users, and that the platform remains stable and reliable.

Here are some common write rate limits that may be imposed by Dato CMS:

- Content item creation: Dato CMS may limit the number of content items that can be created within a certain time frame, such as per minute or per hour. This ensures that the platform is not overwhelmed by a large number of write requests at once.
- Content item updates: Dato CMS may limit the number of content items that can be updated within a certain time frame, such as per minute or per hour. This ensures that resources are allocated fairly to all users, and that the platform remains stable and reliable.
- File uploads: Dato CMS may limit the number of files that can be uploaded within a certain time frame, or the size of files that can be uploaded. This ensures that resources are allocated fairly to all users, and that the platform remains stable and reliable.

Write rate limits are an important part of maintaining the stability and reliability of a system. By limiting the number of write operations that can be performed within a certain time frame, Dato CMS ensures that resources are allocated fairly to all users, and that the platform remains stable and reliable.

### Dato CMS

Dato CMS has write rate limits, which are designed to ensure the stability and reliability of the platform.

### Contentful

Contentful has write rate and complexity limits, those can be lifted based on the project requirements contacting the Contentful support team.

### HyGraph

HyGraph CMS has usage limits for the free tier (1 million api calls/100GB asset traffic) and paid plans with no limits.
