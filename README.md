# 📑Validação de Upload e Cloud Storage

## 📝 Descrição
Breve explicação do que foi testado e qual era o objetivo (ex: Garantir que o upload de imagens funciona corretamente e segue os padrões de segurança).

## 🛠️ Ferramentas e Ambiente
* **Ferramenta:** Postman
* **Ambiente:** Preview (AWS ECS)
* **Método HTTP:** [EX: PATCH / POST / GET]
* **Autenticação:** Bearer Token

## 🎯 Cenários de Validação (Checklist)
✅ Status Code: Validação de sucesso (200 OK) com tempo de resposta de 1.20s.

✅ Regra de Negócio: Substituição do nome original por identificador único UUID.

✅ Integração: Armazenamento em diretórios S3 e entrega via link CloudFront.

✅ Contrato JSON: Validação da estrutura de resposta e campos retornados.

## 📸 Evidência Técnica
> **Nota de Privacidade:** Dados sensíveis (tokens e informações pessoais) foram ocultados para garantir a segurança da plataforma e conformidade com a LGPD.

Resultado do Upload<img width="1352" height="690" alt="atividadeqa" src="https://github.com/user-attachments/assets/4162cd7e-2c9f-4d1f-b4f1-3fed32a94500"/>


## 💡 Conclusão
A validação confirma que a regra de negócio para persistência de dados em nuvem foi aplicada com sucesso. O sistema garante a unicidade dos arquivos via UUID e a eficiência na entrega através da CDN, reduzindo a latência e eliminando riscos de sobreposição de ficheiros no S3. 

🌟 Deixe sua estrelinha!

Se você gostou do projeto, não esqueça de **dar uma estrelinha ⭐** para apoiar e acompanhar meus próximos projetos! 💖  

---

<div align="center">

🌸 **Obrigada por acompanhar a validação deste teste!** 🌸  
💌 Seu apoio me motiva a continuar aprendendo e criando 💕  

<img src="sakura.gif" width="220" alt="Sakura piscando fofinha">

<br>

✨ **Deixe uma estrelinha!** ✨  
⭐ 👉 [Clique aqui e deixe seu apoio!](#)

<p align="center">
  Feito com carinho por <b>Suelem Martins</b> 💖  
</p>

</div>

🐞💻 Testado por

 Suelem Carla Martins
📍 Blumenau - SC
📧 suelemnascinto@gmail.com
   
