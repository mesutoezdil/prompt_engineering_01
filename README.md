Prompt Engineering Project

This project demonstrates the use of the Prediction Guard API for natural language processing tasks.

1. Initialize the Go module:
```
go mod init prompt_engineering_01
```

2. Install the required dependency:
```
go get github.com/predictionguard/go-client
```

3. Create the main Go file (`main.go`) with the provided code.

4. Create a context file:
```
touch context1.txt
```

5. Set the API key as an environment variable:
```
export PGKEY="your_api_key_here"
```

6. Run the program:
```
go run main.go
```

7. If you encounter a model-related error, update the model name in the code to "Hermes-2-Pro-Llama-3-8B".

8. Check the content of the context file:
```
cat context1.txt
```

9. Update the context file with relevant information:
```
echo "In July 2024, we added a new endpoint /v2/analyze to our API, expanding its capabilities for data analysis." > context1.txt
```

10. Run the program again to see the improved results:
```
go run main.go
```

11. Experiment with different questions by modifying the query in the `main()` function of `main.go`.

Here's a template you can use for your README.md:





# Prompt Engineering Project

This project demonstrates the use of the Prediction Guard API for natural language processing tasks.

## Setup

1. Initialize the Go module:
   ```
   go mod init prompt_engineering_01
   ```

2. Install the required dependency:
   ```
   go get github.com/predictionguard/go-client
   ```

3. Create a `main.go` file with the provided code.

4. Create a context file:
   ```
   touch context1.txt
   ```

5. Set your Prediction Guard API key as an environment variable:
   ```
   export PGKEY="your_api_key_here"
   ```

## Usage

1. Run the program:
   ```
   go run main.go
   ```

2. If you encounter a model-related error, update the model name in the code to "Hermes-2-Pro-Llama-3-8B".

3. Check the content of the context file:
   ```
   cat context1.txt
   ```

4. Update the context file with relevant information:
   ```
   echo "Your context information here" > context1.txt
   ```

5. Run the program again to see the results:
   ```
   go run main.go
   ```

6. Experiment with different questions by modifying the query in the `main()` function of `main.go`.

## Troubleshooting

- Ensure your API key is correctly set and you have access to the specified model in your Prediction Guard account.
- If you're not getting the expected results, try adjusting the context in `context1.txt` or modifying the question in the code.

## Further Development

- Experiment with different models, contexts, and questions to explore the capabilities of the Prediction Guard API.
- Adjust the `MaxTokens` and `Temperature` parameters in the code to see how they affect the output.
