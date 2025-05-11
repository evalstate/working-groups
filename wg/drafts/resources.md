# MCP Resources

## Introduction

This document. This document uses the term **Client** to refer to the MCP Client, and **Host** to refer to the coordinating application. 

### Tools

**Tools** are a good starting because they allow the MCP Server developer to:
- Populate LLM Context via Tool Descriptions
- Use LLM API's structured outputs[^1] to create valid function calls for the Tool
- Provide.

Further most modern LLMs show good error recovery, resilience and retry capabilities to "learn" how to use Tools if their first tool call gave unexepcted results or an error.

A large number of Tools can "glue" by returning `text/plain` content that is freely tokenizable by LLMs.

#### Limitations

- Context Hungry. Tool definitions consume context space regardless of whether they are being called or not. Some Host 
- Context Hungry (2). Tool Calls and Results are usually added to the Context cumulatively. 

#### Summary

Low effort, medium reward. Tool focussed Servers can also 

### Resources

Effective use of Resources requires a level of coordination between Host and Server developer.


Inversion of control

## Adoption


