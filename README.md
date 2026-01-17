# 📑Validação de Upload e Cloud Storage

## 📝 Descrição
Breve explicação do que foi testado e qual era o objetivo (ex: Garantir que o upload de imagens funciona corretamente e segue os padrões de segurança).

## 🛠️ Ferramentas e Ambiente
* **Ferramenta:** Postman
* **Ambiente:** Preview (AWS ECS)
* **Método HTTP:** [EX: PATCH / POST / GET]
* **Autenticação:** Bearer Token

## 🎯 Cenários de Validação (Checklist)
- ✅ **Status Code:** Validação de sucesso (ex: 200 OK).
- ✅ **Regra de Negócio:** [Ex: Verificação de UUID no nome do ficheiro].
- ✅ **Integração:** [Ex: Validação de link via CDN CloudFront].
- ✅ **Contrato JSON:** Validação da estrutura dos campos retornados.

## 📸 Evidência Técnica
> **Nota de Privacidade:** Dados sensíveis (tokens e informações pessoais) foram ocultados para garantir a segurança da plataforma e conformidade com a LGPD.

![Legenda da Imagem](docs/nome-da-tua-imagem.png)

## 💡 Conclusão
Descreve aqui se o teste passou ou se encontraste algum bug que precisou de correção. Isso mostra a tua capacidade analítica.
Pastas: Alocação correta no diretório /media/professional_photos/.

CDN: URL de retorno via CloudFront para performance.

Status: Resposta 200 OK em 1.20s.
