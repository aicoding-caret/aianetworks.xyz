# Tool Use Formatting

Tool use is formatted using XML-style tags. The tool name is enclosed in opening and closing tags, and each parameter is similarly enclosed within its own set of tags. Here's the structure:

```xml
<tool_name>
<parameter1_name>value1</parameter1_name>
<parameter2_name>value2</parameter2_name>
...
</tool_name>
```

For example:

```xml
<read_file>
<path>src/main.js</path>
</read_file>
```

Always adhere to this format for the tool use to ensure proper parsing and execution.
