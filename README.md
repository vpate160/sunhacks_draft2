# Research Paper Knowledge Graph

An intelligent interactive knowledge graph that analyzes research papers and creates connections between related publications using AI.

## Features

- 🧠 **AI-Powered Analysis**: Uses LLM to extract concepts and create intelligent connections
- 🕸️ **Interactive Network**: Drag-and-drop visualization of paper relationships  
- 🔍 **Smart Recommendations**: Finds related publications through multi-hop connections
- 📊 **Relevance Ranking**: Orders results by similarity scores and connection strength
- 🛤️ **Path Visualization**: Shows how concepts are interconnected
- 🤖 **GraphRAG**: Ask natural language questions and get AI-powered answers using graph reasoning
- 🎯 **Semantic Search**: Find papers by meaning, not just keywords
- 🌐 **Concept Exploration**: Navigate research concepts and their relationships
- 💡 **Research Insights**: Get AI-generated insights about research patterns and opportunities

## Setup

1. Install dependencies:
```bash
npm install
npm run install-client
```

2. Create `.env` file:
```bash
OPENAI_API_KEY=your_openai_api_key_here
PORT=5000
```

3. Run the application:
```bash
# Option 1: Use the startup script
./start-app.sh

# Option 2: Start servers separately
# Terminal 1 (Backend):
npm start

# Terminal 2 (Frontend):
cd client && npm start
```

## Usage

1. Upload your research papers CSV file (Title, Link columns)
2. Let the AI analyze and create connections between papers
3. Explore the interactive knowledge graph
4. Click on nodes to see paper details and related publications
5. Use the search and filtering features to find specific topics

## Technology Stack

- **Backend**: Node.js, Express, OpenAI API
- **Frontend**: React, D3.js, Material-UI
- **AI**: OpenAI GPT for concept extraction and similarity analysis
- **Visualization**: D3.js force-directed graph
