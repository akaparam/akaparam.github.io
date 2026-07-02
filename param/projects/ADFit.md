# ADFit - C# SDK for ADF <-> HTML conversions

ADFit is a C# SDK for converting HTML to Atlassian Document Format (ADF).

### The Challenge

ADO uses HTML to markup their work item descriptions and JIRA uses ADF. Apparently there is no official C# SDK to do the same. I had the motivation to build a utility which can convert HTML to ADF so that I can migrate the rich text from ADO work items to JIRA issues.

> Also, Shouldn't mention it, but JIRA's ADF format is just soooo bad to work with. It has very weird validations which are not something we can test locally and when you try to make calls to the api with the created object it throws errors. 

### The Solution
To be able to easily map HTML markup into the ADF's json format in C# with support for static object analysis and ease of use with the .NET ecosystem I built `ADFit` with rich domain models and compile-time validations, mapping the validations from the documentation 1:1 (which btw took me weeks to finaize :upside_down:)

It even includes support for:
- Blockquotes
- tables
- lists
- etc.

Built in .NET 8 with <3

**GitHub URL**: https://github.com/btwparam/ADFit.git