[03-escopo-eap.md](https://github.com/user-attachments/files/30235324/03-escopo-eap.md)
# 🧱 Escopo e Estrutura Analítica do Projeto (EAP/WBS)

## Declaração de escopo
<!-- Descrição clara do que será entregue -->

## EAP (Mermaid)

```mermaid
graph TD
    P[Projeto] --> F1[1. Iniciação]
    P --> F2[2. Planejamento]
    P --> F3[3. Execução]
    P --> F4[4. Monitoramento]
    P --> F5[5. Encerramento]

    F1 --> F1a[1.1 TAP]
    F1 --> F1b[1.2 Stakeholders]
    F2 --> F2a[2.1 Cronograma]
    F2 --> F2b[2.2 Riscos]
    F3 --> F3a[3.1 Desenvolvimento]
    F3 --> F3b[3.2 Testes]
    F5 --> F5a[5.1 Lições aprendidas]
    F5 --> F5b[5.2 TEP]
```

## Dicionário da EAP
| Código | Pacote de trabalho | Entrega | Critério de aceite |
|--------|--------------------|---------|--------------------|
| 1.1    | TAP                | Documento assinado | Aprovação do sponsor |
