# Structured Outputs

This folder explores how to make LLMs generate outputs in specific structured formats. The accompanying [Kaggle notebook](https://www.kaggle.com/code/jaswanthreddyd/structured-outputs?scriptVersionId=222008600) provides interactive examples.

## Key Concepts Covered

1. **LLM Input Processing**
   - How LLMs understand and process input text
   - Tokenization methods and their tradeoffs
   - BPE (Byte Pair Encoding) and its advantages

2. **Token Prediction**
   - How LLMs predict the next token
   - Sampling strategies (temperature, top-k, top-p)
   - Probability distribution of token predictions

3. **Structured Output Generation**
   - Constraining LLM outputs to specific formats
   - Implementation of format validators using state machines
   - Converting character-level constraints to token-level constraints

## Code Examples

The notebook includes implementations of:
- Basic token prediction and generation
- JSON format validation using state machines
- Table format validation using FSMs (Finite State Machines)
- Constrained text generation with format validation

## Running the Examples

1. Open the [Kaggle notebook](https://www.kaggle.com/code/jaswanthreddyd/structured-outputs?scriptVersionId=222008600)
2. The notebook uses the HuggingFaceTB/SmolLM2-360M model
3. Follow along with the examples to understand each concept

## Key Files

- `structured-outputs.ipynb`: Main notebook with all examples and explanations
- Implementation of format validators and constrained generation

## Dependencies

- torch
- transformers
- numpy
- greenery (for regex processing)
- pyformlang (for FSM implementation) 