Code templates for llm agents

in 

local_llm = "llama3.1"
llm = ChatOllama(model=local_llm, 
                 temperature=0)

removed responsetype=json, now works fine