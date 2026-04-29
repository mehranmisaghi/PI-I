# Uma pequena introdução sobre GitHub

## O que é o GitHub?

O **GitHub** pode ser definido como uma plataforma online usada para guardar projetos e códigos.

**Pense nele como:**
- Um **Google Drive para desenvolvedores**
- Um lugar onde você pode **salvar, organizar e compartilhar projetos**

---

## O que vamos fazer agora?
### Vamos criar conta:

1. Acesse: https://github.com
2. Clique em **Sign up**
3. Preencha:
   - E-mail
   - Senha
   - Nome de usuário
4. Confirme o código enviado por email
5. Escolha o plano **gratuito**

🎉 Pronto! Sua conta foi criada.

---

## O que você vai ver primeiro?

-  **Repositories** → seus projetos
- **Profile** → seu perfil
- **Botão +** → criar coisas novas

---

##  Criar um Repositório

Um repositório é como uma **pasta do seu projeto**.


1. Clique no botão ➕ (canto superior direito)
2. Clique em **New repository**
3. Preencha:
   - Nome (Coloque **P_Integrador**)
   - Descrição (Este repositório é para fazer os exercícios do **Projeto Integrador**)
4. Escolha:
   -  _Public_ (para repositório público)
5. Marque:
   - _Add a README_
6. Clique em **Create repository**

>Seu reepositório criado com sucesso!

---

## Se você precisar instalar Git no seu computador

1. Acesse: https://git-scm.com
2. Baixe o instalador
3. Clique em **Next** até finalizar

---
## O que é Clonar um Repositório?

Clonar = **fazer download de um repositóriodo GitHub para o seu computador**.

---
## Clonar um Repositório

### 🔗 No GitHub:

1. Abra seu repositório
2. Clique em **Code (botão verde)**
3. Copie o link HTTPS

Exemplo:
```
https://github.com/seu-usuario/meu-projeto.git
```

---

###  No computador:

1. Abra o terminal
2. Vá até a pasta desejada:
```
cd Desktop
```

3. Execute:
```
git clone https://github.com/seu-usuario/meu-projeto.git
```

_Repositório foi clonado no seu computador._

---

## para entrar numa pasta

```
cd meu-repositorio
```

---

##  Para editandr um Arquivo

1. Abra o arquivo `README.md`
2. Escreva seu nome
3. Salve

---

## Enviandr alterações (Commit e Push)


1. Ver alterações:
```
git status
```

2. Preparar arquivos:
```
git add .
```

3. Criar versão:
```
git commit -m "Atualizei o README"
```

4. Enviar para o GitHub:
```
git push
```

Alterações enviadas!

---

## Resumo

| Termo | Significado |
|------|------------|
| Repositório | Pasta do projeto |
| Clone | Baixar projeto |
| Commit | Salvar mudanças |
| Push | Enviar para GitHub |
| Pull | Atualizar projeto |

---

## Algumas Dicas

- Use nomes simples
- Escreva mensagens claras (commit)

---

## Vamos exercitar

1. Criar conta no GitHub
2. Criar repositório:
```
aula-github
```
3. Clonar
4. Editar README com seu nome
5. Fazer commit e push

Se conseguiu, você já sabe o básico!

---
### [Voltar](README.md)