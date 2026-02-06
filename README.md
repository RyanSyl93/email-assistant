# email-assistant
AI Email Classifier Assistant
Designed and implemented an AI assistant that classifies insurance‑style customer emails (claims, complaints, renewals, policy changes) and drafts suggested responses using Python and open‑source LLMs.
Experimented with prompt engineering on a 7B‑class instruction‑tuned model to control tone, structure and policy‑aligned responses, comparing prompt‑only and fine‑tuned approaches.Fine‑tuned an open‑source LLM on a synthetic dataset of customer emails using parameter‑efficient methods (LoRA/QLoRA with the Hugging Face PEFT library), tracking experiments and models with MLflow. Built on a FastAPI microservice exposing /classify and /draft-reply endpoints, containerised with Docker, with basic logging, health checks and CI pipeline integration to mirror real‑world MLOps practices.

# Inital Setup Notes

## Install poetry

pipx install poetry

## Install Dependencies

poetry install 