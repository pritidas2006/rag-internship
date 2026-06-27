# Week 2 Domain Plan: University Admission RAG Assistant

## 1. Project Title
* University Admission RAG Assistant

## 2. Target User
* Prospective students, parents, and applicants looking for university admission details.

## 3. Problem Statement
* Applicants often struggle to find specific information about eligibility, tuition fees, and deadlines scattered across multiple long PDF brochures. This RAG assistant will provide direct, grounded answers based on official university documents.

## 4. Documents to be Used
* `university admission faq pdf.pdf`
* `university fees sturcture.pdf`
* `university pdf 1.pdf`

## 5. Five Expected Questions
1. What are the eligibility criteria for undergraduate courses?
2. What is the application deadline for the upcoming academic year?
3. How much is the tuition fee per semester for engineering courses?
4. What documents do I need to submit along with the application form?
5. Who can I contact if I face issues during online registration?

## 6. Questions the System Should Not Answer (Out of Scope)
* Can you reduce the fee for me?
* Which university is better, this one or Harvard?
* What is the password for my student portal account?

## 7. Success Criteria
* The system retrieves the correct PDF chunks for admission and fee-related queries.
* The chatbot strictly provides answers grounded in the uploaded PDFs and does not hallucinate facts.
