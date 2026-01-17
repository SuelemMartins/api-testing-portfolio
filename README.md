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

![Legenda da Imagem](<img width="1352" height="690" alt="atividadeqa" src="https://github.com/user-attachments/assets/4162cd7e-2c9f-4d1f-b4f1-3fed32a94500" />
.png)

## 💡 Conclusão
A validação confirma que a regra de negócio para persistência de dados em nuvem foi aplicada com sucesso. O sistema garante a unicidade dos arquivos via UUID e a eficiência na entrega através da CDN, reduzindo a latência e eliminando riscos de sobreposição de ficheiros no S3.
