# AI Tool Evaluation Checklist
This project provides a comprehensive framework for evaluating AI tools for use within a library context. It includes detailed instructions and a checklist covering key areas such as usability, accuracy, accessibility, privacy, ethical considerations, environmental impact, integration, and customization. The goal is to facilitate an objective and thorough assessment of AI tools, ensuring their suitability and alignment with library needs and values. There are two accompanying checklist aids (Microsoft Word and PDF) in this repository and below are the instructions and guidance on using the checklists.

# Instructions for Evaluating an AI Tool
These instructions guide you through the process of evaluating an AI tool using the provided checklist. The goal is to provide a comprehensive and objective assessment of the tool's suitability for use within the library context. This evaluation considers various aspects, including usability, accuracy, accessibility, ethical considerations, and environmental impact.

## Preparation and Background Research
1.  **Identify the Target Tool:** Clearly identify the specific AI tool you are evaluating. Note that this checklist is designed to evaluate the overall tool or platform, not individual underlying models in isolation (but does take the models into consideration).

2.  **Gather Documentation:** Collect all available documentation related to the AI tool. This includes:
    * User manuals and guides
    * Technical specifications
    * Privacy policies
    * Terms of service
    * Model cards (if available)
    * Provider websites and publications (including sustainability reports, blog posts, press releases)
    * Any relevant academic papers or independent reviews of the tool.

3.  **Familiarize Yourself:** Spend time using the AI tool directly. Experiment with various features, query types, and settings. This hands-on experience is crucial for a thorough evaluation.

4.  **Understand the Context:** Indicate on the checklist the intended uses for this tool. Consider the intended use cases for the AI tool within the library environment. How might it be used by staff, students, or researchers? This context will inform your evaluation.

## Evaluation Process
1.  **Holistic Assessment:** Evaluate the AI tool as a whole, considering the interplay of its various features and characteristics. Do not focus solely on isolated aspects or individual model performance. Consider the entire user experience and the tool's overall impact.

2.  **Define Best Practices:** Establish organizations that publish best practices. Three organization’s best practices and specifications to consider are: [Green Software Foundation](https://sci.greensoftware.foundation/), [Open Source Initiative (OSI) Open Source AI Definition](https://opensource.org/ai/open-source-ai-definition), [Association of Research Libraries guiding principles for Artificial Intelligence](https://www.arl.org/news/association-of-research-libraries-releases-guiding-principles-for-artificial-intelligence/). These references are reputable suggestions, but an individual evaluator or evaluation team may define their own set of best practices and specification frameworks.

3.  **Comparative Analysis:** Where possible, compare the tool's performance and features with similar available tools.

4.  **Criterion-by-Criterion Review:** Work through each category and criterion in the checklist systematically. For each criterion:
    * **Read the Definition:** Carefully review the description of the criterion and any associated notes.
    * **Gather Evidence:** Collect evidence from your hands-on experience, documentation review, and any other relevant sources.
    * **Checking the Criteria:** The specific rules for applying checkmarks should be agreed upon by the team before starting the evaluation. A checkmark can indicate that a criterion is met sufficiently, is surpassed, or is greatly surpassed. The degree to which the criteria are met is to be determined by the evaluation team.

## Reporting
* Summarize your findings in a clear and concise report. Include key strengths and weaknesses, and any recommendations for adoption or further investigation.
* Be prepared to justify your evaluation to stakeholders.

## Iterative Process
* This is a living document. As AI technology evolves we may need to revise and update the checklist.
* The evaluation itself may be iterative. As you learn more about the tool, you may need to revisit earlier assessments.

## Key Principles
* **Objectivity:** Strive for objectivity in your evaluation. Base your judgments on evidence, not personal preferences.
* **Thoroughness:** Be thorough and comprehensive in your assessment.
* **Contextualization:** Keep the specific needs and context of the library environment in mind throughout the evaluation.
* **Transparency:** Document your reasoning and evidence clearly.

## Testing Documentation
* **Input:** Copy and paste the exact prompt, query, or input you provided to the AI tool. Be precise, even small variations in wording can affect results.
* **Actual Output:** Copy and paste the complete output generated by the AI tool. If the output is very long (e.g., a long article), you can summarize, but always include a link or reference to the full output if it's stored elsewhere. If the output includes images, code, or other non-textual elements, capture those as well (e.g., screenshots, file downloads).
* **Observations:** Note any observations about the tool's behavior, including:
    * Response/compute time (how long it took to generate the output).
    * Any errors or unexpected behavior.
    * Instances of bias, inaccuracy, or inappropriate content.
    * Any positive aspects, such as particularly helpful or insightful responses.
    * Any usability issues encountered.
    * If there are changes of behavior of the tool during the testing process.
* **Settings:** If the AI tool has configurable settings (e.g., temperature, Top-p, different model choices), document the exact settings used for each test.
* **Types of Inputs/Prompts:** Aim for a variety of input/prompt types to test different aspects of the AI tool's capabilities.
* **Data Management:** Keep your testing log and any associated files (screenshots, outputs) well-organized and easily accessible. Ensure naming conventions and file structures are consistent so results can be compared across different testers or time periods.

## Evaluation Criteria

### Usability
* **Ease of Use:** How well can a user determine the purpose of the tool? How intuitive and easy is the AI tool to navigate for users with varying levels of technical expertise? Can users easily find and understand all the tool's capabilities? Consider the clarity of instructions, user interface design, and the learning curve for new users.

* **Efficiency:** How well does the AI tool provide prompt and timely responses to user queries? Evaluate the response time, the AI tool’s ability to handle requests simultaneously from multiple users (scalability) and multiple related queries in rapid succession (session management), and the overall efficiency in completing tasks.

* **Limitations:** Are there hard usage limitations, such as the number of prompts (tokens) allowed within a given time period or throttling of response times? If limitations exist, are the limitations clearly communicated to the user before they encounter them?

* **Model Parameter Customization:** Can the model parameters be adjusted by the user such as the temperature, Top-p, Top-k, or presence penalty?

* **User Satisfaction:** Does the AI tool answer your questions with little friction? Do users feel the tool is worth using compared to traditional methods and what is their willingness to continue using the AI tool? Consider factors such as satisfaction with the AI tool’s helpfulness, ease of use, and overall experience.

### Accuracy and Reliability
* **Accuracy of Responses:** How well does the AI tool provide accurate and reliable information? Does the tool provide sources or citations to support its claims (and are those sources reliable)? Is the information up-to-date, especially for rapidly changing fields? Evaluate the AI tool’s responses against authoritative sources and assess the frequency of errors or misleading information. Are the responses to similar prompts consistent? How well does the tool explain its reasoning when requested?

* **Contextual Awareness:** How well does the AI tool understand the context of user queries and provide relevant responses? Does the tool have the ability to maintain context across multiple turns in a conversation? Evaluate the AI tool’s ability to interpret user intent and provide information that aligns with the specific research needs.

### Accessibility and Inclusivity
* **WCAG 2.1 AA Compliance:** Is the AI tool accessible to users with various disabilities? If a web-based tool, does it adhere to WCAG (Web Content Accessibility Guidelines) 2.2 Level AA or higher? Evaluate the AI tools compliance with accessibility standards, such as providing text-to-speech capabilities, alternative text for images, and keyboard navigation.

* **Multilingual Support:** Does the AI tool support multiple languages to cater to the diverse needs of the university community? Consider "quality of translation" separately from "accuracy", a translation might be accurate but still awkward or unnatural. Evaluate the AI tool’s ability to understand and respond to queries in different languages and the accuracy of translations.

### Privacy, Consent and Security
* **Data Protection:** Does the AI tool protect user data and comply with relevant privacy regulations and University policy? If there is potential for handling student data, is the tool FERPA compliant? If handling patient health information, is the tool HIPAA compliant? Consider "data retention policy", how long is user data stored, and for what purpose? Evaluate the AI Tool’s data encryption methods, data storage practices, and its adherence to privacy policies.

* **Data Usage Transparency:** Is the AI tool transparent about its data collection and usage practices? Evaluate the AI tool’s privacy policy and its clarity in informing users about how their data is collected, stored, and used.

### Ethical and Environmental Considerations
* **Cultural Sensitivity and Bias:** How free is the AI tool from biases that could discriminate against certain groups or individuals, for example gender bias, racial bias, ageism, bias related to disability, or socioeconomic bias. Evaluate the AI tool’s responses for fairness, objectivity, and its ability to avoid perpetuating stereotypes.

* **Accountability:** What accountability mechanisms are in place for the AI tool’s actions and responses. Is there a process for reviewing and updating the AI tool's behavior in response to feedback? Evaluate the procedures for addressing errors, biases, or inappropriate content generated by the AI tool. (Additionally, see environmental impact section below)

* **Model Transparency:** Is a model card (detailed information about the model) easily accessible to the user and prominently displayed? Information about the data that was used to train the model, the creators of the model, its intended uses & potential limitations, including biases and ethical considerations as detailed in [Mitchell, 2018](https://arxiv.org/abs/1810.03993), and the model’s evaluation results ([Info on a model card](https://huggingface.co/docs/hub/en/model-cards#what-are-model-cards)). Does the model card include a section detailing the energy consumption or estimated carbon emissions associated with training the model?

### Environmental Impact
**NOTE:** It's important to distinguish between the energy used to train the model (a one-time, though potentially very large, cost) and the energy used for inference (each time the model is used to answer a query).

* **Model Card Environmental Information:** For the models used within the AI Tool, do their model cards include a section detailing the energy consumption and/or estimated carbon emissions associated with training the model? This should ideally include:
    * Information on the type and quantity of hardware used.
    * Information about the energy source used to power the training infrastructure (e.g., renewable energy, grid mix).
    * An estimate of the total carbon dioxide equivalent (CO2e) emissions generated during training.

* **Tools and Dashboards for Impact Tracking:** Does the AI tool offer any reporting tools or dashboards that quantify the environmental impact of using the tool (e.g., energy consumed, emissions generated)?

* **Provider's Environmental Statement:** Does the AI tool provider (the company or organization) have a publicly available statement or report addressing its overall environmental impact and sustainability efforts? This might be part of a broader Corporate Social Responsibility (CSR) report or a dedicated sustainability page. Do they reference the [Software Carbon Intensity (SCI) specification system](https://greensoftware.foundation/), or similar specifications for calculating the rate of carbon emissions?

### Integration and Customization
If the AI tool being evaluated is a standalone desktop application with no intended integration with other systems, mark this entire "Integration" section as "N/A" (Not Applicable) in the scoring. Provide a brief justification in the notes.

* **Integration with Existing Library Systems:** How well does the AI tool integrate with the library's existing catalog, databases, and other digital resources? Can the AI tool be easily embedded within existing library websites, portals, or applications? (e.g., widgets, or custom integrations).

* **API Access:** Does the tool offer an API for integration with other applications or services? What functions does the API support? (e.g., submitting queries, retrieving results, managing user accounts, accessing usage statistics). Are these functions sufficient for the library's needs? Are there any rate limits or usage restrictions on the API? Are these limits reasonable and clearly communicated?

* **Authentication and Authorization:** Does the AI tool integrate with the library's existing authentication system (e.g., Shibboleth, LDAP)?

* **Interface Customization:** Can the AI tool's user interface (UI) be customized to match the library's branding (e.g., logos, colors, fonts)? Can the layout or presentation of information be adjusted?

* **Functionality Customization:** Can the AI tool's core functionality be modified or extended through configuration options, plugins, or custom scripts? Can the tool be configured to prioritize certain data sources or types of information?

