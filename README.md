An AI-based resume analysis tool that evaluates resumes against job descriptions, highlights missing skills, improves weak sections using language models, and generates a refined PDF, showcasing end-to-end Python and NLP pipeline development.

It will allows users to upload or paste resumes and job descriptions
Uses semantic embeddings to calculate a compatibility score (%)
Detects skill gaps and missing keywords required for the role
Improves resume content using advanced LLMs (Gemini/Groq/OpenAI)
Suggests relevant interview questions tailored to the job
Produces a polished, downloadable PDF version of the resume

Tech Stacks: Developed using Python 3.11 with a Streamlit-based UI
Implemented semantic matching using NumPy and cosine similarity
Integrated multiple LLM APIs (Gemini, Groq, OpenAI) with configurable support
Generated PDFs using ReportLab
Performed text parsing with regex and string processing techniques
Managed sensitive configurations via Streamlit secrets.toml
