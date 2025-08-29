# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM

To evaluate and compare the effectiveness of different prompting techniques—**zero-shot, few-shot, chain-of-thought, and role-based prompting**—across multiple AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in the task of **text summarization**.

---

## SCENARIO

### Step 1

**Task:** Summarize the following 500-word article on *“The Basics of Blockchain Technology”* in **120–150 words** for undergraduate students.
**Requirement:** Keep it **clear, structured, and beginner-friendly**.

**Sample Output (Step 1):**
Blockchain is a decentralized digital ledger that records transactions securely across a network of computers. Unlike traditional systems where a central authority controls data, blockchain distributes information to all participants, making it transparent and tamper-resistant. Each record is stored in a “block” and linked in sequence, forming a “chain.” The technology relies on cryptography for security and consensus mechanisms to verify transactions. This ensures trust without intermediaries like banks. Originally developed for Bitcoin, blockchain is now applied in finance, supply chain management, healthcare, and even voting systems. Its advantages include security, transparency, and reduced costs, though challenges like energy use and scalability remain. Overall, blockchain is reshaping industries by enabling peer-to-peer transactions in a secure and efficient way.

---

### Step 2 (Feedback Revision)

**Task:** Revise the summary to make it even simpler and include **at least two real-world examples** of blockchain applications.

**Revised Output (Step 2):**
Blockchain is like a digital notebook that is shared and updated across many computers, making it very hard to cheat or change. Instead of one company controlling the data, everyone in the network has the same copy, which builds trust. Information is stored in blocks and linked together, so every change is visible. For example, in banking, blockchain is used for faster and cheaper money transfers without needing middlemen. In supply chains, it helps track products like food or medicine to ensure they are genuine and safe. While it offers benefits like transparency and security, challenges such as high energy use still exist. Overall, blockchain is an innovative way to share information safely and is now used in many industries worldwide.

---

## ALGORITHM

1. **Input Selection** – Provide the original text/article (“The Basics of Blockchain Technology”).
2. **Prompting Method Application** – Apply different prompting techniques:

   * **Zero-shot prompting**: Directly ask the model to summarize without examples.
   * **Few-shot prompting**: Give 1–2 examples of good summaries before asking for the target summary.
   * **Chain-of-thought prompting**: Ask the model to reason step by step before writing the final summary.
   * **Role-based prompting**: Instruct the model to act as a teacher or expert simplifying the concept.
3. **Cross-Platform Testing** – Run the same prompts across **ChatGPT, Gemini, Claude, Copilot** (or chosen AI tools).
4. **Output Collection** – Gather summaries from each platform and prompting style.
5. **Evaluation Criteria** – Compare outputs based on:

   * Clarity & simplicity
   * Word limit (120–150 words)
   * Beginner-friendliness
   * Use of real-world examples (in Step 2)
6. **Feedback & Revision** – Refine outputs using additional prompts (as in Step 2).
7. **Result Documentation** – Record findings in a comparative table/chart.

---

## RESULT

<img width="1536" height="672" alt="Gemini_Generated_Image_u0tb2ju0tb2ju0tb" src="https://github.com/user-attachments/assets/2118d04d-1df1-4ac5-9d05-17e497244b87" />


**Conclusion:** Prompting strategies significantly affect the quality of AI-generated summaries. Role-based and few-shot prompting gave the best results for undergraduate-level understanding.

---
