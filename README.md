```mermaid
flowchart TD
    A[Usuário digita no chat] --> B[Chat Trigger]
    B --> C[HTTP Request API]
    C --> D["Processamento (IF + lógica)"]
    D --> E["Gemini (IA)"]
    E --> F[Resposta ao usuário]
