#Validation Framework (Guardrails)

 ## What is Guardrails? 

Guardrails mainly known as Validation framework in context to LLM (Large Language Models), serve as quality checks to ensure model outputs meet reliability standards in real-world applications, particularly verifying alignment with predefined specifications (like JSON structure).

## Why Guardrails?

Guardrails ensure that Language Model outputs are accurate, compliant with the right format, contain correct information, and are free from harmful content, while also safeguarding against adversarial input to maintain content quality and safety. It makes sure that output just doesn't sound good but is also syntactically as well as factually correct.

## How to apply Guardreails?

Majorly there are 5 ways of applying guardrails to any Language Model, which a user can modify as per their use case. Those are: 
<ul>
  <li> Structural guidance ->  It provides direct control over outputs and offers a more precise method to ensure that output conforms to a specific structure or format.​</li>
  <li> Syntactic guardrails -  These include checking if categorical output is within a set of acceptable choices, or if numeric output is within an expected range.​</li>
  <b><li> Content safety guardrails - These verify that the output has no harmful or inappropriate content. ​</li></b>
  <li> Semantic/factuality guardrails  - These confirm that the output is semantically relevant to the input. ​</li>
  <li> Input guardrails - These limit the types of input the model will respond to, helping to mitigate the risk of the model responding to inappropriate or adversarial prompts which would lead to generating harmful content.</li>
</ul>

##
