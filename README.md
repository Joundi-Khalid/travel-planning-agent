# travel-planning-agent
End-to-end multi-agent AI travel planner built with LangGraph. A supervisor agent orchestrates specialist agents to find flats &amp; hotels and build day-by-day itineraries — with MCP tool integration, guardrails, and human-in-the-loop approval.

## Steps to follow:
1.Install uv if not installed :
pip install uv
2.execute : uv init 
3.execute : uv add 'langgraph==1.2.2' 'langchain==1.3.2' 'langchain-groq==1.1.3' 'langchain-community==0.4.2' 'langchain-tavily==0.2.18' 'psycopg[binary]==3.3.4' 'psycopg_pool==3.3.1' 'python-dotenv==1.2.2' 'tavily-python==0.7.24' 'requests==2.34.2' 'langgraph-checkpoint-postgres==3.1.0' 'airportsdata==20260315' 'pycountry==26.2.16' 'fastapi==0.136.3' 'uvicorn==0.48.0' 'jinja2==3.1.6’

4.Execute :  .venv/Scripts/activate 

for  3. in "steps to follow"  , you can add this dependencies via  uv add -r .\requirement.txt
the content of requirement will be :

langgraph==1.2.2
langchain==1.3.2
langchain-groq==1.1.3
langchain-community==0.4.2
langchain-tavily==0.2.18
psycopg[binary]==3.3.4
psycopg_pool==3.3.1
python-dotenv==1.2.2
tavily-python==0.7.24
requests==2.34.2
langgraph-checkpoint-postgres==3.1.0
airportsdata==20260315
pycountry==26.2.16
fastapi==0.136.3
uvicorn==0.48.0
jinja2==3.1.6

# Add All needed key to your Project

GROQ_API_KEY="...."
DATABASE_URL= ...
AVIATIONSTACK_API_KEY= "...."
TAVILY_API_KEY="... "
DEFAULT_ORIGIN_DATA="Casablanca"
LANGSMITH_TRACING="true"
LANGSMITH_ENDPOINT="http://api.smith.langchain.com"
LANGSMITH_API_KEY="......"
LANGSMITH_PROJECT="......"


