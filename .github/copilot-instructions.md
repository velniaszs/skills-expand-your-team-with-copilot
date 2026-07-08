## Development Environment

For setup, install dependencies with `pip install -r src/requirements.txt` and run MongoDB locally (the backend connects to `mongodb://localhost:27017/`). For more details, refer to our [Development Guide](../docs/how-to-develop.md).

### User Interaction

Consider the following when communicating with the staff.

- The staff is not technical. Explain in simple terms as much as possible and avoid software jargon.
- Any new code must be easy to maintain and understand, without significant coding experience.

## Program architecture

- The website users are the students and teachers. Make sure the user experience is simple.
- Do not introduce additional apps or services beyond the existing FastAPI app and MongoDB.
- Do not make command line tools.
- Do not create a long single file application. Always use an easy-to-understand directory structure.
- Only use HTML, CSS, JavaScript, and Python. No other languages.
