# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To design prompts using different prompt structures.

## Scenario:
Students should practice with any one specific application like - Text Summarization or relevant with Project works... From the Basic prompts to upgrade that up to Final out how user defined that.

Basic Prompt
Role Prompt
Context Prompt
Constraint Prompt
Output Format Prompt

## AI Tools required:
ChatGPT, Gemini

## Article: The Importance of Renewable Energy

Polypharmacy Side-Effects Risk Predictor using Quantum Machine Learning is a healthcare-focused project that aims to predict the risk of adverse side effects caused by taking multiple medications simultaneously (polypharmacy). Patients, particularly older adults and those with chronic illnesses, often require several drugs at the same time, increasing the possibility of harmful drug–drug interactions. The proposed system collects patient information such as age, gender, medical history, existing diseases, medication details, dosage, treatment duration, and previous allergic reactions. After preprocessing and encoding the data, a Quantum Machine Learning (QML) model, such as a Variational Quantum Classifier (VQC) or Quantum Neural Network (QNN), is trained to classify the patient's risk level as Low, Medium, or High, or predict whether an adverse side effect is likely to occur. The model can be trained using publicly available datasets such as MIMIC-IV, SIDER, and DrugBank, and its performance can be compared with traditional machine learning algorithms to evaluate the benefits of quantum computing. By identifying high-risk medication combinations before treatment, the system can assist healthcare professionals in making safer prescribing decisions, reducing adverse drug reactions, improving patient safety, supporting personalized medicine, and lowering healthcare costs. Future enhancements include integrating the system with electronic health records, providing personalized dosage recommendations, incorporating explainable AI for transparent predictions, and deploying the solution on cloud-based quantum computing platforms for real-time clinical decision support.

## Prompts
### Basic Prompt
Predict the risk of polypharmacy side effects using Quantum Machine Learning.

---
### Role Prompt
You are an expert content summarizer, summarize the following article in a clear and concise manner.

---
### Context Prompt
You are an expert content summarizer.
The following article is intended for first-year engineering students who need to quickly understand the key concepts of renewable energy before a class discussion.
Summarize the article while highlighting the main ideas.

---

### Constraint Prompt
You are an expert content summarizer.

The following article is for first-year engineering students preparing for an exam.

Summarize the article using these constraints:
- Keep the summary between 120 and 150 words.
- Include only the most important points.
- Do not include personal opinions.
- Use simple and easy-to-understand language.
- Avoid copying complete sentences from the article.

---
### Output Format Prompt (Final Prompt)
You are an expert content summarizer.

The following article is for first-year engineering students preparing for an exam.

Instructions:
- Summarize the article in 120–150 words.
- Use simple language.
- Include only key points.
- Maintain a neutral tone.
- Do not add new information.

Present the output in the following format:

Title:
<Short title>

Summary:
<120–150-word summary>

Key Takeaways:
• Point 1
• Point 2
• Point 3
• Point 4
• Point 5

---

## Output
### ChatGPT
#### Basic Prompt
Summary:

To predict the risk of polypharmacy side effects by analyzing patient and medication data using Quantum Machine Learning (QML), and classify the risk as Low, Medium, or High to support safer treatment decisions.

---

#### Role Prompt
Summary:

Renewable energy sources such as solar, wind, hydroelectric, and geothermal power are vital for addressing climate change and reducing dependence on fossil fuels. They produce fewer greenhouse gas emissions, improve air quality, and help protect the environment. In addition to environmental benefits, renewable energy creates jobs, lowers electricity costs through technological advancements, and strengthens energy security by reducing reliance on imported fuels.

Despite challenges such as weather-dependent power generation, energy storage needs, and infrastructure investments, continued innovation and supportive government policies are driving progress. International cooperation and individual actions, including energy conservation and the adoption of clean technologies, also contribute to the transition. Overall, renewable energy is essential for achieving a sustainable, secure, and economically beneficial future.

---
#### Context Prompt
**Summary for First-Year Engineering Students**

Renewable energy refers to naturally replenished energy sources such as **solar, wind, hydroelectric, and geothermal power**. Unlike fossil fuels, these sources produce much lower greenhouse gas emissions, making them essential for reducing climate change and protecting the environment.

The main benefits of renewable energy include:

* **Environmental protection:** Reduces carbon dioxide emissions, improves air quality, and helps combat global warming.
* **Economic growth:** Creates jobs in manufacturing, installation, maintenance, and research while lowering electricity costs as technology improves.
* **Energy security:** Reduces dependence on imported fossil fuels, providing a more stable and reliable energy supply.

However, renewable energy also faces challenges. Solar and wind power depend on weather conditions, requiring efficient **energy storage systems** (such as batteries) and investments in modern power grids to ensure a reliable electricity supply.

Governments support renewable energy through policies, subsidies, and incentives, while international cooperation helps countries work together to reduce emissions. Individuals can also contribute by conserving electricity, using energy-efficient appliances, and choosing renewable energy sources.

**Key Takeaway:** Renewable energy is a crucial part of a sustainable future because it reduces pollution, supports economic development, improves energy security, and helps address climate change. Continued technological innovation, government support, and public participation are essential for its widespread adoption.


---

#### Constraint Prompt

**Summary (120–150 words):**

Renewable energy includes sources such as solar, wind, hydroelectric, and geothermal power that are naturally replenished and produce much lower greenhouse gas emissions than fossil fuels. It plays an important role in reducing climate change, improving air quality, and protecting the environment. The renewable energy sector also supports economic growth by creating jobs and providing more affordable electricity as technology advances. Another key benefit is improved energy security, as countries can rely more on local energy resources instead of imported fuels. However, renewable energy has challenges, including weather-dependent power generation, the need for efficient energy storage systems, and investment in modern electricity grids. Governments encourage its adoption through policies, subsidies, and incentives, while international cooperation helps reduce global emissions. Individuals can also contribute by saving energy and using energy-efficient technologies. Renewable energy is essential for a sustainable and secure future.

---

#### Output Format Prompt
**Title:**
Renewable Energy and Its Importance

**Summary:**
Renewable energy includes natural sources such as solar, wind, hydroelectric, and geothermal power that can be replenished over time. These energy sources produce fewer greenhouse gas emissions than fossil fuels, helping to reduce climate change and improve air quality. They also support economic growth by creating jobs and reducing electricity costs as technology improves. Renewable energy increases energy security by reducing dependence on imported fossil fuels. However, it also faces challenges, including weather-dependent power generation, the need for reliable energy storage systems, and investment in modern power grids. Governments promote renewable energy through policies, subsidies, and incentives, while international cooperation supports efforts to reduce emissions. Individuals can also contribute by conserving electricity and using energy-efficient technologies. Renewable energy is an important part of building a cleaner, more sustainable, and secure energy future.

**Key Takeaways:**

* Renewable energy comes from naturally replenished sources such as solar, wind, hydroelectric, and geothermal power.
* It helps reduce greenhouse gas emissions and supports environmental protection.
* It creates jobs, lowers electricity costs, and improves energy security.
* Challenges include weather dependence, energy storage, and infrastructure development.
* Government policies, global cooperation, and public participation support the transition to renewable energy.

---

### Gemini

#### Basic Prompt
```
The Polypharmacy Side-Effects Risk Predictor using Quantum Machine Learning (QML) is a healthcare system that uses quantum algorithms (like Variational Quantum Classifiers and Quantum Neural Networks) to predict and classify the risk of adverse drug-drug interactions into Low, Medium, or High risk levels.

By analyzing patient demographics, medical history, and medication profiles sourced from datasets like MIMIC-IV and SIDER, the system assists healthcare professionals in making safer prescribing decisions, minimizing adverse drug reactions, and supporting personalized medicine.
```

#### Role Prompt
Here is a concise summary of **The Importance of Renewable Energy**:

---

## Executive Summary

The transition from fossil fuels to naturally replenished energy sources—such as solar, wind, hydro, and geothermal—is essential for addressing climate change, boosting economies, and securing energy independence worldwide.

---

## Core Pillars & Insights

* **Environmental Impact:** Renewable energy generates significantly lower greenhouse gas emissions, directly lowering carbon footprints, improving air quality, and helping meet international climate targets.
* **Economic Growth:** The sector creates millions of global jobs in manufacturing, installation, and research. Ongoing technological advances have made solar and wind among the most cost-effective electricity sources available.
* **National & Energy Security:** Utilizing domestic clean energy reduces reliance on imported fossil fuels, protecting nations from supply chain disruptions and price volatility in global fuel markets.
* **Key Challenges:** Weather-dependent power generation (intermittency) requires investments in advanced battery storage technologies and modernized power grid infrastructure.
* **Action & Solutions:** Achieving a clean energy future depends on a combination of supportive government policies/subsidies, international climate agreements, continuous tech innovation, and individual adoption of energy-efficient habits.

---

#### Context Prompt
Here is the exam-focused summary:

Renewable energy sources like solar, wind, hydro, and geothermal naturally replenish and produce minimal greenhouse gases compared to fossil fuels. Adopting clean energy reduces carbon emissions, combats global warming, improves air quality, and protects global ecosystems.

Economically, the sector generates millions of jobs in manufacturing, installation, and research. Technological progress has also made wind and solar among the cheapest electricity options. Furthermore, relying on local clean power enhances national energy security by minimizing reliance on imported fuels and stabilizing energy markets.

However, primary challenges include generation intermittency due to weather dependency and the high cost of modernizing power grids. Overcoming these hurdles requires advanced battery storage, supportive government policies, incentives, and international cooperation. Ultimately, combining technological innovation with individual energy-saving habits is essential for building a sustainable future.

---

#### Constraint Prompt

Here is the summary tailored for your exam preparation:

Renewable energy comes from self-replenishing sources such as solar, wind, hydro, and geothermal. Unlike fossil fuels, these technologies emit fewer greenhouse gases, helping mitigate climate change and improve air quality. Economically, the industry creates millions of global jobs, with technological advances significantly lowering power generation costs for solar and wind. Utilizing local resources also strengthens energy security by reducing reliance on imported fuels.

However, key technical challenges persist, particularly supply intermittency caused by weather reliance and the need for upgraded grid infrastructure. Overcoming these obstacles depends heavily on developing advanced battery storage systems. A successful transition requires strong government policy, financial incentives, international agreements, and individual energy conservation. Ultimately, combining engineering innovation with supportive legislation is crucial for establishing a stable, clean energy grid for the future.

---

#### Output Format Prompt
Title:
Overview of Renewable Energy Systems

Summary:
Renewable energy sources like solar, wind, hydro, and geothermal naturally replenish and produce minimal greenhouse gases compared to traditional fossil fuels. Transitioning to clean energy reduces carbon emissions, mitigates climate change, and improves global air quality. Economically, the sector drives job creation across manufacturing and research, while technological advances have rendered solar and wind among the cheapest electricity sources. Developing domestic energy resources also strengthens national security by reducing dependence on imported fuels and stabilizing energy markets. However, engineering challenges remain, particularly supply intermittency due to weather dependency and the need for updated grid infrastructure. Overcoming these hurdles requires advanced battery storage systems alongside supportive government policies, international agreements, and public participation. Ultimately, merging engineering innovation with strategic policy is vital for building a sustainable power grid.

Key Takeaways:
• Renewable sources naturally replenish and emit significantly lower greenhouse gases than fossil fuels.
• Expanding clean energy boosts economic growth, job creation, and national energy independence.
• Main technical challenges include supply intermittency and necessary power grid modernizations.
• Advanced energy storage technologies like batteries are critical for ensuring grid reliability.
• Successful adoption relies on government policy, technological innovation, and individual energy efficiency.

---

## Comparison Table

| Prompt Type | ChatGPT | Gemini |
|-------------|:-------:|:------:|
| Basic Prompt | **8.5/10** | **8.0/10** |
| Role Prompt | **9.2/10** | **9.0/10** |
| Context Prompt | **9.5/10** | **9.3/10** |
| Constraint Prompt | **9.8/10** | **9.7/10** |
| Output Format Prompt | **10/10** | **9.9/10** |
| **Overall Rating** | **9.4/10** | **9.2/10** |

## Conclusion

The experiment demonstrates that prompt engineering significantly improves the quality of AI-generated summaries. As prompts become more specific—from Basic to Output Format Prompt—the responses become increasingly accurate, organized, and aligned with user expectations. Both ChatGPT and Gemini successfully followed the given instructions. ChatGPT consistently produced more detailed and student-friendly summaries, while Gemini generated well-structured and concise responses with a slightly more formal tone. Overall, the **Output Format Prompt** produced the best results because it clearly specified the role, context, constraints, and expected format, leading to the most consistent and high-quality summaries.


