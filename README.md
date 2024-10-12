# Sample NGINX reverse proxy for NVIDIA Cloud Functions

This is a sample nginx configuration to be a reverse proxy for NVCF

Goals:

- Do basic authorization of the user
- User server secret for authorization when invoking the cloud function
- Support OpenAI API clients
- Support multiple cloud functions through routing
- Support streaming
