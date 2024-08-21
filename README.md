# kamal-json-schema
An inferred JSON schema for the Kamal YAML configuration

The idea is;

- pass the `kamal docs` outputs (or the files under `/lib/kamal/configuration/docs` in the [Kamal](https://github.com/basecamp/kamal) project) quickly to an LLM or your own script
- produce a JSON schema based on the above
- validate the schema against various configs. Here `lib/kamal/configuration/validator.rb` could possibly come handy.
