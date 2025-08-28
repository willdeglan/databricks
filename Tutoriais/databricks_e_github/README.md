%md
# DATABRICKS AND GITHUB
Como Configurar o Databricks para sincronizar tudo que vc ta fazendo no GitHub e Vice-versa 
---
### **Primeira parte:** Configurar o `Github`
1. devidamente logado no GitHub, clique na sua foto na parte _superior direita_ da pagina e depois em `Settings`
<img width="1914" height="750" alt="image" src="https://github.com/user-attachments/assets/7e98efa5-6995-45f1-bd19-488a8450ca71" />

2. na pagina de configuração (settings), localize no final do meno esquerdo, `<> Developer settings`
<img width="1300" height="899" alt="image" src="https://github.com/user-attachments/assets/49a0044f-3ac5-4075-af31-4f4fbb9fe422" />

3. na pagina de configurações de desenvolvedor, clique em `🔑 Personal access tokens` e depois em `Fine-grained tokens`, no pagina que aparecer, clique em `Generate new token`
<img width="1917" height="399" alt="image" src="https://github.com/user-attachments/assets/325048eb-32f5-4aed-9755-fb757082d26e" />

4. vai aparecer os campos de identificação do novo token de acesso
> 4.1. em `Token name *`, digite o nome desejado para o token <br>
> 4.2. em `Description`, digite a descriçao para o token <br>
> 4.3. em `Resouce owner` defina quem é o dono desse token, aconcelho deixar voce mesmo <br>
> 4.4. em `Expiration`, escolha a validade do token <br>
> 4.5. em `Repositorio access`, aconcelho deixar para todos os repositorios (_no databricks, vamos escolher qual vamos usar_) <br>
<img width="1909" height="902" alt="image" src="https://github.com/user-attachments/assets/68e98e9f-0dd7-4edf-a16e-c04861fe85ae" />

5. em `Permissions`, vamos clicar em `+ Add permissions` e marcar duas caixinhas:<br>
> 5.1. `Contents` e `Workflows` (_Perceba que a caixinha `Metadata` vai marcar automaticamente e mostrar o aviso de **Required**_) <br>
> 5.2. É importante que nao esqueça de alterar a opção **Access** das caixinhas para `Read and Write`<br>
> 5.3. agora clicque em `Generate token`<br>
<img width="1360" height="632" alt="image" src="https://github.com/user-attachments/assets/86beebb7-8883-4fd1-8788-26b827b54123" />

6. confirme as permissões e clique em `Generate token`
<img width="1149" height="745" alt="image" src="https://github.com/user-attachments/assets/97fcc35f-68cf-489a-9ca4-c0afae5e267b" />

7. vai ser gerada um token para ser configurado onde terá acesso ao github, no nosso caso, no databricks <br>
⚠️ **CUIDADO** ⚠️<br>
_O token gerado deve ser copiado e ja configurado, pois não será mais possivel retornar para vê-lo novamente_<br>
<img width="1918" height="564" alt="image" src="https://github.com/user-attachments/assets/90bd2e14-5fa5-4af8-b494-6f4a583bb07d" />
