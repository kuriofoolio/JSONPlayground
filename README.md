# JSONPlayground
The codebase provides some interactions with .json and .jsonl file formats

# Setting up the environment
## json and jsonlines importation 
The most important modules to import are **json** and **jsonlines**
-  `import json`
-  `import jsonlines`

The other modules included the project can be imported at leisure

# Basic file operations
## Reading a file 
```
with jsonlines.open(f'{PATH}/{file_name}.jsonl') as reader:\n",
    "        for obj in reader:\n",
    "            ...",
```

## Writing to a file
```
with jsonlines.open(f'{PATH}/{file_name}.jsonl', mode='a') as writer:\n",
    "        ...",
```