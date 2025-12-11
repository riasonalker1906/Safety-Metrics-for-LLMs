From: https://cloud.google.com/blog/topics/threat-intelligence/ai-powered-voice-spoofing-vishing-attacks
AI-Powered Voice Spoofing for Next-Gen Vishing Attacks
"AI-powered voice cloning can now mimic human speech with uncanny precision, injecting a potent dose of realism into phishing schemes. This technology, once the stuff of science fiction, is now readily accessible, allowing attackers to impersonate trusted individuals with alarming accuracy. The implications are profound, particularly for vishing (voice phishing) attacks, where a familiar voice can bypass our natural skepticism and lead to devastating consequences."
"While AI-powered voice cloning offers undeniable advantages in legitimate applications, its potential for misuse in vishing attacks demands vigilance. By understanding the technology, recognizing the red flags, and implementing robust security measures, we can mitigate the risks and protect ourselves from this evolving threat."
"AI-powered voice cloning can now mimic human speech with uncanny precision, injecting a potent dose of realism into phishing schemes. This technology, once the stuff of science fiction, is now readily accessible, allowing attackers to impersonate trusted individuals with alarming accuracy. The implications are profound, particularly for vishing (voice phishing) attacks, where a familiar voice can bypass our natural skepticism and lead to devastating consequences."
"Deepfake audio, also known as voice cloning or audio deepfakes, is a type of synthetic media in which a person's voice is replicated using artificial intelligence (AI) algorithms. This technology can create highly convincing fake audio clips that sound like a real person saying things they never actually said. The creation of deepfake audio typically involves training machine learning models on large datasets of a target's voice recordings. These models learn the unique characteristics of the person's speech patterns, intonation, and timbre."
"Deepfake audio has various applications, both positive and negative. On the positive side, it can be used in entertainment, such as in movies or video games to recreate voices of deceased actors or to dub content in different languages. It also has potential in accessibility, helping those who have lost their ability to speak. However, the technology raises serious concerns about misinformation, fraud, and privacy invasion. Malicious actors could use deepfake audio to impersonate public figures, spread false information, or commit scams by mimicking voices of trusted individuals."
"Detecting deepfake audio is challenging but possible through advanced analysis techniques that look for artifacts or inconsistencies in the audio signal that are not present in natural speech."
"The rise of accessible AI tools has democratized voice cloning, making it easier for even non-technical attackers to create convincing deepfakes. This lowers the barrier to entry for sophisticated vishing campaigns, potentially leading to an increase in both the volume and success rate of these attacks."
"While AI-powered voice cloning offers undeniable advantages in legitimate applications, its potential for misuse in vishing attacks demands vigilance. By understanding the technology, recognizing the red flags, and implementing robust security measures, we can mitigate the risks and protect ourselves from this evolving threat."
From: https://blog.google/technology/ai/ai-image-verification-gemini-app/
(Note: This is for images, but Gemini's safety framework extends to multimodal, including audio/voice. No direct voice watermarking, but similar principles apply.)
"Our new Gemini app feature allows you to verify Google AI images and determine whether content was created or edited by AI."
"Google DeepMind’s SynthID watermarking technology is used to embed imperceptible watermarks directly into the pixels of AI-generated images. SynthID is designed to remain detectable even after modifications like adding filters, changing colors, and saving with lossy compression — common changes people make to images."
"By integrating SynthID into our image generation models, we’re making it easier for people to verify the origin and authenticity of AI-generated content."
From: https://ai.google.dev/gemini-api/docs/safety-guidance
"This document is meant to introduce you to some safety risks that can arise when using LLMs, and recommend emerging safety design and development practices that can help you mitigate them."
"Using trained classifiers to label each prompt with potential harms or adversarial signals. Different strategies can then be employed on how to handle the request based on the type of harm detected. For example, If the input is overtly adversarial or abusive in nature, it could be blocked and instead output a pre-scripted response."
"Putting safeguards in place against deliberate misuse such as assigning each user a unique ID and imposing a limit on the volume of user queries that can be submitted in a given period. Another safeguard is to try and protect against possible prompt injection. Prompt injection, much like SQL injection, is a way for malicious users to design an input prompt that manipulates the output of the model, for example, by sending an input prompt that instructs the model to ignore any previous examples. See the Generative AI Prohibited Use Policy for details about deliberate misuse."
"Blocking unsafe inputs and filtering output before it is shown to the user. In simple situations, blocklists can be used to identify and block unsafe words or phrases in prompts or responses, or require human reviewers to manually alter or block such content."
From: https://www.dhs.gov/sites/default/files/2024-10/24_0927_ia_aep-impact-ai-on-criminal-and-illicit-activities.pdf
(Note: This DHS report mentions Gemini as an example of generative AI used in attacks, including voice cloning for elder scams.)
"Creating audio deepfakes, also referred to as voice cloning, is the use of AI to generate convincing fake audio of someone’s voice. Despite some beneficial uses, like generating voices for people with impairments, there have proven to be many malicious uses as well. Some examples include scammers trying to fool a family member that a child is in trouble, and needs immediate financial assistance."
"Illicit use case: Criminals can use voice-cloning to mimic the voice of a victim’s friend, loved one, or colleague, making scams much more believable."
"The use of AI in elder fraud is a growing concern, as it enables more convincing and sophisticated scams targeting vulnerable older adults. These scams often involve the use of AI technologies like voice cloning and emergency scams, exploiting the trust and emotions of the elderly. In a real-world incident, an 82-year-old man in Texas was defrauded of $17,000 after receiving a call from someone using AI to clone his son-in-law's voice, falsely claiming to be in jail and in need of bail money. Another case involved a woman who received a call from what sounded like her daughter, claiming to be kidnapped. The AI-generated voice was so convincing that she nearly wired money to the scammers before realizing it was a fraud. The U.S. Senate Committee on Aging has highlighted this growing threat in its annual fraud report, noting that AI-driven scams targeting older Americans are on the rise, with estimated losses reaching $1.6 billion in 2022."
"Watermarking Techniques Embed markers into AI- generated content to help trace its origin and identify potential misuse. Adversaries can remove or alter watermarks. Identifying watermarks in large datasets can be resource-intensive. Develop more robust watermarking techniques (e.g., based on strong encryption) that are harder to remove. Apply generative AI techniques to automate the detection of watermarked content."
"Deepfake Detection Machine learning models are trained on vast datasets of real and fake videos or images to identify inconsistencies that signal AI synthesis or manipulation. Deepfake technology evolves rapidly, making detection challenging. Detection systems can produce false positives or miss sophisticated fakes. Use hybrid detection models that combine multiple detection techniques to improve accuracy. Invest in ongoing research to stay ahead of deepfake advancements."
"In many of these attacks, adversaries use a generative AI app such as ChatGPT or Google Gemini to generate text (and sometimes images) in great volume and with more fluent grammar than a typical non-native speaker."

Generative artificial intelligence models are powerful tools, but they are not
without their limitations. Their versatility and applicability can sometimes
lead to unexpected outputs, such as outputs that are inaccurate, biased, or
offensive. Post-processing, and rigorous manual evaluation are essential to
limit the risk of harm from such outputs.

The models provided by the Gemini API can be used for a wide variety of
generative AI and natural language processing (NLP) applications. Use of these
functions is only available through the Gemini API or the Google AI Studio web
app. Your use of Gemini API is also subject to the [Generative AI Prohibited Use
Policy](https://policies.google.com/terms/generative-ai/use-policy) and the
[Gemini API terms of service](https://ai.google.dev/terms).

Part of what makes large language models (LLMs) so useful is that they're
creative tools that can address many different language tasks. Unfortunately,
this also means that large language models can generate output that you don't
expect, including text
that's offensive, insensitive, or factually incorrect. What's more, the
incredible versatility of these models is also what makes it difficult to
predict exactly what kinds of undesirable output they might produce. While the
Gemini API has been designed with [Google's AI
principles](https://ai.google/principles/) in mind, the onus is on developers to
apply these models responsibly. To aid developers in creating safe, responsible
applications, the Gemini API has some built-in content filtering as well as
adjustable safety settings across 4 dimensions of harm. Refer to the
[safety settings](https://ai.google.dev/gemini-api/docs/safety-settings) guide to learn more.

This document is meant to introduce you to some safety risks that can arise when
using LLMs, and recommend emerging safety design and development
recommendations. (Note that laws and regulations may also impose restrictions,
but such considerations are beyond the scope of this guide.)

The following steps are recommended when building applications with LLMs:

- Understanding the safety risks of your application
- Considering adjustments to mitigate safety risks
- Performing safety testing appropriate to your use case
- Soliciting feedback from users and monitoring usage

The adjustment and testing phases should be iterative until you reach
performance appropriate for your application.

![Model implementation cycle](https://ai.google.dev/static/gemini-api/docs/images/safety_diagram.png)

## Understand the safety risks of your application

In this context, safety is being defined as the ability of an LLM to avoid
causing harm to its users, for example, by generating toxic language or content
that promotes stereotypes. The models available through the Gemini API have been
designed with [Google's AI principles](https://ai.google/principles/) in mind
and your use of it is subject to the [Generative AI Prohibited Use
Policy](https://policies.google.com/terms/generative-ai/use-policy). The API
provides built-in safety filters to help address some common language model
problems such as toxic language and hate speech, and striving for inclusiveness
and avoidance of stereotypes. However, each application can pose a different set
of risks to its users. So as the application owner, you are responsible for
knowing your users and the potential harms your application may cause, and
ensuring that your application uses LLMs safely and responsibly.

As part of this assessment, you should consider the likelihood that harm could
occur and determine its seriousness and mitigation steps. For example, an
app that generates essays based on factual events would need to be more careful
about avoiding misinformation, as compared to an app that generates fictional
stories for entertainment. A good way to begin exploring potential safety risks
is to research your end users, and others who might be affected by your
application's results. This can take many forms including researching state of
the art studies in your app domain, observing how people are using similar apps,
or running a user study, survey, or conducting informal interviews with
potential users.  

#### Advanced tips

- Speak with a diverse mix of prospective users within your target population about your application and its intended purpose so as to get a wider perspective on potential risks and to adjust diversity criteria as needed.
- The [AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) released by the U.S. government's National Institute of Standards and Technology (NIST) provides more detailed guidance and additional learning resources for AI risk management.
- DeepMind's publication on the [ethical and social risks of harm from language models](https://arxiv.org/abs/2112.04359) describes in detail the ways that language model applications can cause harm.

## Consider adjustments to mitigate safety risks

Now that you have an understanding of the risks, you can decide how to mitigate
them. Determining which risks to prioritize and how much you should do to try to
prevent them is a critical decision, similar to triaging bugs in a software
project. Once you've determined priorities, you can start thinking about the
types of mitigations that would be most appropriate. Often simple changes can
make a difference and reduce risks.

For example, when designing an application consider:

- **Tuning the model output** to better reflect what is acceptable in your application context. Tuning can make the output of the model more predictable and consistent and therefore can help mitigate certain risks.
- **Providing an input method that facilities safer outputs.** The exact input you give to an LLM can make a difference in the quality of the output. Experimenting with input prompts to find what works most safely in your use-case is well worth the effort, as you can then provide a UX that facilitates it. For example, you could restrict users to choose only from a drop-down list of input prompts, or offer pop-up suggestions with descriptive phrases which you've found perform safely in your application context.
- **Blocking unsafe inputs and filtering output before it is shown to the
  user.** In simple situations, blocklists can be used to identify and block
  unsafe words or phrases in prompts or responses, or require human reviewers
  to manually alter or block such content.

  | **Note:** Automatically blocking based on a static list can have unintended results such as targeting a particular group that commonly uses vocabulary in the blocklist.
- **Using trained classifiers to label each prompt with potential harms or
  adversarial signals.** Different strategies can then be employed on how to
  handle the request based on the type of harm detected. For example, If the
  input is overtly adversarial or abusive in nature, it could be blocked and
  instead output a pre-scripted response.

  #### Advanced tip

  - If signals determine the output to be harmful, the application can employ the following options:
    - Provide an error message or pre-scripted output.
    - Try the prompt again, in case an alternative safe output is generated, since sometimes the same prompt will elicit different outputs.

  <br />

- **Putting safeguards in place against deliberate misuse** such as assigning
  each user a unique ID and imposing a limit on the volume of user queries
  that can be submitted in a given period. Another safeguard is to try and
  protect against possible prompt injection. Prompt injection, much like SQL
  injection, is a way for malicious users to design an input prompt that
  manipulates the output of the model, for example, by sending an input prompt
  that instructs the model to ignore any previous examples. See the
  [Generative AI Prohibited Use Policy](https://policies.google.com/terms/generative-ai/use-policy)
  for details about deliberate misuse.

- **Adjusting functionality to something that is inherently lower risk.**
  Tasks that are narrower in scope (e.g., extracting keywords from passages of
  text) or that have greater human oversight (e.g., generating short-form
  content that will be reviewed by a human), often pose a lower risk. So for
  instance, instead of creating an application to write an email reply from
  scratch, you might instead limit it to expanding on an outline or suggesting
  alternative phrasings.

## Perform safety testing appropriate to your use case

Testing is a key part of building robust and safe applications, but the extent,
scope and strategies for testing will vary. For example, a just-for-fun haiku
generator is likely to pose less severe risks than, say, an application designed
for use by law firms to summarize legal documents and help draft contracts. But
the haiku generator may be used by a wider variety of users which means the
potential for adversarial attempts or even unintended harmful inputs can be
greater. The implementation context also matters. For instance, an application
with outputs that are reviewed by human experts prior to any action being taken
might be deemed less likely to produce harmful outputs than the identical
application without such oversight.

It's not uncommon to go through several iterations of making changes and testing
before feeling confident that you're ready to launch, even for applications that
are relatively low risk. Two kinds of testing are particularly useful for AI
applications:

- **Safety benchmarking** involves designing safety metrics that reflect the
  ways your application could be unsafe in the context of how it is likely to
  get used, then testing how well your application performs on the metrics
  using evaluation datasets. It's good practice to think about the minimum
  acceptable levels of safety metrics before testing so that 1) you can
  evaluate the test results against those expectations and 2) you can gather
  the evaluation dataset based on the tests that evaluate the metrics you care
  about most.

  #### Advanced tips

  - Beware of over-relying on "off the shelf" approaches as it's likely you'll need to build your own testing datasets using human raters to fully suit your application's context.
  - If you have more than one metric you'll need to decide how you'll trade off if a change leads to improvements for one metric to the detriment of another. Like with other performance engineering, you may want to focus on worst-case performance across your evaluation set rather than average performance.
- **Adversarial testing** involves proactively trying to break your
  application. The goal is to identify points of weakness so that you can take
  steps to remedy them as appropriate. Adversarial testing can take
  significant time/effort from evaluators with expertise in your application ---
  but the more you do, the greater your chance of spotting problems,
  especially those occurring rarely or only after repeated runs of the
  application.

  - Adversarial testing is a method for systematically evaluating an ML model with the intent of learning how it behaves when provided with malicious or inadvertently harmful input:
    - An input may be malicious when the input is clearly designed to produce an unsafe or harmful output-- for example, asking a text generation model to generate a hateful rant about a particular religion.
    - An input is inadvertently harmful when the input itself may be innocuous, but produces harmful output -- for example, asking a text generation model to describe a person of a particular ethnicity and receiving a racist output.
  - What distinguishes an adversarial test from a standard evaluation is the composition of the data used for testing. For adversarial tests, select test data that is most likely to elicit problematic output from the model. This means probing the model's behavior for all the types of harms that are possible, including rare or unusual examples and edge-cases that are relevant to safety policies. It should also include diversity in the different dimensions of a sentence such as structure, meaning and length. You can refer to the [Google's Responsible AI
    practices in
    fairness](https://ai.google/responsibilities/responsible-ai-practices/?category=fairness) for more details on what to consider when building a test dataset.  

    #### Advanced tips

    - Use [automated testing](https://www.deepmind.com/blog/red-teaming-language-models-with-language-models) instead of the traditional method of enlisting people in 'red teams' to try and break your application. In automated testing, the 'red team' is another language model that finds input text that elicit harmful outputs from the model being tested.

  | **Note:** LLMs are known to sometimes produce different outputs for the same input prompt. Multiple rounds of testing may be needed to catch more of the problematic outputs.

## Monitor for problems

No matter how much you test and mitigate, you can never guarantee perfection, so
plan upfront how you'll spot and deal with problems that arise. Common
approaches include setting up a monitored channel for users to share feedback
(e.g., thumbs up/down rating) and running a user study to proactively solicit
feedback from a diverse mix of users --- especially valuable if usage patterns are
different to expectations.  

#### Advanced tips

- When users give feedback to AI products, it can greatly improve the AI performance and the user experience over time by, for example, helping you choose better examples for prompt tuning. The [Feedback and Control chapter](https://pair.withgoogle.com/chapter/feedback-controls/) in [Google's People and AI guidebook](https://pair.withgoogle.com/guidebook/chapters) highlights key considerations to take into account when designing feedback mechanisms.

## Next steps

- Refer to the [safety settings](https://ai.google.dev/gemini-api/docs/safety-settings) guide to learn about the adjustable safety settings available through the Gemini API.
- See the [intro to prompting](https://ai.google.dev/gemini-api/docs/prompting-intro) to get started writing your first prompts.

This page includes additional usage policies for the Gemini API.

## Abuse monitoring

Google is committed to the responsible development and use of AI. To ensure the
safety and integrity of the Gemini API, we have created these policy guidelines.
By using the Gemini API, you agree to the following guidelines, the [Gemini API
Additional Terms of Service](https://ai.google.dev/gemini-api/terms) and Generative AI [Prohibited
Use Policy](https://policies.google.com/terms/generative-ai/use-policy).

### How We Monitor for Misuse

Google's Trust and Safety Team employs a combination of automated and manual
processes to detect potential misuse of the Gemini API and enforce our policies.

- **Automated Detection:** Automated systems scan API usage for violations of our Prohibited Use Policy, such as hate speech, harassment, sexually explicit content, and dangerous content.
- **Manual Detection:** If a project consistently exhibits suspicious activity, it may be flagged for manual review by authorized Google personnel.

### How We Handle Data

To help with abuse monitoring, Google retains the following data for fifty-five
(55) days:

- **Prompts:** The text prompts you submit to the API.
- **Contextual Information:** Any additional context you provide with your prompts.
- **Output:** The responses generated by the Gemini API.

### How We Investigate Potential Issues

When prompts or model outputs are flagged by safety filters and abuse detection
systems described above, authorized Google employees may assess the flagged
content, and either confirm or correct the classification or determination based
on predefined guidelines and policies. Data can be accessed for human review
only by authorized Google employees via an internal governance assessment and
review management platform. When data is logged for abuse monitoring, it is used
solely for the purpose of policy enforcement and is not used to train or
fine-tune any AI/ML models.

### Working with You on Policy Compliance

If your use of Gemini doesn't align with our policies, we may take the following
steps:

- **Get in touch:** We may reach out to you through email to understand your use case and explore ways to bring your usage into compliance.
- **Temporary usage limits:** We may limit your access to the Gemini API.
- **Temporary suspension:** We may temporarily pause your access to the Gemini API.
- **Account closure:** As a last resort, and for serious violations, we may permanently close your access to the Gemini API and other Google services.

### Scope

These policy guidelines apply to the use of the Gemini API and AI Studio.

## Inline Preference Voting

In Google AI Studio, you might occasionally see a side-by-side comparison of two
different responses to your prompt. This is part of our Inline Preference Voting
system. You'll be asked to choose which response you prefer. This helps us
understand which model outputs users find most helpful.

### Why are we doing this?

We're constantly working to improve our AI models and services. Your feedback
through Inline Preference Voting helps us provide, improve, and develop Google
products and services and machine learning technologies, including Google's
enterprise features, products and services, consistent with the
[Gemini API Additional Terms of Service](https://ai.google.dev/gemini-api/terms) and
[Privacy Policy](https://policies.google.com/privacy).

### What data is included in Feedback?

To make informed decisions about our models, we collect certain data when you
participate in Inline Preference Voting:

- **Prompts and Responses:** We record all prompts and responses, including any uploaded content, in the conversation you submitted feedback about. We also record the two response options that you selected from. This helps us understand the context of your preference.
- **Your Vote:** We record which response you preferred. This is the core of the feedback we're collecting.
- **Usage Details:** This includes information about which model generated the response and other technical and operational details about your usage of this feature.

### Your Privacy

We take your privacy seriously. Google takes steps to protect your privacy as
part of this process. This includes disconnecting this data from your Google
Account, API key, and Cloud project before reviewers see or annotate it. **Do
not submit feedback on conversations that include sensitive, confidential, or
personal information.**

### Opting Out

You'll have the option to skip the Inline Preference Voting when it appears.

Thank you for helping us improve Google AI Studio!

GENERATIVE AI PROHIBITED USE POLICY
Last Modified: December 17, 2024
Generative AI models can help you explore, learn, and create. We expect you to engage with them in a responsible, legal, and safe manner. The following restrictions apply to your interactions with generative AI in the Google products and services that refer to this policy.
1. Do not engage in dangerous or illegal activities, or otherwise violate applicable law or regulations. This includes generating or distributing content that:
a. Relates to child sexual abuse or exploitation.
b. Facilitates violent extremism or terrorism.
c. Facilitates non-consensual intimate imagery.
d. Facilitates self-harm.
e. Facilitates illegal activities or violations of law -- for example, providing instructions for synthesizing or accessing illegal or regulated substances, goods, or services.
f. Violates the rights of others, including privacy and intellectual property rights -- for example, using personal data or biometrics without legally-required consent.
g. Tracks or monitors people without their consent.
h. Makes automated decisions that have a material detrimental impact on individual rights without human supervision in high-risk domains -- for example, in employment, healthcare, finance, legal, housing, insurance, or social welfare.
2. Do not compromise the security of others’ or Google’s services. This includes generating or distributing content that facilitates:
a. Spam, phishing, or malware.
b. Abuse of, harm to, interference with, or disruption to Google’s or others’ infrastructure or services.
c. Circumvention of abuse protections or safety filters -- for example, manipulating the model to contravene our policies.
3. Do not engage in sexually explicit, violent, hateful, or harmful activities. This includes generating or distributing content that facilitates:
a. Hatred or hate speech.
b. Harassment, bullying, intimidation, abuse, or the insulting of others.
c. Violence or the incitement of violence.
d. Sexually explicit content -- for example, content created for the purpose of pornography or sexual gratification.
4. Do not engage in misinformation, misrepresentation, or misleading activities. This includes:
a. Frauds, scams, or other deceptive actions.
b. Impersonating an individual (living or dead) without explicit disclosure, in order to deceive.
c. Facilitating misleading claims of expertise or capability in sensitive areas -- for example in health, finance, government services, or the law, in order to deceive.
d. Facilitating misleading claims related to governmental or democratic processes or harmful health practices, in order to deceive.
e. Misrepresenting the provenance of generated content by claiming it was created solely by a human, in order to deceive.

We may make exceptions to these policies based on educational, documentary, scientific, or artistic considerations, or where harms are outweighed by substantial benefits to the public.


<br />

Effective November 20, 2025

To use[Gemini API](https://ai.google.dev/docs/gemini_api_overview),[Google AI Studio](https://aistudio.google.com), and the other Google developer services that reference these terms (collectively, the "**APIs** " or "**Services** "), you must accept (1) the[Google APIs Terms of Service](https://developers.google.com/terms)(the "**API Terms** "), and (2) these Gemini API Additional Terms of Service (the "**Additional Terms**"). Terms that are not defined in these Additional Terms have the meanings given in the API Terms.

## Age Requirements

You must be 18 years of age or older to use the APIs. You also will not use the Services as part of a website, application, or other service (collectively, "**API Clients**") that is directed towards or is likely to be accessed by individuals under the age of 18.

## Use Restrictions

You may only access the Services (or make API Clients available to users) within an[available region](https://ai.google.dev/available_regions). You may use only Paid Services when making API Clients available to users in the European Economic Area, Switzerland, or the United Kingdom.

You may not use the Services to develop models that compete with the Services (e.g., Gemini API or Google AI Studio). You also may not attempt to reverse engineer, extract or replicate any component of the Services, including the underlying data or models (e.g., parameter weights).

In addition to the "[API Prohibitions](https://developers.google.com/terms#a_api_prohibitions)" section in the API Terms, you must comply with our[Prohibited Use Policy](https://policies.google.com/terms/generative-ai/use-policy), which provides additional details about appropriate conduct when using the Services.

The Services include safety features to block harmful content, such as content that violates our[Prohibited Use Policy](https://policies.google.com/terms/generative-ai/use-policy). You may not attempt to bypass these protective measures or use content that violates the API Terms or these Additional Terms. You should only lower[safety settings](https://ai.google.dev/docs/safety_setting_gemini)if necessary and appropriate for your use case. Applications with less restrictive safety settings may be subject to Google's review and approval.

You may not use the Services in clinical practice, to provide medical advice, or in any manner that is overseen by or requires clearance or approval from a medical device regulatory agency.

## Use of Generated Content

Some of our Services allow you to generate original content. Google won't claim ownership over that content. You acknowledge that Google may generate the same or similar content for others and that we reserve all rights to do so.

As required by the API Terms, you'll comply with applicable law in using generated content, which may require the provision of[attribution](https://ai.google.dev/api/rest/v1beta/CitationMetadata)to your users when returned as part of an API call. Use discretion before relying on generated content, including[code](https://g.co/legal/generative-code). You're responsible for your use of generated content, and for the use of that content by anyone you share it with.

## Unpaid Services

Any Services that are offered free of charge like direct interactions with Google AI Studio or unpaid quota in Gemini API are unpaid Services (the "**Unpaid Services**").

### How Google Uses Your Data

When you use Unpaid Services, including, for example, Google AI Studio and the unpaid quota on Gemini API, Google uses the content you submit to the Services and any generated responses to provide, improve, and develop Google products and services and machine learning technologies, including Google's enterprise features, products, and services, consistent with our[Privacy Policy](https://policies.google.com/privacy).

To help with quality and improve our products, human reviewers may read, annotate, and process your API input and output. Google takes steps to protect your privacy as part of this process. This includes disconnecting this data from your Google Account, API key, and Cloud project before reviewers see or annotate it.**Do not submit sensitive, confidential, or personal information to the Unpaid Services.**

The license you grant to Google under the "[Submission of Content](https://developers.google.com/terms#b_submission_of_content)" section in the API Terms also extends, to the extent required under applicable law for our use, to any content (e.g., prompts, including associated system instructions, cached content, and files such as images, videos, or documents) you submit to the Services and to any generated responses.

Google only uses content that you import or upload to our model tuning feature for that express purpose. Tuning content may be retained in connection with your tuned models for purposes of re-tuning when supported models change. When you delete a tuned model, the related tuning content is also deleted.

If you're in the European Economic Area, Switzerland, or the United Kingdom, the terms under "[How Google uses Your Data](https://ai.google.dev/gemini-api/terms#data-use-paid)" in "[Paid Services](https://ai.google.dev/gemini-api/terms#paid-services)" apply to all Services, including Google AI Studio and unpaid quota in the Gemini API, even though they are offered free of charge.

## Paid Services

When a Service is being offered for a fee, it is considered to be a paid Service (the "**Paid Services** "). When you activate a[Cloud Billing account](https://cloud.google.com/billing/docs/concepts), all use of Gemini API and Google AI Studio is a "Paid Service" with respect to how Google Uses Your Data, even when using Services that are offered free of charge, such as Google AI Studio and unpaid quota of Gemini API.

For Paid Services, "Google" as used in these Terms has the meaning given[here](https://cloud.google.com/terms/google-entity).

### How Google Uses Your Data

When you use Paid Services, including, for example, the paid quota of the Gemini API, Google doesn't use your prompts (including associated system instructions, cached content, and files such as images, videos, or documents) or responses to improve our products, and will process your prompts and responses in accordance with the[Data Processing Addendum for Products Where Google is a Data Processor](https://business.safety.google/processorterms/). For Paid Services, Google logs prompts and responses for a limited period of time, solely for the purpose of detecting violations of the[Prohibited Use Policy](https://policies.google.com/terms/generative-ai/use-policy)and any required legal or regulatory disclosures. This data may be stored transiently or cached in any country in which Google or its agents maintain facilities.

Other data we collect while providing the Paid Services to you, such as account information and settings, billing history, direct communications and feedback, and usage details (e.g., information about usage including token count per prompt and response, operational status, safety filter triggers, software errors and crash reports, authentication details, quality and performance metrics, and other technical details necessary for Google to operate and maintain Services, which may include device identifiers, identifiers from cookies or tokens, and IP addresses) remains subject to the[Google Controller-Controller Data Protection Terms](https://business.safety.google/controllerterms/)and[Google Privacy Policy](https://policies.google.com/privacy)referenced in the API Terms.

When using Grounding with Google Search, additional data is collected and used, as detailed in the "[Grounding with Google Search](https://ai.google.dev/gemini-api/terms#grounding-with-google-search)" section below.

### Payment Terms

Billing and payments for Paid Services are handled by[Cloud Billing](https://cloud.google.com/billing/docs/concepts)in the Google Cloud Platform.

As such, Section 2 (Payment Terms) and Section 14 (Miscellaneous) of the[Google Cloud Platform Terms of Service](https://cloud.google.com/terms)govern payments, invoicing, billing, payment disputes, and related issues, while these Terms govern your use of the Paid Services. These Terms do not govern your direct use of any Google Cloud Platform service (including those listed on the[Google Cloud Platform Services Summary](https://cloud.google.com/terms/services)).

"**Fees** " (as used in the[Google Cloud Platform Terms of Service](https://cloud.google.com/terms)) for Paid Services are as specified on our[pricing](https://ai.google.dev/pricing)page. Google may make changes to this pricing from time to time, effective 30 days after they are posted unless otherwise specified (or in the case of new Paid Services, where pricing takes effect immediately unless otherwise specified). Your continued use of the Paid Services constitutes your consent to those changes.

## Agentic Services

When using agentic services, including the Computer Use API, you are solely responsible for the actions and tasks performed by the service, such as determining whether the service is appropriate for your use case, authorizing the service's access and connection to data, applications, and systems, and exercising judgment and supervision when and if the service is used in production environments. You will not automatically bypass any requests for human confirmation.

## Grounding with Google Search

"Grounding with Google Search" is a Service that provides Grounded Results and Search Suggestions and can be used through Google AI Studio (as an Unpaid Service), and via Gemini API as a (Paid Service). "Grounded Results" mean responses that Google generates using the prompt from the end user, (or from you, when using function calling), contextual information that you may provide (as applicable), and results from Google's search engine. "Search Suggestions" mean search suggestions that Google provides with the Grounded Results. If a Grounded Result is clicked on, separate terms (not these terms) govern the destination page. If a Search Suggestion is clicked on the[Google Terms of Service](https://policies.google.com/terms)govern the[google.com](http://google.com)destination page. "Links" are any other means to fetch web pages (including hyperlinks and URLs), which may be contained in a Grounded Result or Search Suggestion. Links also include titles or labels provided with those means to fetch web pages. Excluding your web domain(s), you will not assert ownership rights in any intellectual property in Search Suggestions or Links in Grounded Results.

### Use Restrictions

- You will only use Grounding with Google Search in an application that is owned and operated by you and will only display the Grounded Results with the associated Search Suggestion(s) to the end user who submitted the prompt.
- You will not, and will not allow your end user or any third party to, cache, frame, syndicate, resell, analyze, train on, or otherwise learn from Grounded Results or Search Suggestions. For clarity, Grounded Results, Search Suggestions, and Links are intended to be used in combination to respond to a given End User prompt and it is a violation of these terms to use Grounding with Google Search to extract or collect one or more of these components for another purpose (for example, using programmatic or automated means to collect Links, using Links to build an index, or using Links to identify destination pages for crawling or scraping).
- You will not, and will not allow your end user or any third party to, copy, store, or implement any click tracking, Link-tracking or other monitoring of Grounded Results or Search Suggestions, except that:
  - You may copy and store, for up to two (2) years, the text of the Grounded Result(s): (1) that were displayed by you only to evaluate and optimize the display of the Grounded Results in your application; (2) in chat history of an end user of your application only for the purpose of allowing that end user to view their chat history; and (3) temporarily for the purpose of resubmitting the text of the Grounded Result in a subsequent prompt that you submit to Google via a function call to obtain a refined or improved Grounded Result to display to the End User, as long as the developer: (i) does not use the interim Grounded Results for any other purpose; (ii) deletes any Grounded Result that is not displayed to the End User once the final Grounded Result is generated; and (iii) displays any associated Search Suggestions or other Links (as applicable) with the final Grounded Result (up to a maximum of 5 Search Suggestions) to the End User.
  - You may copy and store the Grounded Result and Search Suggestions solely for the purpose of and for the minimum time necessary to comply with applicable law or regulations.
  - You may allow end user(s) to copy and store individual Grounded Results that were displayed to them through your application as long as you do not allow Grounded Results to be accessed or collected by automated or programmatic means or to be used to create a database.
  - You may monitor end user interactions with your application interface; however, you will not track whether those interactions were specifically with a given Search Suggestion or Grounded Result (in each case, in whole or in part, including any specific Link).
- Unless permitted by Google in writing, you: (1) will not modify, or intersperse any other content with, the Grounded Results or Search Suggestions; and (2) will not place any interstitial content between any Link or Search Suggestions and the associated destination page, redirect end users away from the destination pages, or minimize, remove, or otherwise inhibit the full and complete display of any destination page.

### Data Collection and How Google Uses Your Data

In addition to the general terms above ("How Google Uses Your Data" under "[Unpaid Services](https://ai.google.dev/gemini-api/terms#unpaid-services)" and "[Paid Services](https://ai.google.dev/gemini-api/terms#paid-services)"), when using Grounding with Google Search, Google will store prompts, contextual information that you may provide, and output for thirty (30) days for the purposes of creating Grounded Results and Search Suggestions and the stored information can be used for debugging and testing of systems that support Grounding with Google Search. When using Grounding with Google Search via paid quota of Gemini API, this processing for debugging and testing of systems is in accordance with the[Data Processing Addendum for Products Where Google is a Data Processor](https://business.safety.google/processorterms/).

This subsection "Grounding with Google Search" will survive termination of the Agreement, as applicable.

The[Client Application Guidelines](https://support.google.com/adsense/answer/10926790)apply to your use of Grounding with Google Search. For purposes of the Client Application Guidelines, your applications that are using Grounding with Google Search are considered Approved Applications.

## Grounding with Google Maps

"Grounding with Google Maps" is a Service that provides Google Maps Grounded Results as a feature of Gemini API. "Google Maps Grounded Results" mean responses that Google generates using Google Maps Data in response to an end user initiated prompt. "Google Maps Data" means the content originating from Google Maps in the Google Maps Grounded Results, including in the output text, in the metadata of the Google Maps Grounded Results, in the Google Maps Links, and content accessed through Google Maps Links. "Google Maps Links" mean the URLs that Google provides in a Google Maps Grounded Result and any titles or labels provided with those URLs. If Google Maps Links are clicked on, these separate[Google Maps End User Terms](https://maps.google.com/help/terms_maps.html)and the[Google Privacy Policy](https://policies.google.com/privacy)govern the destination page. Google Maps Data in the text of a Google Maps Grounded Result will be identified via the Google Maps Links. Notwithstanding anything to the contrary in the Agreement, Google and its content providers retain all rights to Google Maps Data.

### Use restrictions

1. You will only use Grounding with Google Maps in an application that is owned and operated by you and will only use Grounding with Google Maps to display the Google Maps Grounded Results with the associated Google Maps Links to the end user who initiated the prompt. An end user is an individual you permit to use your application.

2. You will not modify the Google Maps Grounded Result or intersperse any other content with the Google Maps Grounded Result, place any interstitial content between the text of the Google Maps Grounded Result and the Google Maps Links or the Google Maps Links and the associated destination page, or redirect end users away from the destination pages or minimize, remove, or otherwise inhibit the full and complete display of any destination page.

3. You will comply with the Documentation for Grounding with Google Maps.

4. You will not, and will not allow your end users or any third party to:

   1. cache or store Google Maps Grounded Results except that you may cache or store Google Maps Grounded Results:

      1. for up to ninety (90) days, only to evaluate and optimize the display of the Google Maps Grounded Results for your application; or,

      2. in the chat history of an end user in your application for up to six (6) months for the purpose of allowing that end user to view their chat history or to maintain prior conversation context for that end user within your application (Section 4 (a) overrides any cache header);

   2. scrape or export any Google Maps Data;

   3. train on any Google Maps Data; or

   4. distribute or market any Customer Applications in any Prohibited Territory as defined in the Documentation.

### Data Collection and How Google Uses Your Data

You acknowledge that it is reasonably necessary for Google to store prompts, contextual information that you may provide, and generated content for thirty (30) days for the purposes of creating Google Maps Grounded Results, and since such information is being stored, you instruct Google that the stored information can be used for debugging and testing of systems that support Grounding with Google Maps. When using Grounding with Google Maps via paid quota of Gemini API, this processing for debugging and testing of systems is in accordance with the[Data Processing Addendum for Products Where Google is a Data Processor](https://business.safety.google/processorterms/).

This subsection "Grounding with Google Maps" will survive termination of the Agreement, as applicable.

## Hardware Safety

The following additional terms apply to models that can be used to control robots or other robotic hardware ("**Robotics Models**").

You acknowledge and agree that the Robotics Models have not been tested with all makes and models of robotics hardware, and therefore, that the performance and safety of the Robotics Models in connection with your hardware is not guaranteed or provided with a warranty of any kind. You therefore agree to operate any hardware or other products that you may use in connection with the Robotics Models in a safe manner, and completely at your own risk. The Robotics Models may act in an unpredictable or unexpected manner when used in connection with robotics hardware. You therefore agree to use discretion before using the Robotics Models in a production, commercial, or public environment, and to not use the Robotics Models for safety-critical applications or work, such as in the following settings: (i) healthcare, (ii) transportation, or (iii) other areas where safety protocols are vital, and a malfunction could reasonably foreseeably lead to death, personal injury, or property damage.

## **Disclaimers**

**The Services include experimental technology and may sometimes provide inaccurate or offensive content that doesn't represent Google's views.**

**Use discretion before relying on, publishing, or otherwise using content provided by the Services.**

**Don't rely on the Services for medical, legal, financial, or other professional advice. Any content regarding those topics is provided for informational purposes only and is not a substitute for advice from a qualified professional. Content does not constitute medical treatment or diagnosis.**
| **Note:** Previous versions of these Additional Terms are[archived here](https://ai.google.dev/gemini-api/terms-archive).