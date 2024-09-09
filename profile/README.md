# CMS-agnostic Pattern and Universal Content Data Model Initiative Community

## The Idea and Motivation

TBD

## Background

There are several examples of universal content data models that have been developed over time to standardize the organization of data across different systems and industries. These models are often designed to work across platforms, languages, and industries, facilitating interoperability and consistency in how content is structured and managed. Here are some prominent examples:

1. Dublin Core Metadata Initiative (DCMI):
Context: Developed in the mid-1990s, Dublin Core is a widely-used metadata standard designed to describe digital content such as documents, web pages, images, and other resources.
Model: It defines a simple set of 15 core metadata elements (e.g., Title, Creator, Subject, Date, Type) that can be applied universally to describe a wide variety of resources.
Usage: Dublin Core is commonly used in libraries, digital archives, and content management systems to ensure standardized metadata descriptions across different types of content.
Example:
```
<dc:title>Example Article</dc:title>
<dc:creator>John Doe</dc:creator>
<dc:subject>History</dc:subject>
<dc:date>2023-09-07</dc:date>
```

2. Schema.org:
Context: Launched in 2011 by Google, Microsoft, Yahoo!, and Yandex, Schema.org provides a structured data model for describing content on the web in a way that search engines and other systems can easily interpret.
Model: It defines types and properties for a broad range of entities (e.g., Articles, Events, Products, Organizations), providing a universal content model for web content that can be embedded in HTML (via Microdata, RDFa, or JSON-LD).
Usage: Schema.org is used to improve search engine optimization (SEO) and ensure that structured data is recognized and displayed in search results.
Example:
```
{
  "@context": "https://schema.org",
  "@type": "Article",
  "headline": "The Future of Universal Content Models",
  "author": {
    "@type": "Person",
    "name": "Jane Smith"
  },
  "datePublished": "2024-09-07"
}
```

3. Content Management Interoperability Services (CMIS):
Context: CMIS is an open standard that defines a data model and a set of web services for managing content across different content management systems (CMS). It was standardized by OASIS in 2010.
Model: CMIS provides a common data model for content repositories, enabling interoperability between systems like Microsoft SharePoint, Alfresco, and others. It includes concepts like "Documents," "Folders," and "Relationships" that apply universally to content stored in repositories.
Usage: CMIS is used in enterprise content management to allow different systems to communicate and exchange content seamlessly.
Example: In CMIS, documents are described using universal types and properties that can be accessed across different systems:
```
<entry>
  <title>Annual Report</title>
  <cmis:objectId>1234</cmis:objectId>
  <cmis:baseTypeId>cmis:document</cmis:baseTypeId>
  <cmis:name>annual-report.pdf</cmis:name>
</entry>
```

4. Public Broadcasting Metadata Dictionary Project (PBCore):
Context: Developed by the public broadcasting community, PBCore is a metadata standard designed to describe media content, particularly for radio, television, and other multimedia assets.
Model: PBCore defines a set of metadata elements specific to media assets, including Title, Creator, Contributor, Rights, and Asset Type. It allows public broadcasters to maintain consistent data models for their content.
Usage: PBCore is widely used in media asset management systems in public broadcasting and other media organizations.
Example:
```
<pbcoreTitle>
  <title>Example Program</title>
</pbcoreTitle>
<pbcoreCreator>
  <creator>Jane Producer</creator>
</pbcoreCreator>
```

5. PRISM (Publishing Requirements for Industry Standard Metadata):
Context: PRISM is a data model used by the publishing industry to describe the structure and content of digital publications. It was introduced by IDEAlliance to ensure consistency across publishing platforms.
Model: It defines a broad range of metadata elements for managing print, online, and mobile publications, including properties like Title, Byline, Publication Date, and Rights Information.
Usage: PRISM is widely adopted by publishing companies for managing content in multi-channel environments (print, web, mobile).
Example:
```
<prism:articleTitle>Universal Content Data Models in Publishing</prism:articleTitle>
<prism:byline>John Editor</prism:byline>
<prism:publicationDate>2024-09-07</prism:publicationDate>
```

6. Open Graph Protocol (OGP):
Context: Developed by Facebook, the Open Graph Protocol is a data model that allows content from websites to be represented in a universal way when shared on social media platforms.
Model: It uses metadata elements like "og
", "og
", and "og
" to describe content that will appear in social media snippets.
Usage: OGP is used across social media platforms (e.g., Facebook, LinkedIn) to ensure that shared content displays consistently.
Example:
```
<meta property="og:title" content="Universal Content Data Models" />
<meta property="og:description" content="An overview of data models used across industries." />
<meta property="og:image" content="https://example.com/image.jpg" />
```

These examples represent different approaches to universal content data models that have been developed to solve the challenges of organizing, describing, and managing content in a standardized way across various platforms and industries. They help ensure that data can be easily shared, understood and used consistently in different contexts.

### Does any one of them can be used as the Universal content model at least for some simple web-site and/or application?

There is a lack of data that we need to handle data objects. For example, unique identifiers and keys. Also, we need better control on how different items of content connected with each other.

## References

TBD

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
