# Considering AEO when Writing for UX

Search is just as relevant as it ever was to UX writing. But now it combines standard search with AI tools.

For example, when you search in Google now, you often get an AI-generated answer (AEO / AI Overviews) instead of just a list of links. So you need to optimize content so that within your document, the AI tool surfaces what is most relevant using hierarchy.

But that doesn't mean you don't need to consider the bigger picture.

You still need your page to be authoritative enough to be surfaced in the first place. Otherwise, the answer may come from a competitor's page, no matter how well structured your own content is within itself.

**Getting AEO to choose the document in the first place is the biggest part of AEO.** If your document does not get surfaced, your content will not come up at all in an answer.

You need to make your source authoritative enough, using standard SEO, that it gets surfaced to any relevant question (instead of your competitor).

## What does this mean?

For example, a user may type:

> What are the benefits of Chime's bill pay?

But if NerdWallet, Forbes, or Bankrate have more authoritative pages reviewing or describing Chime's bill pay than Chime's own website does, then the AI-generated answer will be based on those third-party sources instead of Chime's content.

Second, once it is surfaced by AEO, you need to make sure that the information is hierarchical and digestible, just like you would do for a chatbot.

You can't really measure whether the internet will crawl your page and surface it. You still need to rely on technical and content-level SEO for that.

There are several things that make something authoritative or not, not just hierarchy.

Authority comes from things like:
- backlinks
- domain trust
- citations
- freshness
- topical coverage
- brand recognition
- historical presence in training data
- engagement signals
- technical SEO
- consistency across sources

Hierarchy is not a primary authority signal, but poor hierarchy can indirectly hurt a page’s ability to be selected.
Hierarchy does not guarantee authority. 

As long as you have sound hierarchy (or on-page SEO), hierarchy mostly affects:
- what happens after a document has already been chosen.

## But here is an example of the other part — the UX structure.

One of the biggest influencers in UX structure is hierarchy. Hierarchy on the page begins with headings.

You can use tools like Contentful, or write in Markdown in Visual Studio Code, or even in Google Docs.

The tool doesn't really matter.

What matters is how the content is structured:
- where the answer appears
- what is under which heading
- how sections are ordered
- how the content is chunked

This hierarchy is what helps an AI tool decide what is most important and what it should surface within your document once it has already been selected.

## You might be thinking that structuring and creating hierarchy through headings sounds like on-page SEO.

Here are the key differences:

In on-page SEO, the headings and the content below them can flow from top to bottom and make sense as one continuous page.

But when optimizing content for AI, you need to think in stand-alone chunks.

**An AI tool does not read a page the same way that a web crawler does.** It retrieves chunks of information as stand-alone units.

So you need to make stand-alone units of content, keeping context in mind, so that the answer will be complete and make sense.

## What does this look like in practice?

Using the same example as before:

A user types:

> What are the benefits of Chime's bill pay?

Even if Chime's page does get surfaced by AEO (because it is authoritative enough), the AI still has to decide what to pull from within that page.

If the benefits are buried halfway down the page, mixed into long paragraphs, or not clearly under a heading like "Benefits of Chime Bill Pay," the AI may:
- miss key benefits
- summarize the wrong section
- surface incomplete or less relevant information
- not give the reader the information that you had hoped if they ask an unanticipated question

But if the same content is structured so that:
- the benefits are under a clear heading
- the main benefits are listed first
- the content is chunked into short, scannable sections

then the AI is much more likely to surface the correct answer.

## You need to group by context.

What does this look like in practice?

Using the same example as before:

A user types:

> What are the benefits of Chime's bill pay?

But now imagine the user instead types:

> Does Chime charge fees for bill pay?

### Bad structure (same content, not grouped by context)

*(This content is made up as a demo example. It is not from Chime's website.)*

Chime offers a range of mobile banking features designed to make managing money easier. Users can send money, receive direct deposits, and manage their accounts through the app.

Bill pay is one of many tools available to customers. It allows users to pay bills electronically instead of mailing checks. Some users like that payments can be scheduled in advance. Chime also sends notifications when payments are processed.

Chime does not charge monthly fees and has no minimum balance requirements. It also offers early access to direct deposits.

In this version:
- the sentence about "no monthly fees" is not clearly tied to bill pay
- it's mixed in with unrelated product info
- it's not under a heading about fees
- it's not in a stand-alone chunk with context

So, using this dummy content, which is not really from Chime's site, when a user asks:

> Does Chime charge fees for bill pay?

the AI may:
- pull the wrong sentence ("Chime does not charge monthly fees")
- answer the wrong question (about account fees, not bill pay fees)
- hallucinate a fee or say "it depends"
- give an incomplete or misleading answer

---

This is a start to understanding the bigger picture. UX writing and its relationship to AI tools is evolving every day.
