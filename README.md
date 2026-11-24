# -ClaimSaathi-Multimodal-AI-Assistant-for-Health-Insurance-Claim-Disputes
–	Built a multimodal AI assistant that checks rejected health-insurance claims against policy wording, IRDAI regulations and past Insurance Ombudsman decisions, and drafts escalation letters in Indian languages
–	Engineered a data pipeline that turns Ombudsman award PDFs into a validated dataset (LLM extraction, Pydantic, data-quality checks) and trained a LightGBM outcome model with Optuna tuning and SHAP explanations
–	Implemented hybrid RAG (embeddings, BM25, reranking) in a LangGraph agent with cited answers
–	Built a document-vision pipeline (OpenCV preprocessing, CNN classifier, YOLOv8 segmentation, OCR benchmark) and deployed the system as Dockerised FastAPI services with a React frontend
–	Tech Stack: Python, PyTorch, OpenCV, YOLOv8, LightGBM, LangGraph, FastAPI, PostgreSQL, Docker
