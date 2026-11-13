# Karen (Carl) Nurlybekov

Computing Science graduate (TRU, April 2026) in Victoria, BC. I build Python and Django systems that other people run: a document pipeline a client adopted, a gait-analysis web app with Stripe subscriptions, and before that a 16-month government service desk. Looking for junior data/BI analyst, IT support / systems analyst, or junior developer roles, remote in Canada or on Vancouver Island.

## Current work

- **Software Developer (Contract), (emergency and disaster management consultancy), May 2026 – present. Django 6 email-evidence system (Postfix → Maildir → workers that parse, de-duplicate and tag mail against a per-tenant taxonomy), a multi-tenant emergency-plan generator with Postgres row-level security and pgvector hybrid search, deployed as a Coolify Docker Compose stack with pg_dump backups. Private repository.
- **Software Developer, Walking Reset AI**, Jul 2026 – present. [walkingreset.app](https://walkingreset.app): a phone video of someone walking becomes a written gait report. MediaPipe pose estimation, schema-validated Claude tool calls, Django/Celery/Postgres on Azure Container Apps, Stripe subscriptions, English/Russian/German. Private repository.

## Selected public repositories

| Repo | What it is | Stack |
|---|---|---|
| [knowledgebase](https://github.com/knurlybekov/knowledgebase) | Permission-aware knowledge assistant over Google Drive / SharePoint: hybrid retrieval with cited answers, agentic deep investigation, verified records | Django, PostgreSQL + pgvector, Celery, HTMX |
| [novamart-analytics](https://github.com/knurlybekov/novamart-analytics) | E-commerce operations analysis: 166K+ records through a Medallion pipeline in Snowflake, hypothesis-tested bottlenecks, 5-page Power BI dashboard | Snowflake, SQL, Power BI, DAX, Python |
| [llm_classifier_interface](https://github.com/knurlybekov/llm_classifier_interface) | News classifier: TF-IDF shortlist + fine-tuned Mistral-7B (QLoRA) behind a REST API; 0.82 macro F1 against a Random Forest baseline | PyTorch, Hugging Face, Django REST |
| [timeseries_forecasting](https://github.com/knurlybekov/timeseries_forecasting) | S&P 500 forecasting benchmarked against an efficient-market baseline, Monte Carlo risk, paper-trading bot | scikit-learn, Alpaca, AWS Lambda |
| [ToolApp](https://github.com/knurlybekov/ToolApp) | Tools, employees and work zones on a Folium/Leaflet map with Plotly usage reports; built for the Acres Enterprises Industry Innovation Competition (TRU, 2023) | Flask, Azure SQL, Folium, Plotly |
| [socialnetworkBackend](https://github.com/knurlybekov/socialnetworkBackend) | Subscription social-network API with social OAuth | Django REST Framework, PostgreSQL, Docker |
| [HelpDesk](https://github.com/knurlybekov/HelpDesk) | IT help-desk ticketing desktop app with email notifications and service-quality reporting (diploma project) | C#/.NET WinForms |

Capstone (private, client code): led a 4-person team building a multi-agent RAG pipeline for emergency-management regulatory documents, turning them into machine-readable rulesets for Innomergence Solutions; delivered on the semester deadline and adopted by the client, which led to the contract above.

## Skills

**Data and BI:** SQL (Snowflake, PostgreSQL, Azure SQL, SQL Server), Power BI and DAX, pandas, dimensional and Medallion modelling, hypothesis testing (Mann–Whitney U, chi-square)
**Backend:** Python, Django and Django REST Framework, Flask, Celery/Redis, PostgreSQL with pgvector, Docker Compose, Linux VPS deployment, Azure Container Apps
**ML and LLMs:** PyTorch, scikit-learn, Hugging Face, QLoRA fine-tuning, RAG with hybrid retrieval, Anthropic and OpenAI APIs with schema-validated tool calls, n8n automation
**IT support:** ITIL-style ticketing (OTRS), Active Directory and Exchange, Windows fleet support; 98% first-contact resolution across a 400-device government fleet
**Also:** C#, JavaScript, Folium/Leaflet web maps

## Education

Bachelor of Computing Science, Thompson Rivers University (2021–2026); UREAP undergraduate research award, Dean's List. Diploma in Computer Technology & Software, Turan College (with honours). English and Russian.

## Contact

[LinkedIn](https://www.linkedin.com/in/karennurlybekov/) · nurlybekov.karen@gmail.com · Victoria, BC
