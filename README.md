# LLM Chat Template

## Jinja 2.0 format

### Qwen 2.5 Coder Instruct

[Qwen2.5.jinja](./qwen2.5-coder-instruct.jinja)

You can set system prompt message as a variable.
Please replace the "default_system_message" with your system prompt.

```jinja
{# qwen_template.jinja - Jinja template for Qwen 2.5 Chat Models #}
{%- set default_system_message = 'You are Qwen, created by Alibaba Cloud. You are a helpful assistant.' -%} {# Define default system message variable #}
```
