---
title: Content Structure
---
<Meta title="Content Structure" />

Content at Lightstep can take many different forms to serve different audiences. Because they are all delivered over the web, and to enhance our branding, they all use the same basic structure. 

Read this guideline to understand the different content types at Lightstep and the components used in our content.

## Content types

### Product UI text (micro-content)	
**Description**:
UI text is the content (descriptions, help text, and so on) displayed in our [web app](https://app.lightstep.com).

**Owner(s)**:
The design team creates the text when they design the page.<br>
PM, Marketing, Eng, and Docs all help to refine the final copy

**Audience**:
Anyone using the Lightstep app. Most helpful to new users.

**Guidelines**:
UI Text helps users understand what they're looking at on a page, but they will ignore a wall of text.
* Be as concise as possible
* Use a friendly, but confident tone
* Use present tense
    * Yes: The Instrumentation Quality score checks for these attribute keys...
    * No: The Instrumentation Quality score will check for these attribute keys...

### Blog posts	
**Description**:
Blog posts live on our [website](https://lightstep.com/blog) and are an informal way for us to inform and educate our customers. Unlike product docs, they can show our personalities, entertain, and are rarely updated to match our latest release.

**Owner(s)**:
Marketing - but anyone in the company can create a blog post.

**Audience**:
Anyone visiting the Lightstep website or redirected directly from a social post or other website. 

**Guidelines**:
<p style="color:red;">Do we have stds for blog posts?</p>

### Product doc topics
**Description**:
Product docs live in our [Learning Portal](https://docs.lightstep.com/docs/) and are the "official" documentation for our product. Unlike blog posts, they must be updated when the product changes or adds new features. 

**Owner(s)**:
Product Docs

**Audience**:
Customers and potential customers wanting to learn how to use Lightstep. 

**Guidelines**:
Legally, the *can* serve as a contract for what the product does, so above all else, they must be factual.
* Non-emotional, but they must consider the emotions of the user. 
* Concise, explanatory, and complete. Consider all angles/questions that the user might have.
* Refrain from using "we" (use "you" whenever possible) and other tutorial type tone.


### Learning paths	
**Description**:
Learning paths also live in our [Learning Portal](https://docs.lightstep.com/paths/) and are tutorials that combine and extend the product docs. While the product docs tend to be feature-based, learning paths strive to combine features to mimic real-world use cases. 

**Owner(s)**:
Product Docs

**Audience**:
Customers and potential customers wanting to extend their Lightstep knowledge or prefer tutorials as a way to learn. 

**Guidelines**:
Learning paths are much less formal than product docs.
* The tone is more enthusiastic and supportive. 
* Use "we" and other tutorial-type verbiage.
* Short in duration and complexity to reduce fallout.


### Early access docs	
**Description**:	
Early access docs are for our CA (controlled availability) customers when the content must be password-protected (most CA content is _not_ early-access). 

**Owner(s)**:
Product Docs

**Audience**:
Customers participating in a controlled release. 

**Guidelines**:
Early access content can be considered "beta" as it is often not complete or final. They follow the same guidelines as product docs, except:
* Screenshots and procedural content can be out-of-date if expected to change multiple times during the CA period 
* Content does not need to be as polished, but should be kept as correct as possible.

### OTel docs	
**Description**:	
OTel docs are similar to product docs, but specifically about using OpenTelemetry and are not necessarily Lightstep specific. 

**Owner(s)**:
DevRel

**Audience**:
Developers looking to use OpenTelemetry and not necessarily wanting to use Lightstep to consume the telemetry data.

**Guidelines**:
While OTel docs are vendor-neutral, they do promote Lightstep where they can and must maintain the Lightstep brand and enhance our SEO for the OpenTelemetry space. They have the same guidelines as product docs, plus:
* Should use Lightstep in all examples for consuming telemetry data.
* Use an authoritative tone to reflect Lightstep's expertise in this area.

### Email
*Description**	
Lightstep regularly sends emails for customer and prospective outreach.

**Owner(s)**:
Marketing and Customer Success

**Audience**:
Prospective, new, and existing customers

**Guidelines**:
<p style="color:red;">This is from the old style guide. Still accurate?</p>
*   Personalize emails with meaningful content for high-value targets
*   Provide a way to opt out of future emails
*   Be persistent but don’t be overly pushy
*   Be brief and to the point
*   Use a conversational tone


### Social media
**Descriptiton**:	
Lightstep focuses on [Twitter](https://twitter.com/LightstepHQ) and [LinkedIn](https://www.linkedin.com/company/lightstep/) for our social posts.

**Owner(s)**:
Marketing, but any employee can post/re-post about Lightstep to their own accounts

**Audience**:
DevOps and anyone interested in Observability, as well as existing customers

**Guidelines**:
<p style="color:red;">Do we have existing guidelines?</p>


## Content components
Following are guidelines for using the different components in our deliverables.

Where guidelines may affect only specific deliverable types, the guideline is prefaced by the type:
* _PD_=product docs
* _LP_=learning path
* _OT_=OTel docs

### Page titles		
Use sentence case, but do capitalize proper nouns.
Use `<h1>`.
Don't use bold, italics, or standard punctuation.
Try to incorporate keywords for SEO.
_pd_ Start with a verb
_lp_ Start with the step number, followed by a colon and then a verb (for example, **Step 1: Notice a latency regression**)	

### Meta Description Tags
All web-based pages should use the `<description>` tag to gain SEO. Content in this tag is used by search engines and displays as the description for the page in the search results.

Use keywords in the description, but don't overdo it. Keep description between 50-160 characters (Google truncates to ~155-160). Content for each page should be unique.

### Headings
Use sentence case, but do capitalize proper nouns.
Use progressive heading tags, starting with `<h2>`. Try to not go smaller than `<h4>`
Don't use bold, italics, or standard punctuation in headings.

### Notes/Callouts
_PD, LP, OT_

Use callouts for content that's adjacent to the body content or that needs attention from the reader - it's content that the reader should know/understand before continuing.

Lightstep uses three types of callouts:
* **Tip**: Content is good to know, a shortcut, or a best practice
* **Info**: Content is important to understand or highlight
* **Caution**: Not following or understanding the content can lead to errors or lost data

When using callouts, note the following:
* Keep callout content short.
* Place callouts after the text they pertain to.
* Make sure the callout isn't actually a prerequisite.
* When using in steps, make sure that the user doesn't need that information before they begin the step or even the task itself.
* Add links to more information when applicable.


### Code examples
Use code examples when you need to:
* Show readers example code to help explain content
* Provide code for readers to copy, paste, and use in order to complete a task

If the code is longer than one line, use a code block component. Otherwise use inline code font on a separate line. It's very important to ensure the code is mistake-free. Place the code after the content that describes it.

_PD_ If you need to provide similar code for different languages or environments, use tabs with your code block instead of separate code blocks, with the language or environment as the tab title. ![Tabbed code example](/images/code.png)

### Accordion panels	
_PD, LP_

Use accordion panels when you need to provide a small amount of content that new users may need and you don't want them leaving the page to get it, or when you want to provide content that only people looking for more knowledge might need and there's no existing content to link to.

Example for new users: ![New user accordion](/images/new_accord.png)

Example for information: ![Info accordion](/images/info_accord.png)

### Procedures (steps)		
Always place tasks that require more than one step in lists. Lists make it easier for the reader to follow along, without losing their place.

If the steps have to be done in a certain order, use a numbered list. If the order doesn't matter, you can use a bulleted list.

### Graphics
Graphics are essential for orienting the user and also for visually breaking up a page. 

Always provide alt text for any image.

If the surrounding content is about a particular part of the screenshot, highlight that area using an arrow or box (or both).

For blog posts, be sure the first image that appears is suitable for a Twitter update. (The first image will often get embedded in the tweet.)If this first image is an animated GIF, be sure the first frame is suitable as well.
