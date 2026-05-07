# Olmeda Forms

Sistema de formulários dinâmicos para coleta de dados em clientes Olmeda Agency.

## 🚀 Como Usar

### Formulário de Senhas (Brasil te Ama Institute)

```
https://amandaalmeidda.github.io/olmeda-forms/form.html?form=passwords&client=brasil-te-ama
```

**Parâmetros:**
- `form=passwords` — Tipo de formulário
- `client=brasil-te-ama` — ID do cliente

### Adicionar Novo Formulário

Para adicionar um novo formulário:

1. Vá para a [Master Google Sheet](https://docs.google.com/spreadsheets/d/1ffvH3er0Q5n8SSSBxS4AaYjti7vjh4Gxx6K2mt3t3Aw)
2. Adicione uma linha em `forms_index` com o novo formulário
3. Crie uma nova aba `form_questions_{form_id}` com as perguntas
4. Use a URL: `form.html?form={form_id}&client={client_id}`

## 📋 Estrutura

- `form.html` — Formulário dinâmico único
- Carrega config da Google Sheet via Apps Script
- Salva respostas no Drive do cliente

## 🔗 Referências

- **Master Config:** [Google Sheet](https://docs.google.com/spreadsheets/d/1ffvH3er0Q5n8SSSBxS4AaYjti7vjh4Gxx6K2mt3t3Aw)
- **Apps Script:** Backend que processa formulários
- **Documentação:** [olmeda-operations/templates/forms](https://github.com/amandaalmeidda/olmeda-operations/tree/master/templates/forms)

## 🎨 Design

Utiliza o Olmeda Agency Design System:
- Cores: Purple (#37254c), Lilac (#CFC1E8), Cream (#f4e6bb)
- Fontes: Cormorant Garamond + Inter
- Responsivo para mobile

## 📁 Clientes Suportados

| Cliente | Pasta Drive | Status |
|---------|------------|--------|
| Brasil te Ama | 103VwochrngdL3CrSXHNr3op1-RaUOm8d | ✅ Ativo |

---

**Mantido por:** Olmeda Agency  
**Última atualização:** Maio 2026
