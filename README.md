# AI-Powered Task Optimizer–
Automated AI-Powered Prompt Optimization Framework

This project implements an automated system for optimizing AI prompts using genetic algorithms and machine learning techniques. It's designed to evolve and improve any LLM prompt. 

```javascript
const inputs = [
  {
    text: "<Question to ask the model>",
    foldername: "foldername_for_the_input_output",
  },
];

export default inputs;
```
`additionalSystemPrompts.ts`**: Create and populate the `additionalSystemPrompts.ts` file with the following format:

```javascript
const additionalSystemPrompts = [
  "System Prompt 1",
  "System Prompt 2",
  "System Prompt 3",
  "System Prompt 4",
  "System Prompt 5",
];

export default additionalSystemPrompts;
```

Create a `.env` file in the root directory of the project and add the following environment variables:

Replace `your_anthropic_api_key`, `your_openai_api_key`, `path_to_your_google_application_credentials_json`, `your_cloud_db_connection_string`, `your_local_db_connection_string`, and `your_model_name` with your actual API keys, the path to your Google application credentials JSON file, your database connection strings, and the model name. You can change the model to an open-source model from Ollama or one from Anthropic by setting the `MODEL_NAME` environment variable.

## Installation

To install the necessary Node.js dependencies, run the following command in the root directory of the project:

```bash
npm install
```

To run TypeScript files directly, you need to install `ts-node`. You can install it globally using the following command:

```bash
npm install -g ts-node
```

Alternatively, you can add it as a dev dependency to your project:

```bash
npm install --save-dev ts-node
```

To install the necessary Python dependencies, ensure you have Python installed and then run the following command in the root directory of the project:

```bash
pip install -r requirements.txt
```

This will install the following Python packages:

- `matplotlib`
- `seaborn`
- `pandas`
