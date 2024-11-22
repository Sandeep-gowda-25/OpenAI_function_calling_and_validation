# Function Calling and Response Format Validation

##### In this, code to explore funcation calling ability of LLM (OpenAI) is explained with an example, where LLM decides on function which should be called and also frames arguments for the same. Upon function execution, same can be again looped back into LLM's followup call, so no context will be lost in the flow and final answer can be derived.
![image](https://github.com/user-attachments/assets/1fa7b047-e055-4c1f-959f-41719525a53e)

##### Also, have added code for simple validation of response format from LLM calls using Pydantic and have maked difference between validating with data class agains pydantic.
![image](https://github.com/user-attachments/assets/ae19700d-e36e-411a-8ecc-bb769d26dbad)
