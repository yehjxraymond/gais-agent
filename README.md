##

## Development

The project uses Poetry for dependency management.

### Installing Dependencies

```
poetry install
```

### Activating Virtual Environment

```
poetry shell
```

## Setting up the environment

```
cd trip_planner
cp .env.example .env
```

Update the environment variable with SERPER API KEY and choose a LLM (OpenAI is recommended)

## Running the Agents

```
crewai install
crewai run
```

